# Fake-News-Classifier
## Analysing fake news with text mining and naive bayes

The latest hot topic in the news is fake news and many are wondering what data scientists can do to detect it,
find the underlying patterns and maybe prevent it. 
The used Kaggle dataset contains text and metadata scraped from 244 websites, 
contains news articles published between 26/10/2016 and 25/11/2016 and is mostly related 
to the US presidential campaign in 2016, and the tagging is based on the curated list of www.opensources.co

*Dataset source:* www.kaggle.com/mrisdal/fake-news

### Tags

Open Sources uses combinations of the following tags to classify each website we assess.

**Fake** Sources that entirely fabricate information, disseminate deceptive content, or grossly distort actual news reports

**Satire** Sources that use humor, irony, exaggeration, ridicule, and false information to comment on current events.

**Bias** Sources that come from a particular point of view and may rely on propaganda, decontextualized information, and opinions distorted as facts.

**Conspiracy** Sources that are well-known promoters of kooky conspiracy theories.

**Rumor** Sources that traffic in rumors, gossip, innuendo, and unverified claims.

**State** Sources in repressive states operating under government sanction.

**Junksci** Sources that promote pseudoscience, metaphysics, naturalistic fallacies, and other scientifically dubious claims.

**Hate** Sources that actively promote racism, misogyny, homophobia, and other forms of discrimination.

**Clickbait** Sources that provide generally credible content, but use exaggerated, misleading, or questionable headlines, social media descriptions, and/or images.

**Unreliable** Sources that may be reliable but whose contents require further verification.

**Political** Sources that provide generally verifiable information in support of certain points of view or political orientations.

**Reliable** Sources that circulate news and information in a manner consistent with traditional and ethical practices in journalism.

## Objectives & Methodology

The main objective of this coursework project is to analyse a text-based, labelled dataset in a quantitative way in order to build a machine learning model which is able to distinguish between different classes of news articles according to a given set of labels. These (11) labels are pre-coded, and I will propably recluster them to get better results. Furthermore, I will look into textual associations, visualise the text data by different features (by label, by frequency and more) and by different means (tables, diagrams, wordclouds) during and after I've applied several R text mining methods. After cleaning, transforming and filtering the text data into numerical data I will train and test several Naive Bayes based models. Finally, I am going to compare and validate the performances of these models with more sophisticated unsupervised machine learning algorithms.
