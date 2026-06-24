Hi, I’m Ihor 👋

Software Engineer → Machine Learning Engineer

I’m a Machine Learning Engineer / Data Scientist with experience building web applications using Laravel, PostgreSQL, and modern web technologies.

I’ve been focusing on Machine Learning and Data Science, working toward becoming a world-class ML Engineer capable of building intelligent products and solving real-world problems with data.

🚀 Current Focus

* Machine Learning Fundamentals
* Data Science & Analytics
* Deep Learning
* MLOps
* Kaggle Competitions
* AI-powered Products

🛠 Tech Stack

Software Engineering

* PHP
* Python
* FastAPI
* Laravel
* JavaScript / TypeScript
* PostgreSQL / SQLite / MySQL / MongoDB
* Docker
* Git
* Linux

💙 Machine Learning & Data Science

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn
* Jupyter Notebook

😍 Currently expanding into:

* PyTorch
* Deep Learning
* Neural Networks
* MLOps
* Large Language Models (LLMs)

📈 My Journey

For several years, I’ve been building production web applications and learning how software systems are designed, deployed, and maintained.

Now I’m applying that engineering mindset to Machine Learning:

* building ML projects,
* participating in Kaggle competitions,
* studying mathematics and statistics,
* and gradually transitioning toward ML Engineering.

I believe strong software engineering combined with ML expertise creates a powerful advantage.

🔥 Current Projects

🇺🇦 **Ukrainian News Recommender**

> The Ukrainian media landscape is noisy. This project cuts through it 
> by learning what *you* actually want to read.

A fully local, privacy-first news aggregation system that ingests live RSS 
feeds from major Ukrainian outlets (Ukrinform, Ukrainska Pravda, TSN, 
Suspilne, NV), categorizes articles using NLP, and serves a personalized 
feed ranked by your reading preferences — with no ads, no tracking, and 
no black-box algorithm.

**[→ Live demo](#)**

How it works:

1. **Ingestion** — RSS feeds from 5 Ukrainian outlets are fetched hourly 
   and deduplicated by URL into a local SQLite database.

2. **Categorization** — Each article is classified into topics (War & 
   Security, Politics, Economy, Tech, Sport, Society) using TF-IDF vectors 
   with cosine similarity against category seed texts.

3. **Semantic embedding** — Articles are encoded into 384-dimensional 
   vectors using `paraphrase-multilingual-MiniLM-L12-v2`, a multilingual 
   sentence transformer that understands Ukrainian without fine-tuning.

4. **Preference modeling** — User upvotes and downvotes build a personal 
   preference vector: the weighted mean of liked article embeddings minus 
   a discounted mean of disliked ones, re-computed on every session.

5. **Recommendation** — Unread articles are ranked by cosine similarity 
   to the preference vector. An 85/15 exploitation/exploration split 
   actively counters filter bubble formation.

6. **Delivery** — A FastAPI backend serves personalized feeds via REST API. 
   A React frontend displays ranked articles with match scores, category 
   filters, and one-click upvote/downvote to continuously refine the model.

Tech stack

`Python` · `scikit-learn` · `sentence-transformers` · `SQLite` · 
`FastAPI` · `React` · `feedparser`

**🤖 YouTube Summary Bot**

A Telegram bot that:

* summarizes YouTube videos
* extracts transcripts
* answers questions about video content
* explores practical LLM integrations

📚 Currently Learning

* Mathematics for Machine Learning
* Statistics
* Machine Learning Engineering
* Deep Learning
* Data Structures & Algorithms
* Kaggle Competitions

📫 Connect With Me

* [LinkedIn](https://www.linkedin.com/in/realihorrud/)
* [Email](mailto:ihorryd9@gmail.com)
