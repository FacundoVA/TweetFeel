# TweetFeel
TweetFeel is a Flask web app that performs real-time sentiment analysis on tweets scraped via twscrape. It features user authentication, an SQL database for storing tweets, and data visualizations through PyChart, including histograms and line graphs.


# TweetFeel

**TweetFeel** is a Flask web application that performs real-time sentiment analysis on tweets scraped using `twscrape`. It features user authentication, an SQL database for storing tweets and user data, and interactive data visualizations with PyChart, including histograms and line graphs.

## 📈 Features

- **Real-Time Tweet Scraping:** Collects tweets based on keywords or hashtags using `twscrape`.
- **Sentiment Analysis:** Classifies tweets as positive, negative, or neutral.
- **User Authentication:** Secure login and registration system.
- **SQL Database:** Stores tweets and user information efficiently.
- **Data Visualizations:** Interactive graphs (histograms, line graphs) to display sentiment trends.

## 🛠️ Technologies Used

- **Backend:** Python, Flask, `twscrape`, SQL (SQLite/PostgreSQL)
- **Frontend:** HTML5, CSS3, JavaScript, PyChart

## 🚀 Installation

1. **Clone the Repository**
    ```bash
    git clone https://github.com/yourusername/TweetFeel.git
    cd TweetFeel
    ```

2. **Create a Virtual Environment**
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows: `venv\Scripts\activate`
    ```

3. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

4. **Configure the Database**
    - Update the database URI in `config.py` if necessary.
    - Initialize the database:
        ```bash
        flask db init
        flask db migrate -m "Initial migration."
        flask db upgrade
        ```

5. **Run the Application**
    ```bash
    flask run
    ```

6. **Access the App**
    - Open your browser and navigate to `http://localhost:5000`

## 📊 Usage

1. **Register an Account:** Create a new user to access TweetFeel.
2. **Scrape Tweets:** Enter keywords or hashtags to start scraping tweets in real-time.
3. **View Sentiments:** See sentiment analysis results categorized as positive, negative, or neutral.
4. **Explore Visualizations:** Use interactive graphs to analyze sentiment trends and patterns.

## 🖼️ Screenshots
![Screenshot 2023-11-22 101138](https://github.com/user-attachments/assets/f421ad8b-a134-408a-a2b6-866ee20f87da)
![Screenshot 2023-11-22 101116](https://github.com/user-attachments/assets/01f16b8e-11dc-4be7-83b0-4eb976658317)
![Screenshot 2023-11-22 101517](https://github.com/user-attachments/assets/4a514b6b-dc73-45ab-ad4b-bb91b3cf2715)
![Screenshot 2023-11-22 101218](https://github.com/user-attachments/assets/ab7d3350-5513-43d7-8302-3534ac695f31)


## 🤝 Contributing

Contributions are welcome! Follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 📞 Contact

- **Your Name**
- [your.email@example.com](mailto:your.email@example.com)
- [LinkedIn](https://www.linkedin.com/in/yourprofile/)
- [Twitter](https://twitter.com/yourprofile)

---

