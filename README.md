# Docker-ansible

These roles install Docker and Docker-compose on your machine.

# How To Run

1. Create a venv `python -m venv venv`
2. Install requirements `pip install -r requirements.txt`
3. active venv `source venv/bin/activate`
4. put machines data in `inventory.ini`
5. run playbook `ansible-playbook -i inventory.ini -v play.yaml`
   Note: if you want to skip checking tasks, run playbook with `ansible-playbook -i inventory.ini -v --tags install play.yaml`

[@dwsclass](https://github.com/dwsclass) dws-ops-003-ansible