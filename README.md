## Créditos

### Português
Este projeto utiliza o código de "whaticket-installer", criado e mantido por "riservato-xyz".

- **Autor Original:** riservato-xyz
- **Projeto Original:** whaticket-installer
- **Repositório no GitHub:** `https://github.com/riservato-xyz/whaticket-installer`

Este instalador modificado foi projetado para instalar o código fonte do "whaticket-free" a partir do repositório `https://github.com/unkbot/whaticket-free`, ao contrário do "whaticket-installer" original por riservato-xyz, que instala o código fonte de 'canove'.

### English
This project uses code from "whaticket-installer" created and maintained by "riservato-xyz".

- **Original Author:** riservato-xyz
- **Original Project:** whaticket-installer
- **GitHub Repository:** `https://github.com/riservato-xyz/whaticket-installer`

This modified installer is designed to install the source code of "whaticket-free" from the repository `https://github.com/unkbot/whaticket-free`, unlike the original "whaticket-installer" by riservato-xyz that installs the source code from 'canove'.

## Instructions
Interactive CLI tool for installing and updating whaticket

### download & setup

Firstly, you need to download it:


```bash
sudo apt -y update && apt -y upgrade
sudo apt install -y git
git clone https://github.com/pujoni/whaticket_installer.git
```

Now, all you gotta do is making it executable:

```bash
sudo chmod +x ./whaticket_installer/whaticket
```

### usage

After downloading and making it executable, you need to **navigate into** the installer directory and **run the script with sudo**:

```bash
cd ./whaticket_installer
```

```bash
sudo ./whaticket
```
