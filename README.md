# 🧾 HSN Code Validation Agent (Using Google ADK Framework)

## 📌 Project Overview

This project implements an intelligent agent that validates **Harmonized System Nomenclature (HSN)** codes using a conceptual structure based on the **Google Agent Developer Kit (ADK)** framework. HSN codes are used worldwide to classify traded goods and vary from 2 to 8 digits. The agent validates these codes based on a provided master Excel dataset and returns informative responses such as valid descriptions, format errors, or missing entries.

---

## 🧠 Features

- ✅ Validates numeric HSN codes (2, 4, 6, or 8 digits).
- 🔍 Checks if the code exists in the master dataset.
- 🧬 Optional parent hierarchy validation (e.g., for `01011010`, checks `010110`, `0101`, and `01`).
- 📥 Accepts one or multiple codes.
- 📤 Returns friendly and structured validation responses.
- ⚠️ Detects and handles format errors and unknown codes.

---

## 🗂️ Folder Structure

