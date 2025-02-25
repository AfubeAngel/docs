### **TMDB API Recreation – Capstone Project**  

🚀 The Movie Database (TMDB) API is a powerful and widely used API that provides extensive data on movies, TV shows, actors, and images. It serves as a key resource for developers building entertainment-based applications, offering access to a vast collection of metadata, including ratings, trailers, and posters.

This project is a recreation of the TMDB API, focusing on API documentation best practices and improving developer experience. 

![The TMDB API](https://github.com/user-attachments/assets/0d1330f0-e8ce-4e6a-8215-8c24ab220a92)

<br>

## **📌 Project Overview**  
This project involves **exploring, documenting, and recreating The Movie Database (TMDB) API** to provide clear and structured API documentation. The process includes:  
- API **exploration & documentation** using **Postman**  
- Conversion of the documentation to **OpenAPI Specification (OAS)**  
- Enhancing the OpenAPI spec with detailed examples and authentication info  
- Uploading the final documentation to **Mintlify** for a user-friendly API guide  

<br>

## **🛠️ Tech Stack**  
- **Postman** – API request testing & documentation  
- **Swagger,io** – Standardized API documentation  
- **Mintlify** – Modern and interactive API documentation platform  

<br>

## **📜 Steps to Recreate TMDB API Docs**  

### **1️⃣ API Documentation in Postman**  
- Explored and tested TMDb API endpoints  
- Documented authentication, request methods, headers, parameters, and responses  
- Organized into a structured Postman **Collection**  

![TMDB-PostmanCollection](https://github.com/user-attachments/assets/029e5deb-0a0f-419b-9552-6abd28a4eae1)


### **2️⃣ Convert Postman Docs to OpenAPI**  
- Exported the Postman collection as an **OpenAPI Spec (YAML/JSON)**  
- Ensured correct endpoint details, authentication, and response examples
  

### **3️⃣ Enhance OpenAPI Spec in Swagger**  
- Improved endpoint descriptions and explanations  
- Added detailed request/response examples  
- Verified all authentication and error-handling scenarios  

### **4️⃣ Further enhancement and deployment on Mintlify**  
- Uploaded the final OpenAPI spec to **Mintlify**  
- Customized the UI for better readability and user engagement  

#### Development om Mintlify

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where mint.json is)

```
mintlify dev
```

#### Publishing Changes

Changes will be deployed to production automatically after pushing to the default branch.


<br>

## **🔗 Live API Documentation**  
📌 **Mintlify Docs:** [🔗 View Here](https://angel.mintlify.app/introduction)
 






