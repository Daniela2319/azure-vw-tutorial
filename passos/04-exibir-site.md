# 🌍 Passo 04 – Exibir a Página de Boas-Vindas do IIS

## 🎯 Objetivo

Verificar se o servidor web IIS está funcionando corretamente acessando a página padrão via navegador.

---

## 🧭 Etapas

### 1. Obter o endereço IP público da VM

- No portal do Azure, acesse a **Visão geral** da máquina virtual.
- Passe o mouse sobre o **Endereço IP público** e clique em **Copiar para área de transferência**.

### 2. Acessar via navegador

- Abra um navegador web (Edge, Chrome, Firefox, etc.).
- Cole o endereço IP copiado na barra de endereços e pressione Enter.

### 3. Verificar a página

- A página padrão de boas-vindas do IIS deve ser exibida.
- Ela geralmente contém o título **"Internet Information Services (IIS)"** e confirma que o servidor está ativo.

---

## 📸 Capturas de tela

Para visualizar exemplos reais da interface e entender melhor o processo, consulte a documentação oficial da Microsoft:

- [Desligamento automático de uma VM – Azure Virtual Machines](https://learn.microsoft.com/pt-br/azure/virtual-machines/auto-shutdown-vm)
- Página de visão geral da VM com o IP público visível
- Navegador exibindo a página padrão do IIS

---

## 📝 Observações

- Certifique-se de que a porta HTTP (80) esteja liberada nas regras de entrada da VM.
- Se a página não carregar, verifique se o IIS foi instalado corretamente e se a VM está em execução.
- O endereço IP pode mudar se a VM for reiniciada, a menos que um IP estático seja configurado.
