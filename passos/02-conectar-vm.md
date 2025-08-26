# 🔗 Passo 02 – Conectar-se à Máquina Virtual via RDP

## 🎯 Objetivo

Estabelecer uma conexão remota com a máquina virtual criada no Azure utilizando o protocolo RDP (Remote Desktop Protocol).

---

## 🧭 Etapas

### 1. Acessar a página da VM

- No portal do Azure, vá até a **Visão geral** da máquina virtual.
- Clique em **Conectar > RDP**.

### 2. Configurar a conexão

- Na guia **Conectar-se ao RDP**, mantenha as opções padrão:
  - **Endereço IP público**
  - **Porta 3389**
- Clique em **Baixar arquivo RDP**.

### 3. Iniciar a conexão

- Abra o arquivo `.rdp` baixado.
- Clique em **Conectar** quando solicitado.

### 4. Autenticar com credenciais

- Na janela **Segurança do Windows**, clique em **Mais opções**.
- Selecione **Usar uma conta diferente**.
- Digite:
  - **Nome de usuário**: `localhost\nome_de_usuário`
  - **Senha**: a mesma definida na criação da VM
- Clique em **OK**.

### 5. Confirmar certificado

- Pode aparecer um aviso de certificado.
- Clique em **Sim** ou **Continuar** para prosseguir com a conexão.

---

## 📸 Capturas de tela

Para visualizar exemplos reais da interface e entender melhor o processo, consulte a documentação oficial da Microsoft:

- [Desligamento automático de uma VM – Azure Virtual Machines](https://learn.microsoft.com/pt-br/azure/virtual-machines/auto-shutdown-vm)
- Botão **Conectar > RDP** na visão geral da VM
- Tela de download do arquivo RDP
- Janela de login com opção de conta diferente
- Aviso de certificado

---

## 📝 Observações

- Certifique-se de que as portas RDP (3389) estejam liberadas nas regras de entrada.
- Em sistemas macOS, é necessário utilizar um cliente RDP compatível, como o [Microsoft Remote Desktop](https://apps.apple.com/br/app/microsoft-remote-desktop/id1295203466).
- A conexão pode demorar alguns segundos dependendo da rede.
