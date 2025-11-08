# 📚 Udemy Course Recommendation System

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Flask](https://img.shields.io/badge/Web%20App-Flask-green.svg)](https://flask.palletsprojects.com/)
[![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)](https://github.com/harounerez/recommendation_system/blob/main/LICENSE)

This project implements an end-to-end **content-based recommendation system** for suggesting relevant online courses scraped from the Udemy platform. It covers the full machine learning lifecycle, from **data scraping** and **EDA** to **model training**, **serialization**, and deployment into a live **web application** using Flask.

---

## ✨ Features

* **Web Scraping:** Includes a custom script (`scrap_udemy.py`) to gather up-to-date course data from Udemy.
* **Data Processing & EDA:** Jupyter Notebooks are used for in-depth exploratory data analysis and feature engineering on the course data.
* **Recommendation Model:** A **Random Forest (RF) model** is trained to predict course relevance or suitability based on course features.
* **Content-Based Filtering:** The system suggests courses similar to those a user has previously shown interest in.
* **Web Application:** A simple, interactive user interface built with **Flask** allows users to input their preferences and receive real-time course recommendations.

---

## 🛠️ Tech Stack and Dependencies

The project is built primarily with Python and utilizes a standard ML and Web development stack.

* **Core Language:** Python 3.x
* **Data Analysis:** `pandas`, `numpy`
* **Machine Learning:** `scikit-learn` (for Random Forest), `pickle` (for model serialization)
* **Web Framework:** `Flask`
* **Web Scraping:** `requests`, `BeautifulSoup` 
* **Development:** Jupyter Notebooks (`.ipynb`)

