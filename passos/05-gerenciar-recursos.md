# 🧹 Passo 05 – Gerenciar e Limpar Recursos da Máquina Virtual

## 🎯 Objetivo

Excluir a máquina virtual e seus recursos associados quando não forem mais necessários, ou configurar desligamento automático para evitar cobranças desnecessárias.

---

## 🧭 Etapas

### 🔻 Excluir recursos manualmente

#### 1. Acessar o grupo de recursos

- No portal do Azure, vá até a **Visão geral** da máquina virtual.
- Clique no link do **Grupo de recursos** associado à VM.

#### 2. Excluir o grupo de recursos

- Na página do grupo de recursos, clique em **Excluir grupo de recursos** no topo.
- Digite o nome do grupo para confirmar.
- Clique em **Excluir** para remover todos os recursos vinculados à VM.

---

### ⏲️ Configurar desligamento automático

#### 1. Acessar a opção de desligamento

- Na página da VM, vá até a seção **Operações**.
- Clique em **Desligamento automático**.

#### 2. Configurar horário

- Marque a opção **Ativado**.
- Defina o horário desejado para o desligamento automático.
- Selecione o **fuso horário** correto (padrão é UTC).
- Clique em **Salvar** para aplicar a configuração.

---

## 📸 Capturas de tela

Para visualizar exemplos reais da interface e entender melhor o processo, consulte a documentação oficial da Microsoft:

- [Desligamento automático de uma VM – Azure Virtual Machines](https://learn.microsoft.com/pt-br/azure/virtual-machines/auto-shutdown-vm)

Esse guia mostra:

- A página de configuração de desligamento automático
- Como definir o horário e o fuso horário
- Onde clicar para salvar a configuração

---

## 📝 Observações

- A exclusão do grupo de recursos remove a VM, disco, rede e outros componentes associados.
- O desligamento automático ajuda a evitar cobranças por uso contínuo da VM.
- Verifique se há dados importantes antes de excluir os recursos.
