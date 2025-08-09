🚀 Movie Recommendation System
A smart Movie Recommendation System that suggests movies based on content similarity. This project uses Python, pandas, scikit-learn, and cosine similarity to recommend movies you’ll love.

📌 Features
✅ Content-based filtering using movie metadata

✅ Fast cosine similarity search

✅ Easy-to-use interface for getting recommendations

✅ Precomputed similarity.pkl file for efficiency

📂 Project Structure
bash
Copy
Edit
├── app.py                 # Main app code
├── movies.csv             # Dataset of movies
├── similarity.pkl         # Precomputed similarity matrix (download separately)
├── requirements.txt       # Dependencies
└── README.md              # Documentation

🛠 Installation & Setup
1️⃣ Clone the repository

bash
Copy
Edit
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
2️⃣ Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Download similarity.pkl file
Since the file is over 100MB, it’s hosted on Google Drive.
📥 Download similarity.pkl
[Place it in the project root folder.](https://drive.google.com/file/d/10j78hVW5yQnLNLTCW9B8y9FrjKOIPb7b/view?usp=sharing)

4️⃣ Run the application

bash
Copy
Edit
python app.py


🧠 How It Works
Movie metadata is processed to extract genres, keywords, cast, and crew.

Text data is converted into numerical vectors using CountVectorizer.

Cosine similarity is computed to find the closest matches for any given movie.

The results are sorted and returned as recommendations.

<img width="960" height="404" alt="image" src="https://github.com/user-attachments/assets/e39cc815-bd47-4adf-a0b7-4232b9a67cff" />


📜 License
This project is licensed under the MIT License. Feel free to use and modify it.

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

💡 Author
Shaheer Abbas
📧 Email: shaheerabbas414@gmail.com
🔗 GitHub: Shaheer-star
