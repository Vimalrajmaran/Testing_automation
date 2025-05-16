# 🛍️ Amazon Product Search Automation using Selenium & Java

This project automates the Amazon.in product search workflow using **Selenium WebDriver** and **Java**, showcasing essential test automation practices including interaction, filtering, and data extraction.

---

## 📌 Project Overview

- **Search Term:** "Bags for boys"
- Applies brand and customer rating filters
- Sorts by **Newest Arrivals**
- Extracts product details:
  - Product **Title**
  - **Current Price** and discount
  - **MRP** (Original price)

---

## 🚀 Features

- ✅ Launches browser and navigates to Amazon.in
- ✅ Searches for a product keyword
- ✅ Applies filters and sorting
- ✅ Extracts and prints the title, current price, and MRP of the first result
- ✅ Displays total result count and page title
- ✅ Uses implicit wait for element synchronization

---

## 🛠️ Tech Stack

| Tool/Tech         | Version / Notes                   |
|-------------------|-----------------------------------|
| Java              | JDK 8+                            |
| Selenium WebDriver| 4.x                               |
| SafariDriver      | macOS native WebDriver support    |
| IDE               | Eclipse / IntelliJ                |
| Browser           | Safari (adaptable to Chrome/Firefox) |

---

## 🧩 Folder Structure

project-root/
└── src/
└── week3/
└── day3/
└── marathon/
└── AmazonSearch.java

yaml
Copy
Edit

---

## 📋 How to Run

1. Clone the repo  
   ```bash
   git clone https://github.com/your-username/amazon-search-automation.git
Open in Eclipse or IntelliJ

Ensure Safari’s WebDriver is enabled via terminal:

bash
Copy
Edit
safaridriver --enable
Run AmazonSearch.java as a Java application

🔮 Future Enhancements
Replace Thread.sleep() with WebDriverWait for robustness

Modularize using Page Object Model (POM)

Parameterize search term and filters

Add support for multiple browsers via WebDriverManager

Integrate with TestNG & CI tools (Jenkins, GitHub Actions)

📎 Author
Vimalraj Tamilmaran
📧 mathivimalrajmaran@gmail.com
