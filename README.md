<div align="center">
  <h1>Mowe Client</h1>
  <p><b>Client de Minecraft 1.8.9 focado em performance, cosméticos dinâmicos e segurança.</b></p>

  [![Última Versão](https://img.shields.io/github/v/release/gustamiguel/MoweLauncher?color=0078D7&label=Download&style=flat-square)](https://github.com/gustamiguel/MoweLauncher/releases/latest)
  [![Plataforma](https://img.shields.io/badge/Plataformas-Windows%20%7C%20Linux-lightgrey?style=flat-square)]()
</div>

---

## Sobre o Projeto
O Mowe Client é um ecossistema completo (Launcher + Modpack) desenvolvido para modernizar a experiência do Minecraft 1.8.9. O foco do projeto é manter a estabilidade de quadros (FPS) utilizando renderização otimizada em OpenGL, aliada a uma infraestrutura de backend segura para autenticação e cosméticos.

## Funcionalidades
* **Ecossistema de Cosméticos:** Sistema próprio de renderização de modelos 3D (chapéus, asas, capas) e um editor de capas in-game (desenhe sua própria textura), com sincronização em tempo real entre os jogadores.
* **Launcher Multiplataforma:** Construído em Electron, oferecendo gerenciamento de memória RAM, autologin e interface responsiva para Windows e distribuições Linux.
* **Autenticação Segura:** Login integrado com a Microsoft (Original) e Offline, protegido por uma arquitetura serverless via Cloudflare Workers e Firebase.
* **Atualizações OTA (Over-The-Air):** Sistema de Bootstrapper silencioso. O jogo e o Launcher recebem atualizações contínuas de forma transparente ao usuário.
* **Otimização de Performance:** Render loop refatorado para reduzir alocações de memória (Garbage Collection) e vazamentos de estado do OpenGL, garantindo fluidez em combates.

---

## Instalação

O Client gerencia as dependências do Java e do Minecraft de forma autônoma. Basta escolher o instalador para o seu sistema operacional:

### Windows
Faça o download do executável. O instalador configurará o atalho automaticamente de forma silenciosa.
> [**Baixar Setup (.exe)**](https://github.com/gustamiguel/MoweLauncher/releases/latest)

### Linux
Disponível em formato portátil. Lembre-se de conceder permissão de execução (`chmod +x`) antes de iniciar.
> [**Baixar Portátil (.AppImage)**](https://github.com/gustamiguel/MoweLauncher/releases/latest)

---

<div align="center">
  <sub>Desenvolvido por Gustavo Miguel</sub>
</div>
