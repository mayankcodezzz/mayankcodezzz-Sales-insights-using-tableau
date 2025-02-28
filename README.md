# Sales Insights Using Tableau

## Aims Grid 
An Aims Grid is a strategic planning tool that helps project teams define goals, activities, stakeholders, resources, and metrics.

![(1) Tableau Project For Beginners _ Sales Insights _ 2 - Data Discovery - YouTube - Google Chrome 11_8_2024 12_58_15 PM](https://github.com/user-attachments/assets/92f64c28-77bf-4203-b4c6-ffe08d886979)

## Understanding the DataBase
Here we have sales management system : It is used to store the data, which is then stored in Mysql and managed by a team(falcons).

![Editing mayankcodezzz-Sales-insights-using-tableau_README md at main · mayankcodezzz_mayankcodezzz-Sales-insights-using-tableau - Google Chrome 11_8_2024 12_59_21 PM](https://github.com/user-attachments/assets/c19324da-9d90-48fb-b0f6-89975c25efac)

## For This project to keep things simple we will directly access data from mysql but the better approach would always be to first store the data in data warehouse and the use it for the analytical purpose accordingly
So Here you can use the Two systems,
Online analytical processing (OLAP) and online transaction processing (OLTP) are both data processing systems that help businesses store and analyze data. The main difference between the two is that OLAP is used for complex analysis, while OLTP is used for real-time transaction processing: 
### OLAP
Used for complex data analysis, such as data mining, analytics, and business intelligence. OLAP systems organize large databases and are optimized for heavy read, low write workloads. 

![Editing mayankcodezzz-Sales-insights-using-tableau_README md at main · mayankcodezzz_mayankcodezzz-Sales-insights-using-tableau - Google Chrome 11_8_2024 1_03_16 PM](https://github.com/user-attachments/assets/4c7c88bf-5026-4dd1-8dcc-c7dc31053d5c)

### OLTP
Used for real-time processing of online transactions at scale. OLTP systems store and update transactional data reliably and efficiently. 

![Editing mayankcodezzz-Sales-insights-using-tableau_README md at main · mayankcodezzz_mayankcodezzz-Sales-insights-using-tableau - Google Chrome 11_8_2024 1_03_37 PM](https://github.com/user-attachments/assets/cf372743-ab7d-43e5-86ba-029b4e5b5e7e)

# Now Let's use Tableau For the Creation of interactive Dashboard
First Connected the Mysql With Tableau Also installed Drivers Required then Followed the Steps below i have also cleaned the data like negative values using filter funtion and i have also converted the 2 USD transaction amount into INR by Creating a new column and named it as normalized_amount also note here i am creating Sheets for each widget and then in the end i will combine all widgets that i have created below

## Sheets

![Tableau - Book1 - Tableau license expires in 14 days 11_7_2024 6_55_21 PM](https://github.com/user-attachments/assets/9184a828-3faa-4bd4-8edd-44959ee27863)

![Tableau - Book1 - Tableau license expires in 14 days 11_7_2024 7_17_43 PM](https://github.com/user-attachments/assets/4a47a7c3-06f4-4af0-9aa9-fc4cccaa9be6)

![Tableau - Book1 - Tableau license expires in 14 days 11_7_2024 7_17_50 PM](https://github.com/user-attachments/assets/99f9b4dc-c0a5-4d17-8812-987feb7ef226)

![Tableau - Book1 - Tableau license expires in 14 days 11_7_2024 7_18_51 PM](https://github.com/user-attachments/assets/9daad465-109c-469e-abeb-0a6fdb43aeba)

![Tableau - Book1 - Tableau license expires in 14 days 11_7_2024 7_18_56 PM](https://github.com/user-attachments/assets/4cf7337f-c593-4a9b-bf74-99c4be1af052)

![Tableau - Book1 - Tableau license expires in 14 days 11_7_2024 7_22_48 PM](https://github.com/user-attachments/assets/7708ffa1-e3a4-4c2d-b897-95809de00be3)

![Tableau - Book1 - Tableau license expires in 14 days 11_7_2024 7_22_55 PM](https://github.com/user-attachments/assets/db3f4fe8-73da-4870-9897-c1738601d665)

![Tableau - Book1 - Tableau license expires in 14 days 11_7_2024 7_23_52 PM](https://github.com/user-attachments/assets/b3e05412-c7a2-4140-ae83-9f081a5209ee)

![Tableau - Book1 - Tableau license expires in 14 days 11_7_2024 7_25_20 PM](https://github.com/user-attachments/assets/578b2cbf-deeb-4d1c-9f54-5c832804f81d)

![Tableau - Book1 - Tableau license expires in 14 days 11_7_2024 7_25_28 PM](https://github.com/user-attachments/assets/6f03a0be-e818-45eb-8249-e1da33990d69)

![Tableau - Book1 - Tableau license expires in 14 days 11_7_2024 7_25_33 PM](https://github.com/user-attachments/assets/7c94023f-089f-419b-b59f-2c183dbe3a8b)

![Tableau - Book1 - Tableau license expires in 14 days 11_7_2024 7_26_32 PM](https://github.com/user-attachments/assets/0e86a3b3-7812-4e40-b980-ca94a522cfb5)

![Tableau - Book1 - Tableau license expires in 14 days 11_7_2024 7_27_36 PM](https://github.com/user-attachments/assets/807f1468-aa46-488a-8a27-1289b3e06c05)

![Tableau - Book1 - Tableau license expires in 14 days 11_7_2024 7_40_18 PM](https://github.com/user-attachments/assets/7607406b-8f67-49ec-8be4-0abe663032b6)

![Tableau - Book1 - Tableau license expires in 14 days 11_7_2024 7_43_36 PM](https://github.com/user-attachments/assets/1ed9a3d8-5ff8-4a7e-918a-f4263571341a)

## Dashboard

![Tableau - Book1 - Tableau license expires in 14 days 11_7_2024 7_43_53 PM](https://github.com/user-attachments/assets/57eddfa1-3fa6-4359-b4ca-8bb8a562532b)

![Tableau - Book1 - Tableau license expires in 14 days 11_7_2024 7_55_50 PM](https://github.com/user-attachments/assets/a368eec3-9cb9-401e-85a9-839aa375232c)

![Tableau - Book1 - Tableau license expires in 14 days 11_7_2024 7_56_59 PM](https://github.com/user-attachments/assets/a7e88380-fb45-400c-9b6b-08379fbd92cf)

![Tableau - Book1 - Tableau license expires in 14 days 11_7_2024 7_57_07 PM](https://github.com/user-attachments/assets/6c481b2b-ee78-4b25-9b80-ce27a7850da9)

![Tableau - Book1 - Tableau license expires in 14 days 11_7_2024 7_57_31 PM](https://github.com/user-attachments/assets/a481dd3e-8df8-4d60-9002-25608c8edf40)
