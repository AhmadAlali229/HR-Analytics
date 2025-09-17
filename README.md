# HR Analytics Dashboard  

This project uses the  HR Employee Attrition dataset.
The analysis part (dbDemo.ipynb) applies SQL and Python queries to explore the data, such as counting employees, checking departments, calculating average income, and looking at performance and job satisfaction. 
The dashboard part (app.py) is built with Streamlit and shows interactive charts and tables, with options to filter by department, add new employees, and update existing salaries. Both parts work together to make the HR data easier to study and manage.  
 

---

## Files in this project  

- **app.py** → Streamlit web application (dashboard) with three main tabs:  
  - *Overview* → Data visualizations  
  - *Add Employee* → Form to insert new employee records into the database.  
  - *Update Income* → Tool to update an employee’s monthly income.  

- **dbDemo.ipynb** → Jupyter Notebook containing SQL queries and Python analysis. It demonstrates data exploration and answers business-related questions.  

- **employees.db** → SQLite database storing processed employee data.  

- **WA_Fn-UseC_-HR-Employee-Attrition.csv** → Original HR dataset.  

- **README.md** → Project documentation.  

