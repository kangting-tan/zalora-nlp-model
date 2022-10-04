# Zalora-app-analysis
Natural language processing (NLP) of Zalora’s Apple & Android app store reviews, automatically synthesizing 
key issues for technical &amp; business action – allows for app performance monitoring and quick reaction to customers

______________

__Read the process overview & outputs here: https://karinekode.wixsite.com/folio/nlp__ 

__View Part 1 here: https://github.com/karinekode/Zalora-app-analysis/blob/main/Part%201%20-%20IOS%20App%20store%20web%20scraper.ipynb__ 
where data is automatically scraped from the app stores

__View Part 2 here: https://github.com/karinekode/Zalora-app-analysis/blob/main/Part%202%20-%20LDA%20Model%20for%20NLP%20Analysis.ipynb__
where latent dirichlet allocation (hierarchical Bayesian model) is used for NLP. 

Hyperparametric tuning is done across 2 parameters: the number of topics and the learning decay. Gridsearched across 6 number of topics and 3 learning decays, and best model is selected based on the highest log likelihood score

______________

