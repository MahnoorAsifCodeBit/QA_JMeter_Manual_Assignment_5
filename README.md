# JMeter REST API Testing Project

This repository contains a basic JMeter test plan demonstrating how to create and test REST API requests using **GET**, **POST**, **PUT**, and **DELETE** methods. It is designed as a beginner-level assignment to learn API testing with Apache JMeter.

## 📌 Objective

To create a simple JMeter test plan that:

- Sends REST API requests (GET, POST, PUT, DELETE)
- Uses hardcoded or sample data
- Displays results in a table and tree view
- Demonstrates understanding of basic JMeter elements

---

## 🧪 Test Plan Steps

### ✅ Step-by-Step Instructions

1. **Create a Thread Group**  
   - Right-click on **Test Plan**  
   - Select `Add > Threads (Users) > Thread Group`

2. **Add HTTP Samplers for API Requests**  
   - Right-click on **Thread Group**  
   - Select `Add > Sampler > HTTP Request`  
   - Create separate samplers for each method: **GET**, **POST**, **PUT**, **DELETE**

3. **Configure Each HTTP Request**
   - Set the **Server Name**, **Method**, **Path**, and **Body Data** if required
   - Example:
     - Method: `POST`
     - Body Data:
       ```json
       {
         "name": "John",
         "email": "john@example.com"
       }
       ```

4. **Add Listeners**
   - Right-click on **Thread Group**
   - Add the following:
     - `Listener > View Results Tree`
     - `Listener > View Results in Table`

5. **Save the Test Plan**
   - Save the project as a `.jmx` file

6. **Run the Test**
   - Click the green **Start** button in the toolbar
   - Check results in the **table** and **tree** view

---

---

## 🛠 Tools Used

- [Apache JMeter](https://jmeter.apache.org/) – Load testing and performance tool
- RESTful APIs – Sample APIs used for demonstration

---

## 📬 Author

Created by Mahnoor Asif – as part of internship/assignment work to learn API testing in JMeter.

---

