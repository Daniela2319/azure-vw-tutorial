# ⏲️ Passo 06 – Configurar Desligamento Automático da Máquina Virtual

## 🎯 Objetivo

Evitar cobranças desnecessárias configurando o desligamento automático da máquina virtual em horários definidos.

---

## 🧭 Etapas

### 1. Acessar a opção de desligamento automático

- No portal do Azure, vá até a **Visão geral** da máquina virtual.
- Na seção **Operações**, clique em **Desligamento automático**.

### 2. Configurar o desligamento

- Marque a opção **Ativado**.
- Defina o **horário desejado** para o desligamento automático.
- Escolha o **fuso horário** correto (por padrão, é UTC).
- Clique em **Salvar** no topo da página para aplicar a configuração.

---

## 📸 Capturas de tela

Para visualizar exemplos reais da interface e entender melhor o processo, consulte a documentação oficial da Microsoft:

- [Desligamento automático de uma VM – Azure Virtual Machines](https://learn.microsoft.com/pt-br/azure/virtual-machines/auto-shutdown-vm)
- Página de configuração de desligamento automático
- Campo de horário e fuso horário selecionado
- Botão “Salvar” após ativação

---

## 📝 Observações

- O desligamento automático não exclui a VM, apenas a desliga para evitar uso contínuo.
- Você pode ligar a VM manualmente a qualquer momento pelo portal.
- Certifique-se de ajustar o fuso horário para sua região (ex: Brasília = UTC−3).
- Ideal para ambientes de teste ou aprendizado, onde a VM não precisa ficar ativa 24h.
