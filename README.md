# 🛡️ Nivelamento em Cybersecurity 

<p align="center">
  <img src="https://jsdelivr.net" alt="Docker Logo" width="120"/>
</p>


Neste projeto, realizei a configuração completa do meu ambiente de desenvolvimento local, estruturado especificamente para estudos e práticas de segurança da informação (Cybersec).

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

* **VS Code** – Editor de código principal com extensões personalizadas.
* **Git & GitHub** – Controle de versão e hospedagem do repositório para o portfólio.
* **WSL2 (Ubuntu)** – Subsistema Windows para Linux para execução de ferramentas de segurança nativas.
* **Docker Engine** – Plataforma de conteinerização para isolamento de laboratórios e ferramentas de teste.

---

## 🚀 Práticas Realizadas neste Laboratório

1. [x] Instalação e provisionamento do **WSL2 com Ubuntu 24.04 LTS**.
2. [x] Recuperação e gerenciamento de credenciais via terminal Linux (Root).
3. [x] Integração do **Git Bash** como terminal integrado padrão no VS Code.
4. [x] Vinculação de chaves e identificação global do Git.
5. [x] Instalação do **Docker Engine** via repositório oficial com chaves GPG binárias.
6. [x] Configuração de pós-instalação para execução do Docker sem necessidade de `sudo`.

---

## 📑 Guia Rápido de Comandos Docker

* `sudo service docker start` — Inicializa o motor do Docker no WSL2.
* `docker ps` — Lista os contêineres ativos.
* `docker run hello-world` — Executa o contêiner de teste oficial.
