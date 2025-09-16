
# CV Web App (Django)

  

This is a Django-based project that displays my CV at [http://127.0.0.1:8000/resume](http://127.0.0.1:8000/resume).
  
---
  
## Prerequisites
  
Before running the project, make sure you have the following installed:

1.  **Python 3.8+**
- Check if Python is installed:
```bash
python3 --version
```
- If not installed, download from [Python.org](https://www.python.org/downloads/) or install via package manager:
- Ubuntu/Debian:
```bash
sudo apt update
sudo apt install python3 python3-pip python3-venv
```
- macOS (Homebrew):
```bash
brew install python
```
2.  **pip** (Python package manager)
- Check if pip is installed:
```bash
pip3 --version
```
- If missing, install:
```bash
python3 -m ensurepip --upgrade
```
3.  **Django**
- Check if Django is installed:
```bash
python3 -m django --version
```
- If not, install using pip:
```bash
pip3 install django
```
---
  
## Setup & Run
  
1.  **Clone the repository**
```bash
git clone https://github.com/gpr2033/django-resume.git
cd django-resume
```
2.  **Start the development server**
```bash
python3 manage.py runserver
```
3. **Open the resume app in your browser at `http://127.0.0.1:8000/resume`**
---

## Notes
  
If you encounter port conflicts, run the server on a different port:
```bash
python3  manage.py  runserver  8080
```
Then open `http://127.0.0.1:8080/resume`
