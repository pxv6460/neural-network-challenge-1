# neural-network-challenge-1



I was having trouble with the load_model part of the homework until I realized that load_model was not part of the imports for tenserflow.keras.models so I added it to the import, it works fine now.

**1. Describe the data that you would need to collect to build a recommendation system to recommend student loan options for students. Explain why this data would be relevant and appropriate.**

loan amount, student's academic performance, credit score, income, and employment status. These are important because they directly impact the students ablility to repay the loans and show the risks associated with giving the loan. Example a high loan amount may lead to an increase in payment difficulty for the student


**2. Based on the data you chose to use in this recommendation system, would your model be using collaborative filtering, content-based filtering, or context-based filtering? Justify why the data you selected would be suitable for your choice of filtering method.**

The model I would use wouls be content-based filtering. The reason content based filtering was chosen would be that the features chosen are specific characteristics of the student that influence loan decisions. This would make the model be able to recomend good loan terms, intreset rates and repayment plans


**3. Describe two real-world challenges that you would take into consideration while building a recommendation system for student loans. Explain why these challenges would be of concern for a student loan recommendation system.**

One challenge would be data privacy as the system would require access to sesitive data that is personal to the student such as financial information like credit scores and income. The concern would then be regulations like CCPA have strict requirements on collecting personal data which could lead to legal penalties and or damage to the rep of the company or organization collecting the data 

Another challenge would be incomplete data or data that is inconsistant. Examples being students could have gaps in their credit histories, inaccuriate income which can lead to the model being unreliable and would need human intervention
