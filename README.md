# 🚀 Desafio de Projeto - Máquinas Virtuais no Azure

Este repositório contém a documentação do desafio de laboratório da **DIO** sobre **Máquinas Virtuais no Azure**.  
O objetivo foi aplicar os conceitos aprendidos na prática e consolidar o conhecimento.

---

## 📌 Objetivos de Aprendizagem
- Criar e configurar uma máquina virtual no **Microsoft Azure**.
- Documentar os processos técnicos de forma clara e organizada.
- Utilizar o **GitHub** como ferramenta de versionamento e compartilhamento.

---

## 🛠️ Passo a Passo Realizado

### 1. Criação da Máquina Virtual
- Acesse o [Portal do Azure](https://portal.azure.com).
- Navegue até **Máquinas Virtuais** → **Criar**.
- Selecione:
  - **Sistema Operacional**: Windows Server 2022 (exemplo).
  - **Tamanho da VM**: Standard_B1s (baixo custo para laboratório).
  - **Usuário/Admin**: configurado durante o setup.
- Configurar regras de rede permitindo acesso **RDP (porta 3389)**.

### 2. Acesso à VM
- Baixar o arquivo `.rdp` pelo portal.
- Conectar usando as credenciais definidas.
- Validar que o ambiente está funcionando.

### 3. Testes e Configurações
- Verificar conectividade com `ping`.
- Instalar updates básicos do Windows.
- Capturar prints de cada etapa.

---

## 📂 Estrutura do Repositório
dio-lab-azure-vm
|- 📂 images
|-- criação-vm.png
|-- acesso-rdp.png
|-- painel-vm.png
- README.md
