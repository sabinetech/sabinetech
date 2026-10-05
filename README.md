# 🎗️ Breast Cancer Assistant (MLH Fellowship Code Sample)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/Python-3.11%2B-blue)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/Backend-FastAPI-009688)](https://fastapi.tiangolo.com/)
[![React](https://img.shields.io/badge/Frontend-React-61DAFB)](https://react.dev/)
[![Code Style: Black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

> **Live Demo:** [https://breastcancerssistant.example.com](https://breastcancerssistant.example.com) *(Optional live deployment link)*

A full-stack, machine learning-assisted diagnostic application that evaluates clinical features to assist healthcare professionals in early breast cancer risk assessment.

---

## 📌 Problem & Motivation

Early detection significantly increases successful treatment outcomes for breast cancer. However, diagnostic tools often lack clean, scalable developer APIs and intuitive web interfaces. 

I built this project to bridge machine learning model deployment with clean backend API design and responsive frontend interfaces, demonstrating how clinical classification models can be exposed safely over production REST endpoints.

---

## ✨ Key Features

- **Diagnostic API:** Exposes clean REST endpoints for model inference using FastAPI.
- **Interactive UI:** A React interface allowing medical staff to input feature vectors and receive instant risk probabilities.
- **Model Pipeline:** Built with `scikit-learn`, featuring feature normalization and automated model loading.
- **Robust Error Handling:** Validates incoming payloads using Pydantic schemas to prevent malformed data inputs.
- **Automated Testing:** Suite of unit and integration tests for API endpoints and data processing modules.

---

## 🧰 Tech Stack & Architecture

- **Backend:** Python 3.11, FastAPI, Pydantic, Uvicorn
- **Frontend:** React.js, Tailwind CSS
- **Machine Learning:** Scikit-Learn, Pandas, NumPy
- **DevOps & Testing:** Docker, Pytest, GitHub Actions (CI)
