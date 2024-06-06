# Ansible GCP

## Description
This project contains an implementation of an Ansible playbook to interact with Google Cloud Platform (GCP) services.

## Prerequisites
- Ansible: 2.17.0
- Python: 3.10

## How to run
1. Clone the repository
2. Copy and paste your service account key file in the root directory of the project (`sa.json`)
2. Install required python packages
```
python3.10 -m pip install requests google-auth
```
3. Create a virtual environment
```bash
python3 -m venv venv
source venv/bin/activate
```
3. Install ansible
```bash
pip install ansible
```
4. Install Ansible Google Cloud Collection
```bash
ansible-galaxy collection install google.cloud
```
5. Run the playbook
```bash
make run
```
6. Have fun!
