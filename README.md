
# 📊 WhatsApp Chat Analyzer

A Streamlit-based web app that helps you analyze your WhatsApp chat history with powerful visualizations and insights. 🚀
You can upload an exported WhatsApp chat .txt file, and the app will generate statistics, activity trends, word clouds, emoji usage, and more.

**✨ Features**

✔️ Chat Statistics

Total messages

Total words

Media shared

Links shared

✔️ Timelines

Monthly activity trend

Daily activity trend

✔️ Activity Maps

Most active days

Most active months

Weekly activity heatmap

✔️ User Analysis

Most busy users in group chats

Contribution percentage of each user

✔️ Word Analysis

Word cloud of most used words

Most common words (ignoring stop words)

✔️ Emoji Analysis

Most frequently used emojis

Emoji usage distribution (pie chart)

**📂 Project Structure**

ML/whatsapp_chat_Analysis/

│── app.py               # Main Streamlit app

│── helper.py            # Functions for stats, wordcloud, analysis

│── preprocessor.py      # Preprocesses raw WhatsApp chat data

│── stop_hinglish.txt    # Custom stop words (English + Hinglish)

│── requirements.txt     # Dependencies

│── README.md            # Project documentation

**⚙️ Installation & Setup**

1️⃣ Clone the repository
git clone https://github.com/<your-username>/whats-app_chat-analysis.git
cd whats-app_chat-analysis/ML/whatsapp_chat_Analysis

2️⃣ Create & activate virtual environment (optional but recommended)
python -m venv venv
venv\Scripts\activate     # On Windows
source venv/bin/activate  # On Mac/Linux

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Run the Streamlit app
streamlit run app.py

**📥 How to Export WhatsApp Chat**

Open WhatsApp on your phone

Open the chat you want to export

Tap Options (⋮) > More > Export Chat

Select Without Media (recommended)

Save the .txt file and upload it in the app sidebar



**📊 Example Insights**

📅 Monthly Timeline – Track chat activity over time

📈 Daily Timeline – See which days are most active

🔥 Most Busy Users – Find out who dominates the conversation

☁️ Word Cloud – Visualize most used words

😂 Emoji Usage – Discover which emojis are used the most


**🛠️ Technologies Used**

Python 3

Streamlit
 – Web app framework

Pandas
 – Data processing

Matplotlib
 & Seaborn
 – Visualizations

WordCloud
 – Word cloud generation

emoji
 – Emoji handling

urlextract
 – Extracting links from messages


**🚀 Future Improvements**

Sentiment analysis of chats

Interactive filters for users & date ranges

Export insights as PDF report

Multi-language support


**🙌 Contributing**

Contributions are welcome!

Fork the repo

Create a new branch

Commit changes

Open a Pull Request
