# About the Project 
This is a project for the subject Programming for Data Analytics at Rennes School of Business. It aims to analyze the factors influencing flight ticket prices using two datasets, referred to as data_f1 and data_f2, which contain various attributes related to flights, such as departure and arrival times, airline carriers, flight duration, and additional features like layovers and seasonal trends. By employing descriptive analytics, exploratory data analysis (EDA), and predictive modeling techniques, we seek to identify key variables that significantly impact ticket prices.  

Our approach includes visualizing data distributions, examining correlations between different factors, and building predictive models to forecast ticket prices based on the identified influential variables. The insights derived from this analysis will not only enhance our understanding of pricing strategies in the airline industry but also equip travelers with knowledge to make informed decisions when purchasing tickets.   

The analysis will employ descriptive analytics, exploratory data analysis (EDA), and predictive analytics to uncover insights into the pricing dynamics of multiple airlines. Through collaboration among our team of five university students, we aim to leverage our diverse skill sets in programming, data analysis, and statistical modeling to deliver a comprehensive report that addresses the research question: "Which factors influence the ticket price more?" 

## Team member
*   **[Kuan-Yu HOU](https://github.com/DoreenHou)** 
*   **[María Teresa Hidalgo](https://github.com/Teresiux14)**   
*   **[Annie HUNG](https://github.com/RUEI-CHIEH)**
*   **[Yi-Hsin TUNG](https://github.com/evatung0719)**
*   **[Xian Harding Anglés](https://github.com/r41ss4)**    

## The Dataset
The datasets have been obtained through **[Kaggle](https://www.kaggle.com/)** platform and selected to provide relevants insights regarding flights pricing. 
*   **data_f1:** It includes a wide range of features and variables, such as flight routes, departure and arrival cities, airline carriers, departure and arrival times, ticket class, and more. It was extracted from **[Flight Price Prediction](https://www.kaggle.com/datasets/muhammadbinimran/flight-price-prediction)**      
*   **data_f2:** Dataset contains information about flight booking options from the website Easemytrip for flight travel between India's top 6 metro cities. There are 300261 datapoints and 11 features in the cleaned dataset. It was extracted from **[Flight Fare Prediction | 10 ML Models](https://www.kaggle.com/code/varunsaikanuri/flight-fare-prediction-10-ml-models/notebook)**         

## Folders and organization 
```
rennes_da/          
│           
├── data/         
│   ├── raw/                   
│   │   ├── data_f1.csv               
│   │   └── data_f2.csv     
│   ├── cleaned/        
│   │   ├── clean_dataf1.csv        
│   │   └── clean_dataf2.csv            
│   └── merged/         
│       └── merged_df.csv           
│                       
├── notebooks/                    
│   ├── descriptive.ipynb         
│   ├── cleaning.ipynb          
│   ├── diagnostic.ipynb 
│   ├── EDA.ipynb          
│   ├── merging_data.ipynb          
│   ├── predictive.ipynb      
│   └── prescriptive.ipynb                
│       
├── .ipynb_checkpoints/     
├── .jupyter/           
├── .virtual_documents/         
├── .DS_Store     
├── Insights.md               
└── README.md          
```

## Methodology
**1. Data Cleaning:** We will preprocess the datasets to handle missing values, outliers, and inconsistencies.          
**2. Exploratory Data Analysis (EDA):** Conduct visualizations and statistical analyses to understand relationships between ticket prices and other variables.      
**3. Descriptive Analytics:** Generate summary statistics to provide insights into the datasets.     
**4. Diagnosic Analysis:** Investigate root causes of observed patterns and anomalies in the data.      
**4. Predictive Analytics:** Build predictive models to estimate ticket prices based on the identified factors.     
**5. Prescriptive Analytics:** Develop optimization models to recommend pricing strategies that maximize revenue or market share.   

## Conclusions
Feel free to review our findings in the file **[Insights.md](https://github.com/r41ss4/rennes_da/blob/main/Insights.md)**. For more information, there is a full report available by request to team members of the project. 

## Tools and Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- Visual Studio Code 
- GitHub repository

