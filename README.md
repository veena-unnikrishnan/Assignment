# Assignment
# Drug Recommendation System

# Objective
Design and implement a drug recommendation system that provides suggestions for
drugs based on patients' symptoms or medical history. This project will test your ability
to apply machine learning techniques, basic natural language processing (NLP), and
recommendation algorithms in a healthcare context.
# Problem Statement
You are tasked with building a Drug Recommendation System that helps patients
identify appropriate drugs based on their symptoms or past medical records. The system
should leverage a combination of collaborative filtering, content-based filtering, and
basic NLP techniques to analyze input data and provide relevant recommendations.

# Task Requirements
1. Data Preprocessing:
   
o Load the dataset and clean it by handling missing values, duplicate
records, and inconsistencies.
o Tokenize and preprocess any textual data (e.g., symptoms, reviews) for
analysis.
o Encode categorical variables if required.

2. Recommendation System:

o Hybrid Recommendation System:
§ Collaborative Filtering: Use a method like matrix factorization or a
pre-built library (e.g., Surprise, implicit) to recommend drugs
based on user-drug interaction data (e.g., ratings or reviews).

§ Content-Based Filtering: Analyze drug descriptions, reviews, or
symptom-related text to recommend drugs with similar properties
or features.

o Integration: Combine results from both methods into a hybrid system to
improve the quality of recommendations.

3. Symptom Analysis Using NLP:
   
o Use an LLM (Large Language Model) like BERT, GPT, or any open-source
alternative to process patient symptom descriptions and match them
with relevant drugs.
o Train or fine-tune the model (if time permits) to extract key symptoms and
associate them with drugs eRectively.

4. User Interface:
   
o Create a simple prompt based interface where user can enter systems
and then our model can suggest drugs and dosage

5. Explainability:
   
o Implement techniques like SHAP or LIME to explain the
recommendations made by the model.
o Document how symptoms are mapped to drug recommendations.

# Deliverables
1. Sample Outputs:
   
o Provide at least 3-5 examples of:
§ Patient symptoms or conditions.
§ Recommended drugs with reasons for selection (e.g., similar
symptoms, high ratings, etc.).

o Include visualizations showcasing your analysis and results.

2. Documentation:

o A brief report (1-2 pages) summarizing your approach, methods used,
challenges faced, and insights derived.
o Explain the strengths and limitations of your recommendation system.
o Recorded demo or screenshots of the working model

3. Jupyter Notebook:

o Include the following:
§ Data preprocessing steps.
§ Implementation of the collaborative filtering and content-based
filtering methods.
§ NLP-based symptom analysis using LLMs.
§ Final hybrid recommendation system and evaluation metrics.
o Clearly commented code and markdown sections explaining your
approach


# Additional Guidelines
• Use Python as the primary programming language. Libraries like Pandas,
NumPy, Scikit-learn, NLTK, TensorFlow/PyTorch, and Matplotlib/Seaborn can
be used.

• You may use open-source pre-trained models for NLP tasks.
