# Linux VM no Azure

## 🧩 Descrição do Projeto
Este projeto teve como objetivo criar e configurar uma **Máquina Virtual Linux com GNOME Desktop** na plataforma **Microsoft Azure**, demonstrando o processo de implementação de uma infraestrutura em nuvem e a configuração de acesso remoto seguro.

O projeto envolveu a criação de vários recursos essenciais no Azure, garantindo conectividade, segurança e acessibilidade à máquina virtual.

---

## ⚙️ Tecnologias Utilizadas
- **Microsoft Azure** – Infraestrutura cloud e serviços de computação
- **Linux (Ubuntu com GNOME Desktop)** – Sistema operativo utilizado na VM
- **SSH (Secure Shell)** – Acesso remoto seguro através de chaves públicas/privadas
- **Azure CLI** – Ferramenta de linha de comando para gestão de recursos
- **Remote Desktop Connection (RDP)** – Ligação gráfica à VM
- **Rede Virtual (VNet) e Grupo de Segurança (NSG)** – Estrutura de rede e regras de segurança

---

## 🧠 Objetivos
- Criar uma **máquina virtual Linux** na cloud Azure.  
- Implementar **autenticação SSH** através de **chaves públicas e privadas**.  
- Configurar **IP público**, **interface de rede** e **rede virtual**.  
- Criar e associar um **grupo de segurança de rede (NSG)** com regras específicas.  
- Abrir a **porta 320** para permitir acesso remoto RDP de forma segura.  
- Aceder remotamente à máquina via **Azure CLI** e **Remote Desktop Connection**.

---

## 🏗️ Etapas de Implementação

1. **Criação do Grupo de Recursos**
   - Centralização de todos os componentes do projeto num único grupo para facilitar a gestão e o ciclo de vida dos recursos.

2. **Configuração da Rede Virtual (VNet) e Sub-rede**
   - Criação da rede virtual e sub-rede associada para isolar e organizar a comunicação entre os recursos.

3. **Criação do Endereço IP Público**
   - Geração de um IP público estático para permitir o acesso remoto à VM.

4. **Criação da Interface de Rede (NIC)**
   - Associação da interface à VNet e ao IP público, servindo de ponte entre a máquina virtual e a rede.

5. **Configuração do Grupo de Segurança de Rede (NSG)**
   - Definição das regras de entrada e saída, incluindo a **abertura da porta 320** para o **acesso RDP** via SSH.

6. **Geração de Chaves SSH**
   - Criação das chaves públicas e privadas para autenticação segura.

7. **Criação da Máquina Virtual Linux**
   - Instalação de uma distribuição **Ubuntu** com ambiente gráfico **GNOME Desktop**.

8. **Acesso Remoto**
   - Possibilidade de acesso via **Azure CLI** ou **Remote Desktop Connection**, utilizando as chaves SSH configuradas.

---

## 🖼️ Evidências do Processo
As seguintes imagens ilustram o processo de configuração:

- Criação dos recursos no portal Azure  
- Associação da rede e grupo de segurança  
- Geração de chaves SSH  
- Configuração do acesso remoto  
- Acesso final à VM via GNOME Desktop

> As capturas de ecrã encontram-se na pasta `/Screenshots` deste repositório.

---

## 📘 Conclusão
Este projeto permitiu compreender de forma prática o processo de **criação e gestão de uma máquina virtual Linux no Azure**, abordando conceitos essenciais como redes virtuais, segurança, autenticação SSH e acesso remoto.  

A experiência reforçou a importância de uma **configuração de segurança rigorosa** e do uso de ferramentas como o **Azure CLI** para automação e administração eficiente.

---

## 👨‍💻 Autor
**Hugo Gonçalves**  
Projeto académico/desenvolvido no âmbito de prática em computação na nuvem.  
