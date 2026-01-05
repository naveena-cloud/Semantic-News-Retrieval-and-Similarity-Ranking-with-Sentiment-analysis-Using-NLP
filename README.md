# Semantic News Retrieval and Similarity Ranking with Sentiment Analysis Using NLP

## Overview
This project implements an NLP-based system that retrieves real-time news articles, ranks them based on semantic similarity to a user query, and analyzes sentiment polarity to provide insightful and structured news understanding.

## Objectives
- Fetch relevant news articles using the GNews API  
- Rank articles using semantic similarity (TF-IDF + Cosine Similarity)  
- Perform sentiment analysis on news titles  
- Provide a simple and interpretable output for users  

## Technologies Used
- Python  
- GNews API  
- TextBlob (Sentiment Analysis)  
- Scikit-learn (TF-IDF, Cosine Similarity)  
- Requests  

## How It Works
1. User enters a news topic or title  
2. System fetches related articles via GNews API  
3. Articles are ranked using semantic similarity  
4. Sentiment polarity is analyzed  
5. Results are displayed in ranked order

## Sample Output
Enter a news title or topic: Artificial Intelligence in healthcare

📰 Article 1 (Similarity: 0.28, Sentiment: 👎)
Title: Artificial intelligence to be at the heart of innovation in coming year
Source: The Irish Times
URL: https://www.irishtimes.com/business/2026/01/02/artificial-intelligence-to-be-at-the-heart-of-innovation-in-coming-year/
Published: 2026-01-02T05:00:00Z
Description: ‘After a year of cautious pilots, 2026 will see the Irish public sector accelerate AI adoption, with healthcare at the forefront’...

📰 Article 2 (Similarity: 0.25, Sentiment: 👎)
Title: Artificial Intelligence: Revolutionizing Every Aspect of Life - Global Dialogue: AI and Democracy in the Commonwealth
Source: Devdiscourse
URL: https://www.devdiscourse.com/live-discourse/8922-artificial-intelligence-revolutionizing-every-aspect-of-life
Published: 2026-01-04T08:38:16Z
Description: Artificial Intelligence (AI) is rapidly redefining the way we live, work, and interact. No longer confined to the realm of science fiction, AI is now a driving force behind innovations across all sect...

📰 Article 3 (Similarity: 0.08, Sentiment: 😐)
Title: Letters | How universities can rein in the abuse of AI
Source: South China Morning Post
URL: https://www.scmp.com/opinion/letters/article/3338305/how-universities-can-rein-abuse-ai
Published: 2026-01-02T03:30:09Z
Description: Readers discuss ways to ensure ethical artificial intelligence use in academia, the importance of activating Hong Kong’s emergency alerts, and the city’s healthcare fee hikes....

📰 Article 4 (Similarity: 0.00, Sentiment: 👍)
Title: “Better than doctors?” Elon Musk’s AI comment on MRI scans goes viral
Source: Times of India
URL: https://timesofindia.indiatimes.com/etimes/trending/better-than-doctors-elon-musks-ai-comment-on-mri-scans-goes-viral/articleshow/126319875.cms
Published: 2026-01-03T09:21:00Z
Description: Trending News: Artificial intelligence is once again being talked about widely online, this time for its role in healthcare. And like many tech debates these days, E....
