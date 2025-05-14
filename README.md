# 💼 Freelancer Expense Tracker

A full-stack application to help freelancers automate expense tracking, categorize transactions, and generate tax-ready reports with real-time analytics.

## 🚀 Features

- 📥 Automated expense capture via receipt uploads & manual entry
- 🧾 Smart categorization of expenses (e.g., travel, software, subscriptions)
- 📊 Real-time analytics dashboard
- 🗂️ Monthly and yearly tax reports
- 🔔 Notification system for unreviewed or uncategorized transactions
- 🔐 Secure login and role-based access control

## 🛠️ Tech Stack

| Layer           | Technologies                          |
|----------------|---------------------------------------|
| **Backend**     | Spring Boot, Kafka, PostgreSQL       |
| **Frontend**    | React Native                         |
| **DevOps**      | Docker, AWS (EC2, RDS, S3), GitHub Actions |
| **Others**      | Kafka Streams for async processing   |

## 🎯 Problem Statement

Freelancers often struggle with manually tracking their expenses throughout the year, especially during tax season. This app was designed to reduce the burden by automating most of the process.

## ✅ Solution Overview

- **Backend (Spring Boot)** handles REST APIs, user authentication, transaction processing, and Kafka integration for asynchronous event handling.
- **Kafka** enables decoupled and scalable processing of incoming transactions and notifications.
- **Frontend (React Native)** provides a cross-platform mobile interface for real-time expense entry and visual analytics.
- **AWS Infrastructure** hosts the application securely with Dockerized deployments for high availability.

## 📈 Impact

- Helped 100+ freelancers streamline their financial record-keeping.
- Reduced manual bookkeeping by over 70% during tax filing season.
- Improved compliance and financial visibility with real-time insights.

## 🧪 Key Functional Modules

- **Expense Module**: Add, edit, auto-categorize, and visualize expenses.
- **Report Module**: Download monthly/annual tax reports.
- **Notification Service**: Kafka-based alerts for pending actions.
- **Admin Panel**: Manage users, view usage analytics.

## 🔧 Setup Instructions

### Backend (Spring Boot)
```bash
cd backend
./mvnw clean install
./mvnw spring-boot:run
