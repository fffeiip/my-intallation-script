# My Installation Scripts

## Instalação do Ansible

Para instalar o Ansible:
```bash
sudo apt update  
sudo apt install ansible -y
ansible --version
```

## Como executar

Execute o playbook com:

ansible-playbook playbooks/*.yml --ask-become-pass
> Para logs mais detalhados: usar o -vv
```bash
ansible-playbook playbooks/install_default_tools.yml --ask-become-pass -vv
```

## Programas instalados

- Docker
- VS Code  
- Spotify 
- Telegram 
- GitKraken 
- Remmina  
- GIMP  
- Zsh + Oh My Zsh  
- Repositório Flathub para Flatpak