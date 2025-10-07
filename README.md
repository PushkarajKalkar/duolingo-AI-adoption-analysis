# duolingo-AI-adoption-analysis
Analyzed 10,000 Reddit posts to evaluate user sentiment and willingness to pay for Duolingo Max after the stock’s rally to $441. Built an ETL and sentiment pipeline to test if AI-driven hype matched real adoption—finding users liked the feature but wouldn’t pay $30/month.


In early 2024, Duolingo’s stock rallied to $441 after the launch of Duolingo Max, its AI-powered premium subscription that promised a more personalized language learning experience. The market narrative was clear: investors believed AI would unlock a new wave of monetization for Duolingo.

I wanted to test that narrative against real user behavior.

Using data from 10,000 Reddit posts and comments, I built an ETL pipeline to extract, clean, and analyze discussions mentioning “Duolingo Max” and its AI mascot “Lily.” I ran sentiment analysis to gauge how users felt about the new feature and developed a Willingness-to-Pay (WTP) score to measure whether users were willing to pay the $30/month subscription price.

The results told a nuanced story:

Users liked the new AI feature—general sentiment was strongly positive.

But the WTP score was negative, showing that enthusiasm didn’t translate into payment intent.

The market’s excitement around AI adoption was disconnected from monetization potential.

This insight shaped my investment view: despite strong user sentiment, the pricing and adoption dynamics didn’t justify the rally. I built a short-side thesis around this finding, which later met the price target as the hype moderated.

Tech stack: Python, Pandas, Matplotlib, NLTK, Reddit API (PRAW)
Outputs: Sentiment and WTP analysis tables, comparative visualizations, and a reproducible data pipeline.
