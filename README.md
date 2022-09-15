# Employee-Management-System-with-Machine-Learning
Employee Management System modules incorporated with Machine Learning features like Salary Prediction and Attendance via Facial Recognition

# Features of this project:
- It can perform CRUD operations like: add/delete employees, view their details, update salary, generate employee and salary reports
- Provides employees the ability to apply for leaves
- Apart from the basic authentication method, it also has an option for Two Factor Authentication via the google authentication method
- Makes use of AuthGuard, which prevents redirection to any web page until the authentication process completes. It is a safeguard against the Broken Access Control     vulnerability
- Using Machine Learning, we have built and embedded a salary prediction model in our project, that predicts the salary of an employee based on their age and years of   experience.
- Using Machine Learning, we have built a model that when fed with a dataset containing photos of various individuals, it trains itself, and then when fed with live     broadcast of the person, it detects who the person in the broadcast is.

# Tools and Technologies Used:
- For Frontend : HTML , CSS , JavaScript,  Bootstrap(an open-source CSS framework), Angular(using typescript).
- For Backend : Core Java , Spring Boot Framework , REST API , JPA.
- Machine Learning
- Database : MySQL

# Machine Learning Libraries and Modules used:
1. For Salary Prediction Model: 
    (i) Numpy- For linear algebra 
    (ii) Pandas- For data processing, CSV file I/O (example: pd.read_csv)
    (iii) Matplotlob.pyplot- For plotting purposes
    (iv) train_test_split- For training the model using 75% of dataset, and testing the model on 25% of the dataset
         Imported from package: sklearn.model_selection
    (v) LinearRegression,Lasso,Ridge,ElasticNet- Imported all these models to compare their accuracies and use the best one
        Imported from package: sklearn.linear_model
    (vi) Gradio- To build GUIs specifically for machine learning

2. For Attendance via Facial Recognition:
    (i) Cv2- Open-cv, used for video and image processing, and analysis
    (ii) Numpy- For linear algebra and working with arrays
    (iii) Face_recognition- For facial detection and analysis
    (iv) Datetime- For current date and time features
    (v) OS- For read and write functions on a file

# Steps for Running Spring Boot and Angular Project:
    Step 1: Run Angular Code
        1. Open CMD and open angular folder there in CMD. Run Command
        2. npm install
        3. Install angular Latest version command: npm install -g @angular/clilatest
        4. Run command
        5. Ng Serve
        6. Open browser and open the URL:http://127.0.0.1:4200
        This will display you the frontend
        
    Step 2: Run and configure the database part
        1. Open the URL http://127.0.0.1/phpmyadmin
        2. Choose the database from left side panel
        3. Click on Import and choose the sql file from extracted project folder
        4. Click on Go, all the tables will be imported into the database.
        
    Step 3: Run Xampp
        1. Start XAMPP –Apache and Mysql services
        2. Open CMD and run command: ng serve from angular folder
        3. Open STS Right Click on Project >> Run As >> SpringBootApp
        4. Open the browser
        5. Open the URL http://127.0.01:4200
        
    Step 4: Run project
        1. Right click on the project
        2. Click on ‘Run it as SpringbootApp’
