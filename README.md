# Hi, I'm Jerra!

I’m a data analyst with a focus on civic tech and public policy, currently pursuing a Masters degree in Computational Social Science at UC Berkeley. My goal is to work at the intersection of data and government, to build tools and analyses that make public institutions more transparent, equitable, and effective.

My path into this work has been shaped by both academic training and lived experience. I earned my B.A. in Economics and Sociology at UC Santa Barbara, where I worked as a research assistant on a [sociological study of mass shootings in America](https://pubmed.ncbi.nlm.nih.gov/37214768/). Through this project, I saw firsthand how data can be used to tell stories, uncover patterns, and support evidence-based change.

Currently, I’m deepening my technical toolkit by developing skills in Python, R, SQL, while continuing to work on mission-driven projects. Most recently, I partnered with [Ten Strands](https://tenstrands.org/work/data-initiative/), a non-profit focused on Environmental Literacy within K-12 schools, to analyze environmental policy language from over 700 California school districts. I helped build a scalable data pipeline to extract, clean, and analyze policy documents, using Natural Language Processing (NLP) techniques like topic modeling, semantic similarity and quantitaive techniques like regression analysis to identify language associated with stronger climate action.

I’m especially motivated by work that combines data, policy, and social impact! I’m excited to contribute to projects that help communities and public institutions navigate complex challenges with clarity and care.

### Analytical Skills 
Through rigorous graduate coursework at UC Berkeley, data-related interships and projects, I’ve developed advanced programming and analytical capabilities at the intersection of data science and social impact. My work spans the full data lifecycle; from engineering robust computing environments to interpreting statistical models for real-world decision-making.

**Computing and Machine Learning:**
- Proficent in Python using pandas, NumPy, matplotlib, scikit-learn, PyTorch, and spaCy for scientific computing and applied machine learning.
- Built end-to-end machine learning workflows including feature engineering, hyperparameter tuning, and cross-validation with tools like XGBoost, LightGBM, and Sentence-BERT.
- Developed natural language processing pipelines and fine-tuned Large Language Models (LLMs) using prompt engineering.

**Statistical Analysis & Causal Inference:**
- Conducted statistical analysis in R and Python—using regression, hypothesis testing, RCTs, IVs, and panel data—to answer policy and social science questions.
- Used statistical modeling tools including statsmodels, ggplot2, and tidycensus to analyze public policy, labor markets, and displacement risk.

**Data Wrangling:**
- Processed and merged complex datasets across formats (JSON, CSV, GeoJSON), and modalities (tabular, text, spatial).
- Retrieved and analyzed large-scale web data via APIs, web scraping, and manually downloading files (due to firewalls).

**Data Visualization:**
- Created interactive visualizations using tools like Tableas, Mapdeck, Matplotlib, Seaborn, and ggplot2 to tell engaging data stories. 

**Read below for more details about projects I have worked on.**

## Projects
- [NLP on CA School Board Policies](https://github.com/jerramcl/school-board-NLP)

    I analyzed environmental school board policies from 700+ California school districts by extracting text from PDFs using Python (fitz, pdf2image,  pytesseract) and cleaning the data with regex and NLP tools. Using regression analysis, semantic similarity, and topic modeling, I explored whether specific policy language correlates with climate action. I created visualizations—including graphs and word clouds—to highlight key patterns and developed a scalable, replicable framework for qualitative policy analysis. The goal was to understand if school board policy language affects implentation of climate friendly action on campuses across California.

- [Investments in Public Transportation on Property Values](https://github.com/jerramcl/transportation-project/tree/main)

    This project investigates whether the 2017 expansion of BART to Warm Springs in Fremont, CA increased nearby property values. Using a Weighted Least Squares regression model with Zillow housing data from 2011–2020, I controlled for mortgage rates, unemployment, lagged values, and addressed statistical issues like serial correlation and heteroskedasticity. Results showed no statistically significant effect from the station’s opening on local property values, though macroeconomic indicators were strong predictors. A 1% rise in mortgage rates correlated with a 10% drop in property values. It's important to note that due to data limitations at the zip-code level, localized effects may have been obscured. 


- [Gender Disparities within the Workplace](https://github.com/jerramcl/women-at-work/tree/main)
  
   This project analyzes gender-based inequalities in salary and leadership representation using data from the National Survey of College Graduates. Through linear and logistic regression modeling, I show that women—especially those with advanced degrees or in the business sector—consistently earn less and are underrepresented in top leadership roles. The analysis highlights how race, education, and family status shape women’s career outcomes and underscores the need for targeted equity interventions.

- [Displacement Risk in LA and SF Counties](https://github.com/jerramcl/rent-burden)

   I analyzed displacement risk in Los Angeles and San Francisco counties by merging CDC health data with U.S. Census housing data. The project compares rent burden and chronic health outcomes across counties and examines vulnerable subgroups (e.g., renters, seniors, children, racial minorities). Findings show that LA faces greater displacement risk, driven by higher rent burden, worse health indicators, and a larger share of marginalized populations.
