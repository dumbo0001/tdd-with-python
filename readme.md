# Getting Started

1. Create virtual environment. Run: `<Path to Python 3 executable' -m venv .\virtenv`.
2. Install requirements. Run: `.\virtenv\Scripts\pip.exe install -r .\requirements.txt`.
3. Start server: `.\virtenv\Scripts\python.exe .\superlists\manage.py runserver`.
4. Run test: `.\virtenv\Scripts\python.exe .\superlists\functional_tests.py`.

## Generate requirements file
Run: `.\virtenv\Scripts\pip.exe freeze > .\requirements.txt`.