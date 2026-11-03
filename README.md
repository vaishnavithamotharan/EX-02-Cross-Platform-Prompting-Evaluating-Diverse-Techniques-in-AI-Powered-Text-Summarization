# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Algorithm

# Step 1: 
Define the objective of summarizing the 500-word article on “The Basics of Blockchain Technology” for undergraduate students.

# Step 2: 
Select AI platforms such as ChatGPT, Google Gemini, and Claude for comparison.

# Step 3: 
Prepare three prompts using zero-shot, few-shot, and structured prompting techniques.

# Step 4: 
Submit the same article and prompts to each AI platform and collect the generated summaries.

# Step 5: 
Evaluate each summary based on accuracy, coherence, simplicity, speed, and user experience.

# Step 6: 
Assign scores from 1 to 5 for each evaluation criterion and compare the results.

# Step 7: 
Identify the best combination of AI platform and prompting technique based on the overall scores.

# Step 8: 
Present the results in a comparison table and select the most suitable approach for educational content summarization.

## OUTPUT
# 1. INTRODUCTION
Prompting is the process of giving instructions to an Artificial Intelligence system to obtain the required output. Different prompting techniques help improve the quality, accuracy, and presentation of AI-generated responses.

The four prompting techniques used in this experiment are:
1. Zero-Shot Prompting
2. Few-Shot Prompting
3. Chain-of-Thought Prompting
4. Role-Based Prompting
2. ZERO-SHOT PROMPTING
# Definition:

Zero-Shot Prompting is a technique where the AI is given a direct instruction without providing any examples. The model uses its existing knowledge to understand the task and generate an answer.

# Prompt:
Summarize the given 500-word article about the basics of Blockchain Technology in simple English. Include its definition, working process, important features, advantages, and real-world applications. Make the summary short and easy for undergraduate students to understand.



# Picture:


<img width="1290" height="860" alt="image" src="https://github.com/user-attachments/assets/54cf1c66-daa9-4bf6-acad-620f4256550d" />





# Content / Expected Output:

Blockchain is a digital technology used to store and share information securely across a network of computers. It consists of blocks connected in a chain, where each block contains transaction data. Transactions are verified by network participants before being added to the blockchain. It provides transparency, security, and decentralization. Blockchain is widely used in cryptocurrency, banking, healthcare, and supply chain management.

# Observation:
Zero-Shot Prompting generates a direct summary without requiring examples.
# 3. FEW-SHOT PROMPTING
# Definition:

Few-Shot Prompting is a technique where the AI is provided with a small number of examples before performing the actual task. These examples guide the AI to produce the output in the required style and format.

# Prompt:
Summarize the Blockchain Technology article using the following examples.

Example 1:
Input: Artificial Intelligence enables machines to perform tasks that normally require human intelligence.
Output: AI helps machines perform intelligent tasks.

Example 2:
Input: Cloud computing provides storage and computing services through the internet.
Output: Cloud computing offers online storage and computing facilities.

Now summarize the given article about Blockchain Technology using the same simple writing style. Include its definition, working process, advantages, and applications.



# Picture:


<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/74c3d406-8be1-41d4-b7e1-9b3a9d91abfb" />





# Content / Expected Output:

Blockchain is a secure digital system used to record and share transactions across multiple computers. It stores information in connected blocks and uses cryptographic methods to protect data. Every transaction is verified before being added to the chain. Blockchain provides transparency, security, and reliability. It is commonly used in digital payments, banking, healthcare, and supply chain systems.

# Observation: 
Few-Shot Prompting helps the AI follow a consistent writing style by using examples.
# 4. CHAIN-OF-THOUGHT PROMPTING
# Definition:

Chain-of-Thought Prompting encourages the AI to organize a complex task into logical steps before producing the final answer. It helps generate structured and meaningful responses.

# Prompt:
Analyze the given article about Blockchain Technology. Identify the following important points:
1. Definition of Blockchain.
2. Main components.
3. Working process.
4. Important features.
5. Advantages and applications.
Use these points to prepare a logically organized summary in simple English for undergraduate students. Present only the important findings and the final summary.



# Picture:


<img width="1045" height="860" alt="image" src="https://github.com/user-attachments/assets/58309416-bd8e-4468-b90f-c89224e96c31" />











# Content / Expected Output:

Blockchain technology works through a decentralized network of computers. Its main components include blocks, nodes, transactions, and cryptographic hashes. When a transaction takes place, network participants verify it through a consensus mechanism. After verification, the transaction is added to a block and connected to the existing chain. This process improves security, transparency, and data integrity. Blockchain is useful in finance, healthcare, digital identity, and supply chain management.

# Observation: 
This technique helps organize important information logically and produces a structured summary.
# 5. ROLE-BASED PROMPTING
# Definition:

Role-Based Prompting is a technique where the AI is assigned a specific role, such as a teacher, researcher, or expert. This helps the AI generate responses according to the user's requirements.

# Prompt:
Act as an experienced Computer Science professor. Summarize the given 500-word article about Blockchain Technology for undergraduate students. Explain the definition, working principles, important features, advantages, and real-world applications using simple English. Make the summary informative, clear, and easy to understand.



# Picture:



<img width="700" height="700" alt="image" src="https://github.com/user-attachments/assets/94036d4d-1f18-433a-bdd2-630735a48336" />






# Content / Expected Output:

Blockchain is an advanced digital technology that stores information securely in a distributed network. It consists of connected blocks containing transaction records. Each block is linked using cryptographic hashes, which help protect the information from unauthorized changes. Transactions are verified by network participants using consensus mechanisms. Blockchain offers security, transparency, decentralization, and reliability. It is used in cryptocurrency, banking, healthcare, and supply chain management.

# Observation: 
Role-Based Prompting generates explanations according to a specific role and makes the content suitable for the target audience.
# 6. AI PLATFORMS USED
Different AI platforms are used to test the prompting techniques and compare their generated summaries.

# Picture:


<img width="1290" height="860" alt="image" src="https://github.com/user-attachments/assets/0ef2f6a4-5a80-4bf9-aa0c-a8a22ed0fa56" />






# Content:
S.No	AI Platform	Purpose
1	ChatGPT	Generates clear and informative text summaries.
2	Google Gemini	Provides simple explanations and summaries.
3	Claude	Generates detailed and well-structured content.
4	Microsoft Copilot	Provides quick summaries and useful explanations.


# 7. EVALUATION CRITERIA
The generated summaries are evaluated using the following criteria.
| S.No | Criteria | Explanation |
|---|---|---|
| 1 | Accuracy | Checks whether the information is correct. |
| 2 | Coherence | Checks whether the sentences are logically connected. |
| 3 | Simplicity | Measures how easily students can understand the summary. |
| 4 | Speed | Measures how quickly the AI generates the output. |
| 5 | User Experience | Evaluates readability and overall usefulness. |

# 8. COMPARISON OF PROMPTING TECHNIQUES
| S.No | Prompting Technique | Main Advantage | Expected Performance |
|---|---|---|---|
| 1 | Zero-Shot | Direct and quick response. | Good |
| 2 | Few-Shot | Maintains a consistent output style. | Very Good |
| 3 | Chain-of-Thought | Organizes information logically. | Very Good |
| 4 | Role-Based | Produces audience-specific explanations. | Very Good |

Note: These are expected qualitative ratings. Actual ratings should be based on the outputs generated during testing.
# 9. SAMPLE SUMMARY OF BLOCKCHAIN TECHNOLOGY
Introduction:

Blockchain is a digital technology used to store and manage information securely across a distributed network of computers.

Working Process:
1. A user initiates a transaction.
2. The transaction is shared with the network.
3. Network participants verify the transaction.
4. Verified transactions are added to a block.
5. The block is connected to the existing blockchain.
Advantages:
- Provides data security.
- Improves transparency.
- Reduces the need for intermediaries.
- Maintains reliable transaction records.
Applications:
- Cryptocurrency
- Banking and finance
- Healthcare
- Supply chain management
- Digital identity
10. OVERALL WORKFLOW
Picture / Flowchart:



<img width="1024" height="768" alt="image" src="https://github.com/user-attachments/assets/6ce72c40-7b4e-4c8b-9f48-94adeb1c2de6" />




# Workflow:
<img width="502" height="361" alt="{E9A0B50C-D1F0-4E33-9341-81149FDB0853}" src="https://github.com/user-attachments/assets/f61f6fe5-3c53-47cb-91b8-6e05b66cad20" />

# Conclusion:

Prompting techniques play an important role in obtaining effective results from AI platforms. Each technique has its own advantages. Few-Shot Prompting helps maintain consistency, Chain-of-Thought Prompting supports logical organization, and Role-Based Prompting produces audience-specific explanations. The best combination can be identified by evaluating accuracy, coherence, simplicity, speed, and user experience.

## Result

To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization is successfully completed.
