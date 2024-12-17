How to Run the Project
Prerequisites:
Python (>= 3.8) installed on your system.
Ansible installed in a virtual environment.
Git installed for version control.

Steps to Run:
Clone the repository:

bash
Copy code
git clone <repository-url>
cd <project-folder>


Set up a virtual environment:

bash
Copy code
python -m venv myenv
source myenv/bin/activate


Install dependencies:

bash
Copy code
pip install -r requirements.txt


Run Ansible playbooks:

bash
Copy code
ansible-playbook playbook1.yml
ansible-playbook playbook2.yml
ansible-playbook playbook3.yml


Verify CI/CD pipeline:

Push changes to the repository and check GitHub Actions for pipeline execution.

