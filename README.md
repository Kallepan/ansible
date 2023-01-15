# How to install
```bash
python3 -m virtualenv venv
source venv bin activate
pip install -r requirements.txt
```
- Now Ansible should be available
- To run a playbook run:
```bash
- anisble-playbook test.yml -K --ask-vault-pass
```