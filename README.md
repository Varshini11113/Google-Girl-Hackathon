# Google-Girl-Hackathon - Varshini M
Welcome to the GitHub repository of my Medical Assistant project - _[MediMatch]_ developed for the Google Girl Hackathon.

# **MediMatch - Receive the care you Deserve**
Welcome to _MediMatch_, your trusted companion in navigating the complexities of healthcare. Our innovative recommendation system connects you with specialized doctors whose expertise aligns perfectly with your needs and schedules. <br/>
**Our Mission :** To empower users like you to find the right healthcare providers based on your symptoms, ensuring you receive the care you deserve.

# **Problem Statement**
Medical Assistant: Develop a healthcare recommendation system that analyzes user symptoms leveraging symptom data (using mock data), healthcare provider databases, and user ratings,  recommends doctors with matching specialties and aligned schedules

# Our Solution and Project Overview
This project, _MediMatch_ aims to create a healthcare recommendation system that analyzes user symptoms, recommends relevant specialists, and provides assistance based on symptom data and healthcare provider databases. Through a user-friendly chatbot interface, users can input their symptoms, and our system analyzes the data using advanced AI algorithms to predict potential diseases and recommend relevant specialist doctors. <br> <br>
_MediMatch_ offers a versatile **multimodal** interface, allowing users to interact via text, images, or audio, accommodating diverse communication preferences and enabling nuanced symptom analysis. Additionally, its **multilingual** support ensures accessibility by providing medical advice in users' preferred languages, breaking down language barriers and offering personalized healthcare experiences. <br> <br>
Here's a brief overview of the key components and functionalities:
<br><br>
**Chatbot Interface:** Developed using Next.js, users can input their symptoms and receive recommendations. <br>
**Symptom Analysis:** Utilizes a combination of the RAG (Retrieval-Augmented Generation) model and the Language Learning Model (LLM) with GPT OpenAI for symptom analysis and response generation. The FAISS (Facebook AI Similarity Search) algorithm is used to convert symptom data into vector representations for efficient retrieval. <br>
**Data Training:** Fine-tunes the RAG model on symptom data and healthcare provider databases to learn disease-symptom associations and specialist recommendations. <br>
**Backend Integration:** Implemented in Python using Flask, the backend hosts interactions between the chatbot and the AI models. <br>

# **Technologies Used** <br>
**Frontend**: Next.js <br>
**Backend**: Python, Flask <br>
**AI** **Techniques**: RAG Model, GPT OpenAI (LLM), Deep Learning, Generative AI (GEN AI), Transformers <br>
**Libraries** **and** **Packages**: faiss-cpu, torch, pandas, numpy, sentence-transformers, npm packages <br>

# **Work Flow**
![alt text](<mediMatch workflow.png>)

# **How to Run the Code**
_**Set Up Environment**_ <br>
# **Back-end**
* **Install Python and Flask:** <br>
If not already installed, download and install Python from the official website: [Python Downloads](https://www.python.org/downloads/). <br>
* Install Flask using pip:<br>
  pip install flask <br>
* **Install Required Python Packages:** <br>
Navigate to the api folder: <br>
cd api <br>
* **Install the required Python packages using pip:** <br>
pip install -r requirements.txt <br>
* Run the root python file (faiss_api.py) <br>
python faiss_api.py <br>
**The back-end server starts working** <br>
* move to the location UI/nextjs-multi-modal/app/api/chat/route.js and include **open api key** in the front-end <br>

# **Front-end**
* Move to folder - UI/nextjs-multi-modal <br>
* **Install all the dependencies** <br>
  npm install
* **To run the development server** <br>
  npm run dev <br>
* Click on the link generated after the complete run of developer server to view the result <br>
* Example - Open http://localhost:3000 with your browser to see the result.

# **Project (MediMatch) - demo video link**
link --> https://drive.google.com/file/d/1IlwIWjp3idKkpih5HmosHfvgfaaxKF-8/view?usp=drive_link <br>

# **Project (MediMatch) - Screenshots**
link --> https://drive.google.com/drive/folders/1JjRCrQWny9rj-rj4LB7w0Sdnz1RlUUKw?usp=drive_link <br>

# **Dataset links**
https://drive.google.com/file/d/1sKiMGy1Hp83rjznuMLhtS7JFhaS7ovxC/view?usp=drive_link

## _**Thank you!**_





