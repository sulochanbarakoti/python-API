<div align="center">
  <h1>✅ Task Manager API</h1>
  <p><i>A secure, searchable, and professional RESTful API built with Django & DRF</i></p>

  <img src="https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Django-5.0-green?style=for-the-badge&logo=django" alt="Django">
  <img src="https://img.shields.io/badge/DRF-REST-red?style=for-the-badge&logo=django" alt="DRF">
</div>

<hr />

## 🌟 Overview
This project is a full-featured backend for a Task Management application. It provides a robust API that allows users to manage their to-do lists with built-in security and documentation.

### 🚀 Key Features
<ul>
  <li><b>🔒 User Isolation:</b> Users can only view, edit, and delete their own tasks.</li>
  <li><b>🔍 Advanced Search:</b> Search tasks by title or filter by completion status.</li>
  <li><b>📖 Interactive Docs:</b> Full Swagger/OpenAPI documentation at <code>/api/docs/swagger/</code>.</li>
  <li><b>🛠️ Professional Stack:</b> Includes CORS headers, Filtering backends, and Schema generation.</li>
</ul>

---

## 🛠️ Development Log
<details>
<summary><b>Click to see the step-by-step build process</b></summary>
<br>
<ol>
  <li><b>Setup:</b> Initialized environment and installed DRF, <code>django-filter</code>, and <code>drf-spectacular</code>.</li>
  <li><b>Models:</b> Created <code>Task</code> model with a Foreign Key relationship to the User.</li>
  <li><b>Logic:</b> Implemented <code>ModelViewSet</code> with custom <code>get_queryset</code> for security.</li>
  <li><b>Docs:</b> Wired up Swagger UI for live API testing.</li>
  <li><b>CORS:</b> Configured Cross-Origin Resource Sharing for frontend integration.</li>
</ol>
</details>

---

## 💻 Installation & Setup

1. **Clone & Enter Folder**
   ```bash
   git clone <your-repo-url>
   cd task_api


