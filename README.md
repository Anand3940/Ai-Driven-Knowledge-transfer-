# AI-Driven Personalized Learning and Recommendation

This project, based on the research paper "AI-Driven Personalized Learning and Remedial Recommendation Through Knowledge Concept-Centric Evaluation," presents an AI framework to create a personalized learning experience for students.

The system is designed to:
-   Identify gaps in a student's knowledge.
-   Generate questions tailored to the student's level.
-   Provide personalized evaluations and recommendations to help them improve.

## Models Used

The framework uses a combination of advanced AI models:

1.  **Retrieval-Augmented Generation (RAG):** This model is used to automatically generate multiple-choice questions from course materials. It uses **OpenAI's Large Language Models (like GPT-4)** as its main engine, with other models like **Google's Gemini** and **DeepSeek** used for verification to ensure the questions are high-quality and relevant.

2.  **Exercise-Aware Knowledge Tracing (EKT):** This model continuously tracks a student's progress and understanding of different concepts over time. It analyzes their answers to questions to predict their knowledge state and identify areas where they are struggling.

## Accuracy

The paper evaluates the models using several metrics. The most notable accuracy-related result is for the **Exercise-Aware Knowledge Tracing (EKT)** model, which predicts student performance.

-   The EKT model achieved a performance score (AUC - Area Under the Curve) of **93.34%** on the test dataset. This high score indicates that the model is very effective at predicting a student's performance and understanding their knowledge gaps.

## Dataset

The dataset used to train and evaluate the models was collected from a real-world university setting.

-   **Source:** The data was gathered from a 4-year Computer Science program at Amrita Vishwa Vidyapeetham using their in-house Learning Management System (LMS) called "AMPLE."
-   **Availability:** The paper does not provide a public link to the dataset. It appears to be private data from the institution. The paper links to a news article about the AMPLE system, but not the dataset itself.
