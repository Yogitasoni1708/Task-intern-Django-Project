# Task-intern-Django-Project
# 📚 Library Management System (Django)

This is a Django-based Library Management System that allows users to manage authors, books, and borrow records, with features like pagination and Excel export.

---

## 🛠 How to Run This Project

Follow the steps below to set up and run this project on your local machine.

---

### ⚙️ Step-by-Step Setup

```bash
# 1. Clone the repository
git clone <your_repo_url>
cd Library_management

# 2. Create a virtual environment
# For Windows
python -m venv venv
venv\Scripts\activate

# For macOS/Linux
python3 -m venv venv
source venv/bin/activate

# 3. Install required packages
pip install -r requirements.txt

# If requirements.txt is not available, install manually:
pip install django openpyxl

# 4. Make and apply database migrations
python manage.py makemigrations
python manage.py migrate

# 5. Run the development server
python manage.py runserver
