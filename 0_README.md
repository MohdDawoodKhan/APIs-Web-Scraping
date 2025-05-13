# 📡 Review of Accessing APIs

## ✅ Objectives

By the end of this lab, you will be able to:

- Understand the basics of HTTP and API communication.
- Analyze HTTP GET and POST requests.
- Extract data from JSON responses using Python's `requests` library.

---

## 🧪 Key Concepts Covered

### 🔹 HTTP GET Request

- Sends data via URL query parameters.
- Response data can be accessed using:

  ```python
  r.json()['args']  # e.g., {'ID': '123', 'name': 'Joseph'}

