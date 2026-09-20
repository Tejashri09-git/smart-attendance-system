# Smart Attendance System on Cloud

## Project Overview

Smart Attendance System is a cloud-based attendance application developed using Amazon Web Services (AWS).

The system allows students to mark attendance through a web interface. Attendance data is processed using AWS Lambda and stored in Amazon DynamoDB. An attendance dashboard displays the stored records.

## AWS Services Used

- Amazon S3 – Hosts the website
- Amazon API Gateway – Provides REST API
- AWS Lambda – Processes attendance requests
- Amazon DynamoDB – Stores attendance records
- AWS IAM – Manages permissions
- QR Code – Provides quick access to the attendance website

## Architecture

QR Code
↓
S3 Hosted Website
↓
API Gateway
↓
AWS Lambda
↓
DynamoDB
↓
Attendance Dashboard

## Features

- Student attendance marking
- QR-based website access
- Automatic attendance data storage
- Attendance dashboard
- Cloud-based architecture
- REST API integration

## Technologies

- HTML
- CSS
- JavaScript
- Python
- AWS

## Project Outcome

The project demonstrates how AWS cloud services can be integrated to build a simple and automated attendance management system.
