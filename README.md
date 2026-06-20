# 🚀 jsonplaceholder.typicode API Testing with Apache JMeter

<div align="center">

![JMeter](https://img.shields.io/badge/Apache-JMeter-D22128?style=for-the-badge\&logo=apache)
![API Testing](https://img.shields.io/badge/API-Testing-blue?style=for-the-badge)
![FakeStoreAPI](https://img.shields.io/badge/FakeStoreAPI-REST-green?style=for-the-badge)

**Performance & Functional Testing of Fake Store API using Apache JMeter**

</div>

---

## 📌 Overview

This project contains an **Apache JMeter Test Plan** for testing endpoints of the **Fake Store API**.
It demonstrates how to perform:

* ✅ GET requests
* ✅ POST requests
* ✅ PATCH requests
* ✅ Response validation
* ✅ API performance testing

---

## 📂 Project Structure

```text
.
├── FAKEAPI-Request.jmx      # JMeter test plan
├── README.md               # Project documentation
```

---

## 🛠 Tools Used

| Tool           | Purpose                 |
| -------------- | ----------------------- |
| Apache JMeter  | API Testing             |
| Fake Store API | Test REST Endpoints     |
| JSON           | Request & Response Data |

---

# ⚡ Tested Endpoints

## 1️⃣ GET Products

Retrieve all products.

```http
GET https://jsonplaceholder.typicode.com/posts
```

### Expected Response

```json
[
  {
    "id": 1,
    "title": "Product Name",
    ...
  }
]
```

---

## 2️⃣ POST Product

Create a new product.

```http
POST https://jsonplaceholder.typicode.com/posts
```

### Request Body

```json
{
  "title": "New Product",
  "price": 100
}
```

---

## 3️⃣ PATCH Product

Update an existing product.

```http
PATCH https://jsonplaceholder.typicode.com/posts/7
```

### Request Body

```json
{
  "title": "Updated Product"
}
```

---

# 📋 Test Plan Details

### Thread Group

```text
Fake-API_testing Group
```

### HTTP Requests Included

| Request            | Method |
| ------------------ | ------ |
| GET-HTTP Request   | GET    |
| POST-HTTP Request  | POST   |


---

# ▶️ Running the Test

### Open JMeter

```bash
ApacheJMeter.jar
```

### Load Test Plan

```
File → Open → FAKEAPI-Request.jmx
```

### Run Test

Click:

```text
Start ▶
```

---

# 📊 View Results

Use:

* View Results Tree
* Response Data
* Request Details
* JSON Response

---

# 🎯 Learning Objectives

This project demonstrates:

* REST API testing with JMeter
* Sending GET, POST and PATCH requests
* Working with JSON payloads
* Inspecting responses
* Understanding API workflows

---

# 🚀 Future Improvements

* [ ] Add DELETE request
* [ ] Add Assertions
* [ ] Add CSV Data Set Config
* [ ] Add Load Testing
* [ ] Add HTML Dashboard Report
* [ ] Add Response Time Graphs

---

## 👨‍💻 Author

**Aryan Kale**

---

### ⭐ If you found this project useful, give it a star!
