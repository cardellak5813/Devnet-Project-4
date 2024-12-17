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
  ansible-playbook 01_verify_connectivity.yml
  ansible-playbook 02_basic_config.yml
  ansible-playbook 03_vlan_config.yml
  ansible-playbook 04_backup_config.yml


Verify CI/CD pipeline:

Push changes to the repository and check GitHub Actions for pipeline execution.

