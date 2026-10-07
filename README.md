# Project ING5 Ethic of AI

## 4.1. Guidelines 

**Goal** : make ethical (by design) a classic AI workflow 

**Steps** :
- Find a real-life dataset (on Kaggle & co), enlight its biases and reduce them if you decide to implement an unbiased prediction but not for a realistic prediction (slides 27-28)
- Get a handleable LLM, adapt it by the three methods and benchmark them in order to save the most appropriate one
-  Use it as a solution for a relevant problem regarding your dataset
-  Explain its decisions thanks to both XAI tools

Teams of 3-4 students (10 teams per group), 10-min presentations at the next class Notebook and slides to upload on Boostcamp before the presentation Up to 3 bonus points on the written exam grade.


## 4.2.1. Examples : realistic prediction 
**Dataset** : Forward market values prediction ; features : statistics, country, market value, etc. 

**Solution/title** : LLM-powered forward market values prediction 
Bias : Despite scoring less goals, forwards from very few countries are always more valued than others 

**Bias reduction** : None (unless you want to turn it into a decision-making solution) 
Final demo (asking the specialized LLM) : What is the market value of a 23-years old moroccan forward who scored 6 goals and provided 1 assist in 9 games this season with Lille ? And of a brazilian one with nearly the same features ? Why ? (cf. XAI) 

## 4.2.2. Examples : unbiased prediction 
**Dataset** : College first-year admissions ; features : grades, location, admitted (0/1), etc. 

**Solution/title** : LLM-powered college first-year admissions decision-making 

**Bias** : Despite having same baccalauréat grades, suburbs students are widely less admitted 

**Bias reduction** : 
- Shortening/altering the dataset to train your model more fairly
- And/or keep your dataset unchanged and configure your model

Final demo (asking the specialized LLM) : Between Jonas (18/20 and from a remote area) and Bartosz (17.5/20 and from the capital), who was before the biases reduction more likely to be admitted and now is ? Why ? (cf. XAI)




