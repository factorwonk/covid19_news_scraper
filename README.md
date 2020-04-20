# covid19_news_scraper

Given a list of clients as strings, scrapes Google News RSS Feed using the BeautifulSoup library for all covid-19 related news headlines about a particular client/orgnisation. Then runs a VADER sentiment model against each headline to arrive at a normalised sentiment score for each news headline. Subsequently a MALLET GENSIM model is run and a Topic Model is created based on the highest Coherence Score to identify the topic keywords of greatest relevance to each headline.
