# Ansible-DebianUpdate

This is Ansible Automation to Update Debian Installed Software

# Diagram
```mermaid
graph TD
A[Ansible] --> B(Debian Update Packages)
B --> C(Debian Upgrade Packages)
C --> D(Install common software)
D --> E(FINISH)
```

# Requirement
- Debian Operating System
- Debian Repository

# common software
        - build-essential
        - curl
        - libssl-dev
        - wget
        - nano

# how to install
```mermaid
graph LR
A[Ansible] --> B(edit hosts file)
B --> C(ansible-playbook -i hosts DebianUpdate.yml)
C --> D(FINISH)
```

# Thanks
contributor : t3mp30r3k@2022 (kangoprek.com) - rusdianto
