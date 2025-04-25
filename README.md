# 🌸 Web Dashboard for Perfume Store  

An interactive and responsive web-based dashboard designed to help perfume store owners make data-driven decisions through clear visualizations and intelligent forecasts.  

[🔗 Live Project Link](https://project-dashboard-wc9p.onrender.com)  
[📊 Kaggle Dataset](https://www.kaggle.com/datasets/kanchana1990/perfume-e-commerce-dataset-2024/data)  

---  

## 📌 Project Overview  

This project analyzes an e-commerce perfume dataset to create a comprehensive digital dashboard. It provides summary insights, detailed gender-based analysis, and future sales forecasts to support decision-making.  

---  

## 🔑 Key Features  

- 🌍 **Homepage** – General statistics and quick links to analysis sections  
- 📋 **General View** – Comprehensive visual analysis  
- 👨 **Men's Section** & 👩 **Women's Section** – Targeted gender-based visual analysis  
- 📈 **Forecasts Page** – Linear regression-based predictions  
- 🔐 **Secure Registration/Login System** – With email verification  
- 🌗 **Light/Dark Mode** – Built-in theme switching  
- 📱 **Responsive Design** – Compatible with all devices  

---  

## 📄 Dashboard Pages  

### 1. **Home Page**  
- Entry page after login  
- Key metrics:  
  - Market growth  
  - Number of fragrances  
  - Countries covered  
- Quick links to "Men", "Women", and "Forecasts" sections  

### 2. **General View**  
- Table listing all products  
- Displayed fields:  
  - Brand  
  - Type  
  - Price  
  - Availability  
  - Sold Quantity  
- Charts (bar, scatter) to analyze correlations (e.g., price vs. sales)  

### 3. **Men's & Women's Sections**  
- Specific analysis for men's and women's perfumes  
- Visual statistics including:  
  - Top brands by category  
  - Average price trends  
  - Stock availability and sales performance by gender  

### 4. **Prediction Page**  
- Sales trend predictions using linear regression  
- Trend graphs with confidence intervals  
- Key metrics:  
  - Estimated revenue  
  - Average product price  
  - Confidence score (e.g., 90%, 100%)  
- Dynamic filters: gender, brand, type, or perfume name  

### 5. **Login/Registration**  
- Registration form: name, email, password  
- Email verification with manual admin approval   
- Secure backend with Node.js and MongoDB  

---  

## 🛠️ Technologies Used  

### **Front-End:**  
- **React.js** – Interactive UI  
- **Tailwind CSS** – Modern modular design  
- **HTML & JavaScript** – Base structure and functionality  

### **Back-End:**  
- **Node.js + Express** – Server logic and API  
- **MongoDB** – Secure user storage  
- **Python** – Data cleaning and preparation  

### **Development Tools:**  
- Git & GitHub  
- Visual Studio Code  
- Kaggle for data acquisition  

---  

## 🔐 Security Features  

- Email verification for registration  
- Bcrypt password hashing  

---  

## 📦 Local Project Setup    
```bash
git clone https://github.com/ChaimaMansouri/Perfume_Dashboard.git
cd Front_end
npm install
cd ../Back_end
npm install
npm start
