# 📘 Passo 01 – Criar uma Máquina Virtual no Azure

### 🎯 Objetivo

Criar uma máquina virtual (VM) com Windows Server 2022 no portal do Azure, configurando os detalhes básicos da instância.

# 🧭 Etapas – Criar uma Máquina Virtual no Azure

## 1. Acessar o serviço de máquinas virtuais

- No portal do Azure, digite **Máquinas virtuais** na barra de pesquisa.
- Clique em **Criar > Máquina virtual do Azure**.

## 2. Preencher os detalhes da instância

- **Nome da VM**: `myVM`
- **Região**: selecione a mais próxima ou recomendada.
- **Imagem**: `Windows Server 2022 Datacenter: Azure Edition - x64 Gen 2`
- **Tamanho**: mantenha o padrão sugerido.
- **Zonas de disponibilidade**: se disponível, escolha conforme necessidade.

## 3. Configurar a conta de administrador

- **Nome de usuário**: `azureuser` (ou outro de sua preferência)
- **Senha**: mínimo de 12 caracteres, com letras maiúsculas, minúsculas, números e símbolos.

## 4. Definir regras de porta de entrada

- Selecione **Permitir portas selecionadas**
- Escolha:
  - **RDP (3389)** – para acesso remoto
  - **HTTP (80)** – para acesso via navegador

## 5. Finalizar a criação

- Clique em **Examinar + criar**
- Após a validação, clique em **Criar**
- Aguarde a implantação e selecione **Ir para o recurso**

---

## 📸 Capturas de tela

Para visualizar exemplos reais da interface e entender melhor o processo, consulte a documentação oficial da Microsoft:

- [Desligamento automático de uma VM – Azure Virtual Machines](https://learn.microsoft.com/pt-br/azure/virtual-machines/auto-shutdown-vm)
- Tela de criação da VM com os campos preenchidos
- Seção de regras de porta de entrada
- Botão “Examinar + criar” e “Criar”

---

## 📝 Observações

- A criação pode levar alguns minutos.
- Certifique-se de que a região e o tamanho da VM estejam dentro do orçamento disponível.
- A opção de zonas de disponibilidade pode variar conforme a região escolhida.
