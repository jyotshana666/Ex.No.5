

# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

### Date: 27-02-2026
### Register No: 212224230111

# Aim: To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 



### AI Tools Required: 
ChatGPT


## **Objective**  
- Understand how the same task can be refined into multiple prompting techniques: Zero-shot, Few-shot, Chain-of-Thought.  
- Compare naïve vs. basic prompts across different healthcare-related scenarios.  
- Evaluate outputs in terms of **quality, accuracy, and depth**.  


## **Selected Test Scenarios**  
1. Generating a creative story.  
2. Answering a factual question.  
3. Summarizing an article/concept.  
4. Providing advice/recommendations.  


## **Scenario 1: Generating a Creative Story**  
**Naïve Prompt (Basic):**  
"Write a story about AI in healthcare."

**Zero-Shot Prompt:**  
"Without any examples, write a short story about AI being used in a hospital to help patients."

**Few-Shot Prompt (2 Examples):**  
"Example 1: AI helps doctors detect diseases faster using imaging data.  
Example 2: AI chatbots remind patients to take medicine on time.  
Now, write a new story about AI helping patients in a healthcare setting."  

**Chain-of-Thought Prompt:**  
Step 1: AI is applied in hospitals to assist doctors.  
Step 2: AI monitors patient data in real time.  
Step 3: Predict potential health risks.  
Step 4: Alert doctors for early intervention.  
Step 5: Write a story combining these steps. 

**ChatGPT Response :**  
"In a busy city hospital, AI monitors patient vitals around the clock. One day, it notices unusual heart patterns in a patient and alerts the doctor, who intervenes in time. Meanwhile, AI chatbots guide patients to take their medicines regularly. Thanks to AI, patients recover faster and hospital staff work more efficiently, saving lives every day."

---

## **Scenario 2: Answering a Factual Question**  
**Naïve Prompt:**  
"How does AI help in diagnosing diseases?"

**Zero-Shot Prompt:**  
"Without any examples, explain how AI assists doctors in identifying illnesses."

**Few-Shot Prompt (2 Examples):**  
"Example 1: AI detects cancer cells from X-ray scans.  
Example 2: AI analyzes blood test results to flag anomalies.  
Now, explain another way AI helps in diagnosing diseases."

**Chain-of-Thought Prompt:**  
Step 1: Doctors need to analyze patient data.  
Step 2: AI can review images, lab reports, and symptoms.  
Step 3: AI highlights abnormalities or patterns.  
Step 4: Doctors confirm diagnosis based on AI suggestions.  
Step 5: Explain this process in detail.

**ChatGPT Response :**  
"AI assists doctors by analyzing medical images, lab results, and patient history to identify potential illnesses early. For example, it can detect cancerous cells in scans or flag abnormal blood results. AI acts as a decision support tool, helping doctors make faster and more accurate diagnoses."

---

## **Scenario 3: Summarizing an Article/Concept**  
**Naïve Prompt:**  
"Summarize an article about AI in healthcare."

**Zero-Shot Prompt:**  
"Without prior examples, summarize a passage that discusses AI applications in hospitals and clinics."

**Few-Shot Prompt (2 Examples):**  
"Example 1: AI improves patient monitoring and reduces errors.  
Example 2: AI accelerates drug discovery processes.  
Now summarize another passage describing AI in healthcare."

**Chain-of-Thought Prompt:**  
Step 1: Identify the main points of the article.  
Step 2: Focus on AI applications in hospitals.  
Step 3: Highlight benefits such as efficiency, accuracy, and patient care.  
Step 4: Combine points into a concise summary.

**ChatGPT Response :**  
"AI in healthcare is transforming hospitals by improving patient monitoring, assisting in accurate diagnosis, and enhancing operational efficiency. It also helps in drug discovery and personalized patient care, reducing errors and improving outcomes."

---

## **Scenario 4: Providing Advice/Recommendations**  
**Naïve Prompt:**  
"Give advice on using AI in healthcare."

**Zero-Shot Prompt:**  
"Without examples, suggest how hospitals can implement AI for better patient care."

**Few-Shot Prompt (2 Examples):**  
"Example 1: Use AI to monitor patient vitals in real-time.  
Example 2: Implement AI chatbots to answer patient queries.  
Now give three more ways hospitals can use AI effectively."

**Chain-of-Thought Prompt:**  
"Step 1: Identify hospital challenges.  
Step 2: Think of AI solutions for each challenge.  
Step 3: Suggest practical implementations.  
Step 4: Explain benefits of each solution.  
Step 5: Provide recommendations."

**ChatGPT Response :**  
"Hospitals can implement AI by monitoring patient vitals in real-time, using AI chatbots for patient support, and employing predictive analytics to prevent complications. Additionally, AI can optimize staff scheduling and resource allocation, ensuring better patient care and operational efficiency."  

---

## **Evaluation Table (Quality, Accuracy, Depth: 1–5 scale)**  

| Scenario                       | Prompt Type       | Quality | Accuracy | Depth |  
|--------------------------------|-----------------|---------|---------|-------|  
| Creative Story                  | Naïve            | 3       | 3       | 2     |  
|                                | Basic/Refined    | 5       | 5       | 5     |  
| Answering Factual Question      | Naïve            | 3       | 3       | 2     |  
|                                | Basic/Refined    | 5       | 5       | 5     |  
| Summarizing Article/Concept     | Naïve            | 3       | 3       | 2     |  
|                                | Basic/Refined    | 5       | 5       | 5     |  
| Providing Advice/Recommendations| Naïve            | 3       | 3       | 2     |  
|                                | Basic/Refined    | 5       | 5       | 5     |  

---

## **Analysis:**  
- **Basic/Refined prompts consistently generate higher quality, more accurate, and deeper responses** compared to naïve prompts.  
- Naïve prompts work but often produce vague or incomplete answers.  
- Chain-of-Thought prompting provides structured reasoning, improving clarity and depth.  
- Few-shot prompts improve performance when examples are provided, especially for complex tasks like summarization or advice.  
- Zero-shot prompts work moderately but can miss context or detail if the instruction is too broad.  



## RESULT:

The prompts for all scenarios were executed successfully using different prompting patterns.  
ChatGPT generated meaningful responses, and refined prompts provided clearer and more complete outputs than naive prompts.

