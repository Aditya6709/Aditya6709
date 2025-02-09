## 👋 Hi, I'm Achyutam Dubey!

I'm an **Electronics and Communication Engineering (ECE)** undergraduate with a passion for **data science**, **machine learning**, and **Android development**. I enjoy solving real-world problems by building intelligent systems, blending innovation with engineering principles.

---

## 🔧 Skills
- **Programming Languages:** Python, Java, Kotlin
- **Machine Learning Frameworks:** TensorFlow, PyTorch
- **Tools & Platforms:** Android Studio, Streamlit, Supabase
- **Development Environments:** WSL (Windows Subsystem for Linux), Kaggle Notebooks

---

## 💻 Projects
### 1. **Music Genre Classification App** 🎵  
- **Overview:**  
  Developed a machine learning model to classify music genres based on audio features. The app analyzes audio files provided by users and predicts the genre with high accuracy.  

- **Key Features:**  
  - Extracts and processes audio features like **MFCCs (Mel-frequency Cepstral Coefficients)**, chroma, and spectral contrast using libraries like **Librosa**.  
  - Trained a deep learning model using **TensorFlow/Keras** for robust classification.  
  - Offers a user-friendly interface where users can upload audio files and receive predictions in real-time.  

- **Tech Stack:**  
  - **Backend:** Python, TensorFlow, Librosa  
  - **Frontend:** Streamlit (for web app)
  - **Deployment:** Hosted the model on **Streamlit**

- **Challenges Solved:**  
  - Optimized the model to handle varying audio qualities and file formats.  
  - Enhanced performance by normalizing audio input and reducing noise in datasets.  

- **Future Improvements:**  
  - Expanding the dataset for better accuracy across diverse music genres.  
  - Adding support for real-time genre prediction from live audio recordings.  
  - Enabling recommendations for similar songs/artists based on genre predictions.  

- **Impact:**  
  Simplifies music genre identification for music enthusiasts, DJs, and producers, while showcasing the power of machine learning in audio classification.  


### 2. **Resume Ranking System** 📄    
- **Overview:**  
  A system designed to automatically categorize and rank resumes by specific domains (e.g., Data Science, Web Design, Java Development). It helps recruiters and hiring managers streamline the hiring process by identifying the best candidates based on required skills.  

- **Key Features:**  
  - Categorizes resumes into domains like **Data Science**, **Web Design**, **Database Management**, and more using keyword matching and weighted scoring.  
  - Ranks resumes within each category based on the relevance of skills, projects, and experience.  
  - Provides an intuitive, user-friendly web interface for uploading resumes and viewing results.
  - It has 2 sections job seeker and recruiter.
  - In the job seeker section, user can upload his resume and get the rank of latest uploaded resume.
  - In the recruiter section, a recruiter can see the leaderboard of any domain and can also download any resume with the available download link.

- **Tech Stack:**  
  - **Backend:** Python, Resume Parsing with libraries like **PyPDF2** and **spaCy**   
  - **Storage:** **Supabase** bucket to store resumes in organized folders.  
  - **Deployment:** Deployed on **Streamlit** for easy accessibility.  

- **Challenges Solved:**  
  - Efficiently extracting and analyzing data from various resume formats (PDF, Docx).  
  - Implemented a scoring algorithm to weigh skills, certifications, and projects dynamically.  
  - Ensured domain-specific customization by allowing flexibility in skill weighting.  

- **Future Improvements:**  
  - Incorporate NLP-based semantic analysis to enhance keyword matching and ranking accuracy.  
  - Add support for generating domain-specific feedback for candidates.  
  - Enable multi-language support for international resumes.  

- **Impact:**  
  Significantly reduces the time and effort required in the initial screening of candidates, helping organizations focus on top talent quickly and efficiently.  

- **Live Demo:**  
  The project is live on **Streamlt** and ready for recruiters to test and use.
  
### 3. **Movie Recommendation Android App** 🎥  
- **Overview:**  
  An intelligent Android app that recommends movies based on user-selected genres. This app leverages machine learning to analyze user preferences and suggests highly-rated movies, making it easy for users to explore films they’ll enjoy.  

- **Key Features:**  
  - Allows users to select one or multiple genres (e.g., Action, Comedy, Thriller).  
  - Recommends movies from a curated dataset based on genre-specific popularity and ratings.  
  - Displays key movie details like title, release year, rating, and a brief synopsis.  
  - Features an intuitive and visually appealing interface developed in **Android Studio**.  

- **Tech Stack:**  
  - **Backend:** Python for building the recommendation model (using collaborative filtering and content-based filtering).  
  - **Frontend:** Android app built in **Kotlin** using **Material Design** principles.  
  - **Dataset:** Curated data from IMDb or TMDb, stored in **CSV format** for offline access.  

- **Challenges Solved:**  
  - Preprocessed and cleaned the movie dataset for faster querying and better accuracy.  
  - Designed a lightweight recommendation model optimized for mobile devices.  
  - Implemented a seamless integration between the backend model and the Android app for real-time predictions.  

- **Future Improvements:**  
  - Add personalized recommendations based on user watch history.  
  - Include user reviews and ratings as part of the recommendation criteria.  
  - Integrate APIs like **TMDb API** for fetching live movie data, posters, and trailers.  

- **Impact:**  
  Makes movie selection quick and enjoyable by providing accurate and personalized recommendations, catering to diverse user preferences.  

- **Future Deployment:**  
  Planning to host the recommendation model on a cloud platform for dynamic updates and real-time predictions.  

### 4. **Comment Toxicity Classification App** 💬  
- **Overview:**  
  An advanced deep learning-based app designed to classify text comments into various categories of toxicity, including hate speech, offensive language, and harassment. The app helps in moderating online platforms by identifying harmful content and ensuring safer user interactions.  

- **Key Features:**  
  - Classifies comments into toxicity categories such as **toxic**, **severe toxic**, **obscene**, **threat**, **insult**, and **identity hate**.  
  - Uses a deep learning **LSTM recurrent neural network** model for classification.   
  - Provides an intuitive user interface for inputting and displaying results.  

- **Tech Stack:**  
  - **Backend:** Python, TensorFlow/PyTorch for deep learning model 
  - **Frontend:** Streamlit (for web interface).
  - **Deployment:** Streamlit app 

- **Challenges Solved:**  
  - Effectively handles nuanced language patterns and context for accurate toxicity classification.  
  - Deals with unstructured, informal comment text often seen in social media platforms.  
  - Balances false positives and false negatives to improve model precision and recall.  

- **Future Improvements:**  
  - Enhance model accuracy with domain-specific training (e.g., for specific social media platforms).  
  - Add multi-language support for global content moderation.  
  - Incorporate sentiment analysis to assess the severity of toxic comments.  

- **Impact:**  
  Aims to improve online discourse by providing automated moderation tools, reducing harmful content, and fostering positive environments on digital platforms.  

- **Live Demo:**  
  A **Streamlit** demo via hugging face spaces for testing the toxicity classification in real-time.  

---

## 📫 Let's Connect!
- **Email:** dubeyachyutam.2004@gmail.com

  
Feel free to explore my repositories to see what I'm up to! Let's collaborate and build something amazing together. 🚀

