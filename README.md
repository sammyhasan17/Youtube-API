# 🎥 YouTube Channel Sentiment Analysis with NLTK & Data Visualization

This Jupyter Notebook project analyzes **YouTube video content and audience reactions** using publicly available data from the **YouTube Data API**. It pulls metadata like **video titles, descriptions, and comments** from multiple channels, and applies **Natural Language Processing (NLP)** to detect patterns in tone, sentiment, and engagement.

By analyzing both **creator intent** (via titles/descriptions) and **audience response** (via top-level comments), the tool offers powerful insights

# Big Questions

*Content Strategy Optimization: Identify what types of videos perform well or poorly, so you can double down on successful content and phase out what underperforms

*Trending Topics Detection: Spot topics with high positive engagement and leverage those macro trends to attract more viewers and subscribers

*Audience Misalignment: Discover where creators may be missing the mark so they can avoid repeated mistakes and improve audience satisfaction

*Collaboration Opportunities: Analyze where different channels share similar audience behavior, helping creators partner effectively to boost engagement and views

Whether you're a content creator, social media analyst, or brand strategist, this project helps quantify and visualize messaging tone and community feedback across any set of YouTube channels.

---

## 🔍 Key Features

* Pulls metadata and top-level comments from multiple YouTube channels
* Applies **NLP-based sentiment analysis** to titles, descriptions, and comments
* Flags **positive/negative audience sentiment trends**
* Visualizes insights with intuitive graphs for quick analysis

---

## 📊 Visual Insights

### 📈 Sentiment Scatter Plot

Displays sentiment scores for videos across all selected channels, grouped by channel for comparison.

### 📊 Bar Plot of Sentiment by Video

Ranks videos by sentiment score to highlight **most positive** and **most negative** content.

### 📋 Comments Analysis (Optional)

Examines viewer comments to identify:

* Videos with strong negative/positive reception
* Common keywords/themes using word clouds or frequency plots
* Audience mood trends over time

---

## 🧰 Tools & Libraries Used

| Tool / Library                        | Purpose                                    |
| ------------------------------------- | ------------------------------------------ |
| **YouTube Data API**                  | Fetch video titles, descriptions, comments |
| **Python**                            | Programming language                       |
| **Jupyter Notebook**                  | Interactive coding environment             |
| **NLTK (SentimentIntensityAnalyzer)** | Sentiment analysis                         |
| **Matplotlib & Seaborn**              | Data visualization                         |

---

## 🚀 How It Works

1. **API Authentication**
   Connect to YouTube using a developer API key

2. **Data Collection**
   Pull video metadata (title, description, views, likes) and top-level comments

3. **Sentiment Analysis**
   Apply `NLTK`’s sentiment scoring to each text field (titles, descriptions, comments)

4. **Trend Detection**
   Flag low-performing videos, trending topics, and audience sentiment patterns

5. **Visualization**
   Graph insights to understand content tone and audience engagement

---

## 🧠 Example Use Cases

* Identify videos with **negative sentiment** or **poor reception**
* Track which **themes resonate most** with audiences
* Uncover **trending topics** across content creators
* Compare tone between channels (e.g., educational vs. entertainment)
* Pinpoint collaboration opportunities with **shared audience sentiment**

---

Let me know if you'd like this saved as a `.md` file or want help integrating comment analysis in code.
