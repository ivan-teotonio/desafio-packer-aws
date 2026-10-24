# Desafio de Infraestrutura como Código (IaC): Packer + Ansible na AWS

Este projeto demonstra a aplicação prática dos conceitos de **Infraestrutura como Código (IaC)** e **Infraestrutura Imutável**. Utilizando o **HashiCorp Packer** integrado ao **Ansible**, automatizamos o processo de construção de uma imagem de máquina virtual personalizada (**AMI**) na **Amazon Web Services (AWS)** com o servidor web **Apache** pré-configurado.

---

##  Tecnologias Utilizadas

* **HashiCorp Packer:** Automação do build e provisionamento da imagem de VM (AMI).
* **Ansible:** Automação do gerenciamento de configuração (instalação e configuração do Apache).
* **AWS (Amazon Web Services):** Provedor de nuvem utilizado para armazenar a AMI e executar a instância EC2.
* **Ubuntu Linux (WSL2):** Ambiente local de execução dos scripts de automação.

---

##  Estrutura do Repositório

```text
.
├── desafio.pkr.hcl   # Arquivo de configuração do HashiCorp Packer (HCL2)
├── apache.yml        # Playbook Ansible para instalação e configuração do Apache
└── README.md         # Documentação e evidências do projeto