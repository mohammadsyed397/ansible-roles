<h1 align="center">🤖 Ansible Roles for Roboshop Microservices</h1>

<p align="center">
  🚀 Automate the deployment of Roboshop microservices using Ansible roles.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Automation-Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Author-Mohammad%20Syed-blue?style=for-the-badge"/>
</p>

---

## 📦 Project Structure

```bash
ansible-roles/
├── inventory.ini           # Inventory file (static or dynamic)
├── playbook.yaml           # Main playbook
└── roles/
    ├── frontend/
    │   ├── tasks/
    │   ├── handlers/
    │   ├── templates/
    │   └── vars/
    ├── catalogue/
    ├── user/
    └── payment/
