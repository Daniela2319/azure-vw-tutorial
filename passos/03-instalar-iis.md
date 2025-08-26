# 🌐 Passo 03 – Instalar o Servidor Web IIS

## 🎯 Objetivo

Instalar o servidor web IIS (Internet Information Services) na máquina virtual para habilitar a exibição de páginas web.

---

## 🧭 Etapas

### 1. Acessar a VM via RDP

- Conecte-se à máquina virtual utilizando o arquivo `.rdp` baixado anteriormente.
- Faça login com as credenciais definidas durante a criação da VM.

### 2. Abrir o PowerShell

- Após o login, clique com o botão direito no menu Iniciar.
- Selecione **Windows PowerShell (Admin)** para abrir com privilégios administrativos.

### 3. Executar o comando de instalação

- No PowerShell, digite o seguinte comando e pressione Enter:

```powershell
Install-WindowsFeature -name Web-Server -IncludeManagementTools
```
