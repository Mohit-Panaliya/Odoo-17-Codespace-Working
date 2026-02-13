# 🚀 Odoo 17 Community Edition: Startup Guide

This guide assumes you have the three master scripts (`setup_env.sh`, `install_deps.sh`, and `run.sh`) saved in your root directory.

## 📂 Preparation

Before running the installation, ensure your scripts have the correct execution permissions.

* Open your terminal and run:
`chmod +x *.sh`

---

## 🛠️ Step 1: Infrastructure Initialization

This step installs the PostgreSQL server, system-level headers, and the Odoo source code.

* **Command:** `./setup_env.sh`
* **Wait for:** The message `✅ Infrastructure Ready!`

---

## 🐍 Step 2: Python Environment & Dependencies

This step sets up the virtual environment and installs all required Python packages.

1. **Activate the environment:** `source odoo-venv/bin/activate`
2. **Install requirements:** `./install_deps.sh`

* **Wait for:** The message `🚀 Python Environment Ready!`

---

## 🚀 Step 3: Launching Odoo

This step starts the database service and the Odoo web server.

* **Command:** `./run.sh`
* **Wait for:** The terminal to show the URL and the message `HTTP service (werkzeug) running on localhost:8069`.

---

## 🌐 Step 4: Browser Configuration

1. Click the **"Open in Browser"** button provided by GitHub Codespaces.
2. You will be directed to the **Odoo Database Manager**.
3. Use the following credentials to create your first database:
* **Master Password:** `admin`
* **Database Name:** `odoo_dev` (or your choice)
* **Email/Login:** `admin`
* **Password:** `admin`


4. Click **Create Database** and wait for the Odoo Apps dashboard to appear.

---
