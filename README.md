# Ecommerce-ML-Product-Detection

# Project Overview

This project focuses on developing a comprehensive system for product recommendation, OCR-based query processing, and image-based product detection. The system is divided into four modules, each addressing specific aspects of the development process.

## Modules

### Module 1: Data Preparation and Backend Setup

- **Task 1: Data Cleaning**
  - Remove duplicates, handle missing values, and standardize formats.

- **Task 2: Vector Database Creation**
  - Set up a vector database using Pinecone to store product vectors.

- **Task 3: Similarity Metrics Selection**
  - Choose and implement similarity metrics (e.g., cosine similarity) for product vector comparison.

### Module 2: OCR and Web Scraping

- **Task 4: OCR Functionality Implementation**
  - Develop the capability to extract text from images using OCR technology.

- **Task 5: Web Scraping for Product Images**
  - Automate scraping of product images from e-commerce websites for training data.

### Module 3: CNN Model Development

- **Task 6: CNN Model Training**
  - Train a CNN model from scratch using product images to identify products.

### Module 4: Frontend Development and Integration

- **Task 7: Frontend Interfaces**
  - Develop basic HTML interfaces for text and image-based product queries.

## Challenges Faced

The project encountered several challenges, including:

- Overcoming web scraping restrictions (403 and 503 errors) from e-commerce websites.
- understanding the dataset
- building a dataset from scraping website due to webscraping restrictions
- dealing with the cnn structure
- Integrating with Pinecone for efficient storage and retrieval of product vectors.

## Endpoint Thought Process

Endpoints were designed to:
- Handle natural language queries and OCR-based queries for product recommendations.
- Process image-based queries using a trained CNN model for product detection.

## Key Skills Demonstrated

As a ML engineer and data engineer, key skills demonstrated include:

- Data cleaning and preprocessing.
- Model development and training.
- Integration with external services (Pinecone).
- Basic HTML knowledge for interface development.
