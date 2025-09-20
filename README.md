**Project**: Retail Customer Transaction Data
**Source**: https://www.kaggle.com/datasets/sahilprajapati143/retail-analysis-large-dataset
**Size**: 302,000 rows x 30 columns
**The Purpose of the Project**: 


**Tools** - 
**Python**:
- Pandas
- Matplotlib
- Seaborn
**MySQL**
**Power BI**


**Structure**: 
- Data Cleaning using Python
- Information Extraction with MySQL
- Data Visualization using Power BI

**The Project: Retail Customer Transaction Data**
**Python**: According to the source, the dataset contains null values and duplicates. 
The null values in the categorical columns have been filled with the expression 'Not Provided'. Other options were not considered to replace the null values not to distort the original data:
<img width="1598" height="86" alt="Ekran görüntüsü 2025-09-20 215243" src="https://github.com/user-attachments/assets/b96b0af9-97a7-42f0-8ac7-708b281a6c21" />



The null values in the numerical columns are substituted with the median:
<img width="720" height="79" alt="Ekran görüntüsü 2025-09-20 235701" src="https://github.com/user-attachments/assets/091959f2-889b-4708-81c1-b4ab69d0526c" />


The duplicates were removed:
<img width="1728" height="554" alt="Ekran görüntüsü 2025-09-20 235917" src="https://github.com/user-attachments/assets/1bf083b6-7e1b-4bad-8c96-7abfe54a92c3" />
<img width="319" height="40" alt="Ekran görüntüsü 2025-09-20 235931" src="https://github.com/user-attachments/assets/567b73ce-9010-48a2-be33-d8cb482e2684" />

Now it 's the time to use the MySQL to acquire information related to the dataset: 

The average customer is around 44 years old, so customer base likely skews middle-aged:
<img width="553" height="45" alt="Ekran görüntüsü 2025-09-17 182309" src="https://github.com/user-attachments/assets/ccb731d6-32d0-4463-9bfd-b59e3cb6b2a9" />

Based on Revenue, the clients spend money for books and grocery the most:
<img width="495" height="134" alt="Ekran görüntüsü 2025-09-17 190757" src="https://github.com/user-attachments/assets/4f947a4a-b0bc-4c05-8c4f-2e69676e30bb" />

England, Ontario, and Berlin are the states and Portsmouth, Kitchener, and Dortmund are the cities where the most of the purchases have been performed, which means that the company makes the profit the most from these places. 
<img width="308" height="93" alt="Ekran görüntüsü 2025-09-17 190953" src="https://github.com/user-attachments/assets/23f6d0ac-c570-4c64-a23f-79e1db82fc43" />
<img width="298" height="89" alt="Ekran görüntüsü 2025-09-17 194725" src="https://github.com/user-attachments/assets/2c7e3483-ad0e-4114-af33-77fa2fd8a18d" />

Penguin Books leads among the brands, hitting the highest revenue, while Ikea comes the last on the list. 
<img width="351" height="346" alt="Ekran görüntüsü 2025-09-17 191842" src="https://github.com/user-attachments/assets/bfe97a16-c026-4b72-8bb5-6b7ec14d6d2d" />

As seen, customers prefer to pay with a credit card, followed by a debit card.
<img width="231" height="115" alt="Ekran görüntüsü 2025-09-17 192341" src="https://github.com/user-attachments/assets/1d2b2b0e-57b7-4e8f-9b6b-2de3bbd66f53" />

Based on the results, it is obvious that total sales boosted in January, 2024.
<img width="351" height="346" alt="Ekran görüntüsü 2025-09-17 191842" src="https://github.com/user-attachments/assets/2aee087b-cccd-446b-851f-6177c36f2256" />

Zachary Abbott and Shelby Perry are the highest-spending customers. Such information should be taken into account to turn them into loyal customers so that the revenue may increase thanks to such clients.
<img width="351" height="346" alt="Ekran görüntüsü 2025-09-17 191842" src="https://github.com/user-attachments/assets/a415a4cd-9c1b-4ae7-8095-9587e873e8d4" />


Continued...

