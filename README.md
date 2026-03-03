<h1 align="center">
  Django E-Learning Platform 🎓
</h1>

<p align="center">
  <strong>A comprehensive and interactive online learning platform built with Django's MVT architecture.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap" />
  <img src="https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white" alt="PayPal API" />
</p>

---

## 📖 About The Project

> Developed as the final project for the **Web Development (WEGB301)** coursework.

This E-Learning Platform is a robust web application designed to facilitate online education through seamless course consumption and secure e-commerce capabilities. Built entirely on the **Django framework (Python)**, the project strongly adheres to the MVT (Model-View-Template) architectural pattern and the DRY (Don't Repeat Yourself) principle.

The system provides a rich user experience by integrating modern web technologies such as AJAX for asynchronous requests, Fluid Player for video rendering, and the **PayPal API** for real-time checkout processing. It also features a dual-business model, allowing users to either purchase individual courses or subscribe to VIP monthly/annual plans for unlimited access.

---

## 👥 Team Members

*Project developed by **WEB08TEAMPROJECT**.*

| Role | Name | Student ID | Email |
| :--- | :--- | :--- | :--- |
| 👑 **Leader** | **Lê Nguyên Khang** | GCS210650 | `khangln211103@gmail.com` |
| 👨‍💻 **Member** | **Bùi Minh Hoàng** | GCS210950 | `Hoangbmgcs210950@fpt.edu.vn` |

---

## ✨ Implemented Features Showcase

The platform is divided into several modular Django apps (`Account`, `Course`, `Cart`, `Order`). Below is a showcase of the key features successfully implemented in this system:

| Module | Core Functionalities & Features |
| :--- | :--- |
| **🔐 Authentication (Account)** | • Secure Registration & Login/Logout.<br>• Automated **Email Verification** via token generation.<br>• Secure **Password Reset** workflow via email instructions.<br>• Comprehensive User Profile management (update info & avatar). |
| **📚 Course Management** | • Advanced Course Discovery: Search by name and filter by category.<br>• Dynamic **Pagination** (8 courses per page).<br>• Detailed course overview and instructor information.<br>• Custom video rendering using **Fluid Player** for enrolled students. |
| **🛒 E-Commerce & Cart** | • Add/Remove courses to/from the shopping cart dynamically.<br>• Automatic total price calculation. |
| **💳 Payment & Orders** | • Seamless checkout integration using **PayPal API**.<br>• Detailed Order/Payment History dashboard.<br>• Pop-up modals to view specific order invoices and items. |
| **👑 VIP Subscription** | • Monthly ($300) and Annually ($1000) subscription tiers.<br>• **Unlimited access** to all courses for subscribed users.<br>• Real-time expiration date calculation and VIP status badge. |
| **🌟 UI / UX Enhancements** | • Fully responsive design utilizing Bootstrap grid systems.<br>• Interactive pop-ups utilizing **SweetAlert** for user feedback.<br>• Integrated support Chatbot. |

---

## 🛠️ Technology Stack

- **Backend Framework:** Django (Python)
- **Database:** SQLite (Development)
- **Frontend:** HTML5, CSS3, JavaScript, Bootstrap
- **Forms & Validation:** Django Crispy Forms
- **Asynchronous Requests:** AJAX / Fetch API
- **External APIs & Libraries:** PayPal API, SweetAlert, Fluid Player, Owl Carousel

---

## 🏗️ System Architecture

### Entity-Relationship Diagram (ERD)
*Outlines the relational database schema, mapping the relationships between Accounts, Courses, Categories, Carts, and Orders.*
<p align="center">
  <img width="1405" height="1023" alt="erd" src="https://github.com/user-attachments/assets/736a1680-eb42-4b76-9ec7-30cafc62de47" />
</p>

---

## 📸 User Interface Showcase

*A visual tour of the platform's responsive interface and core functionalities.*

### 🌟 Core Experience & Discovery
<table align="center">
  <tr>
    <td align="center" width="50%">
      <img width="975" height="446" alt="image" src="https://github.com/user-attachments/assets/80bdd6ec-1ffd-4119-bd09-c0957be09330" />
      <br/><b>Home Page & Hero Banner</b>
    </td>
    <td align="center" width="50%">
     <img width="975" height="453" alt="image" src="https://github.com/user-attachments/assets/a775bf3e-a576-4861-868b-28672cb952d9" />
      <br/><b>Course Discovery</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
     <img width="975" height="504" alt="image" src="https://github.com/user-attachments/assets/d1cdcfee-705f-40fe-b8b3-e0231f93d8ac" />
      <br/><b>Course Search & Category Filters</b>
    </td>
    <td align="center" width="50%">
 <img width="975" height="407" alt="image" src="https://github.com/user-attachments/assets/897deda0-9f01-428b-b1e4-c9d94ebc4ce0" />
      <br/><b>Interactive Support Chatbot</b>
    </td>
  </tr>
</table>

### 🛒 Commerce & Payment
<table align="center">
  <tr>
    <td align="center" width="50%">
    <img width="975" height="397" alt="image" src="https://github.com/user-attachments/assets/5b4cb5c3-72aa-4a64-90d5-14b8dcdabd0f" />
      <br/><b>Shopping Cart Management</b>
    </td>
    <td align="center" width="50%">
      <img width="975" height="446" alt="image" src="https://github.com/user-attachments/assets/71ffd310-c3a5-4810-afaf-9e638a5e4ac0" />
      <br/><b>PayPal API Checkout Integration</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img width="975" height="409" alt="image" src="https://github.com/user-attachments/assets/4fc6b9c8-e840-4694-8a58-10b875386f18" />
      <br/><b>Payment History</b>
    </td>
    <td align="center" width="50%">
       <img width="975" height="626" alt="image" src="https://github.com/user-attachments/assets/a42c53dc-b94f-438e-8b90-8d708f414178" />
      <br/><b>Order Details & Invoice</b>
    </td>
  </tr>
</table>

### 🎓 Learning & Subscription
<table align="center">
  <tr>
    <td align="center" width="50%">
      <img width="975" height="467" alt="image" src="https://github.com/user-attachments/assets/9e4a4f5f-f50e-4d97-b9b4-68a90f597233" />
      <br/><b>My Learning Hub (Purchased Courses)</b>
    </td>
    <td align="center" width="50%">
   <img width="892" height="408" alt="image" src="https://github.com/user-attachments/assets/4d2348ab-109c-4ebf-8b79-9b02ffe53f4a" />
      <br/><b>Course Video Player</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
       <img width="845" height="435" alt="image" src="https://github.com/user-attachments/assets/ebb1f874-539e-4920-9832-1c3ed440f57c" />
      <br/><b>VIP Subscription Pricing Plans</b>
    </td>
    <td align="center" width="50%">
     <img width="907" height="497" alt="image" src="https://github.com/user-attachments/assets/a6781e5f-8bec-4ccb-a298-51a5dede1bc4" />
      <br/><b>Purchasing Subscription</b>
    </td>
  </tr>
    <tr>
    <td align="center" width="50%">
      <img width="975" height="456" alt="image" src="https://github.com/user-attachments/assets/62f56f69-9f0a-4d28-833b-d1fb8910fbd2" />
      <br/><b>My Learning Hub (VIP Subscription)</b>
    </td>
    <td align="center" width="50%">
     <img width="872" height="507" alt="image" src="https://github.com/user-attachments/assets/a7dec750-a5bd-4546-bfae-7da41b8e0a23" />
      <br/><b>Beautiful SweetAlert Notification</b>
    </td>
  </tr>
  
</table>

### 🔐 Authentication & Profile
<table align="center">
  <tr>
    <td align="center" width="50%">
       <img width="975" height="713" alt="image" src="https://github.com/user-attachments/assets/5f161022-37cc-41de-848a-6ee6ab910cc4" />
      <br/><b>Secure Registration & Login</b>
    </td>
    <td align="center" width="50%">
 <img width="975" height="330" alt="image" src="https://github.com/user-attachments/assets/3bce14e2-3e88-48b6-990e-c13728076a25" />
      <br/><b>Email Verification</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="100%" colspan="2">
   <img width="975" height="552" alt="image" src="https://github.com/user-attachments/assets/502a1405-9d35-4fd2-9447-40229b651451" />
      <br/><b>User Profile Management</b>
    </td>
  </tr>
</table>

---

## 🚀 Getting Started

To run this Django project locally on your machine, follow these steps:

### Prerequisites
* Python 3.8+
* pip (Python package installer)

### Installation Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/khangln2111/Greenwich-WEBG301-Team08-ELearning
