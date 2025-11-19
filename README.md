🛒 Urban Grocers – API Test Automation

📌 Project Description Urban Grocers is an e-commerce application focused on selling food products through predefined or customized kits. This project is centered on test automation to validate the correct functioning of the kit creation endpoint, with emphasis on the “name” field.

🧩 Problem Solved The main objective is to ensure that the “name” field meets the established validation criteria, guaranteeing data integrity and system stability against both valid and invalid inputs. This allows early error detection and improves backend quality.

🛠️ Technologies Used Python – Pytest – Requests – Venv – GitHub

▶️ How to Run the Project Clone the repository:
git clone https://github.com/Saracalle1234/qa-project-Urban-Grocers-app-es.git

Create and activate a virtual environment:
python -m venv venv  
source venv/bin/activate  # En Linux/Mac  
venv\Scripts\activate      # En Windows

Install dependencies:
pip install -r requirements.txt

Run the tests:
pytest Create_kit_name_kit_test.py
