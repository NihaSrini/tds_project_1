# tds_project_1
# 🧠 TDS Project 1 — Task Receiver API

A **FastAPI-based REST service** deployed on **Hugging Face Spaces** for the TDS Course evaluation.  
This service exposes a `/ready` endpoint that accepts POST requests with JSON payloads from the instructor’s evaluation system.

---

## 📋 Project Summary

This API acts as a **task receiver**:
- Instructors send POST requests with a JSON body.
- The app validates the secret and adds the received task to a processing queue (simulated here by printing).
- Returns HTTP 200 with a confirmation message.

---

## 🌐 Public API Endpoint

**Base URL:**  
👉 [`https://nihasrini-tds-project-1.hf.space`](https://nihasrini-tds-project-1.hf.space)

**Endpoint:**  
`POST /ready`

---

## 🔐 Secret Authentication

Your secret key : IITM_22f1000020

```bashSTUDENT_SECRET="YOUR_SECRET_HERE"

