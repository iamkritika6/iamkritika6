<h1 align="center">Kritika Singh Chauhan</h1>

<p align="center">
  MSc Artificial Intelligence (Distinction) &nbsp;|&nbsp; Machine learning and data engineering &nbsp;|&nbsp; Reading, UK
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/kritika-singh-chauhan-899bbb3b8"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:chauhankritika.singh77@gmail.com"><img src="https://img.shields.io/badge/Email-444444?style=flat-square&logo=maildotru&logoColor=white" alt="Email"></a>
</p>

---

I did an MSc in AI and spent my dissertation teaching neural networks to predict where CRISPR accidentally cuts DNA. Before that, and alongside it, I led shifts of 7 to 9 people at a noodle bar, which taught me more about deadlines than any module did. Now I'm building data projects and looking for my first role in the field.

- **Open to:** data science, machine learning and data engineering roles in London and the Thames Valley
- **Into:** machine learning you can actually trust, data engineering, and AI for biology
- **Currently getting better at:** SQL and data modelling, one awkward dataset at a time

## Projects

### [CRISPR-AI: Safe-Edit Off-Target Prediction](https://github.com/iamkritika6/crispr-ai-safe-edit-offtarget)

My MSc dissertation. Deep learning models (GRU, BiLSTM, CNN-BiLSTM) that predict where CRISPR/Cas9 might cut DNA by mistake. Only 656 of 153,233 sequence pairs are positives, so accuracy would be meaningless and I evaluated with AUPRC instead. I tuned the models with random search and a genetic algorithm, then used integrated gradients and in-silico mutagenesis to look at what they had learned. The README lists the limitations too.

`Python` `PyTorch` `scikit-learn` `Captum`

### [UK Employer Intelligence Warehouse](https://github.com/iamkritika6/uk-employer-intelligence-warehouse)

A PostgreSQL warehouse that links two UK government open datasets. It has raw, staging and star-schema layers, change tracking, 18 automated quality checks and a one-command pipeline in Docker. The part I like most: I measured how wrong my fuzzy matching is by checking a sample by hand, instead of assuming it was fine.

`PostgreSQL` `SQL` `Docker` `Python`

### [Bengaluru House Price Prediction](https://github.com/iamkritika6/house-price-prediction)

Predicting the asking price of residential property listings. On a test set of 2,523 listings held back from every cleaning, training and tuning decision, half the predictions land within 16.2% of the asking price. I benchmarked it against a price-per-square-foot domain rule as well as predicting the median, because beating the median only proves the model learned something, while beating a sensible rule of thumb is what shows the machine learning earned its place. The README is clear that this models what sellers ask, not what buyers pay.

`Python` `scikit-learn` `pandas`

## Toolbox

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow">
  <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=databricks&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
</p>

**Machine learning:** deep learning, hyperparameter tuning, evaluation on imbalanced data, model interpretability
**Data:** SQL, PostgreSQL, data modelling, data quality checks, entity matching
**Tools:** Python, Docker, Git, GitHub

## How I work

- I write down the limits of my results, not just the good numbers.
- I check every number in a README against the code that produced it.
- I write READMEs so a stranger can rerun the project.

## Say hi

Best reached on [LinkedIn](https://www.linkedin.com/in/kritika-singh-chauhan-899bbb3b8) or by [email](mailto:chauhankritika.singh77@gmail.com).

*Fun fact: getting through a lunch rush with nine people taught me to stay calm when everything breaks at once. Very useful for pipelines.*
