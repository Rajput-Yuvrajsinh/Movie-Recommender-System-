🎬 Movie Recommender System
A content-based Movie Recommendation System built using Python, Streamlit, and TMDb API. This web app recommends similar movies based on the user's selected movie and also displays their posters using TMDb API.

📌 Features
Recommends top 5 similar movies.

Displays movie posters fetched via TMDb API.

Interactive UI using Streamlit.

Easy-to-use dropdown selection for movies.

📊 Demo

Replace this with a screen recording or screenshot of your app

🛠️ Tech Stack
Python 🐍

Streamlit – UI Framework

Pandas – Data Handling

Scikit-learn – Similarity Matrix

Pickle – Model/Data Serialization

TMDb API – For fetching movie posters

🚀 How It Works
User selects a movie from the dropdown.

The app finds the top 5 most similar movies using a cosine similarity matrix.

Movie posters are fetched using the TMDb API.

All recommendations are displayed side-by-side.

🧾 Installation
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/yourusername/movie-recommender-system.git
cd movie-recommender-system
Install Dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the App:

bash
Copy
Edit
streamlit run app.py
📁 Project Structure
bash
Copy
Edit
├── app.py                  # Main Streamlit App
├── movie_dict.pkl          # Serialized movie data
├── similarity.pkl          # Precomputed similarity matrix
├── requirements.txt        # Python dependencies
└── README.md               # Project Documentation
🔑 API Key
This project uses TMDb API to fetch movie posters. You need to generate your own TMDb API key and replace the one used in:

python
Copy
Edit
response = requests.get("https://api.themoviedb.org/3/movie/{}?api_key=YOUR_API_KEY&language=en-US")
📷 Screenshot![Screenshot 2025-06-12 155306](https://github.com/user-attachments/assets/bd4c943f-84c9-49dd-8d25-1b44b40d0f43)

✨ Future Improvements
Add movie filtering by genre, year, rating.

Add user login and history.

Improve UI/UX using custom CSS.

Add collaborative filtering for better recommendations.

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

📄 License
This project is licensed under the MIT License.
