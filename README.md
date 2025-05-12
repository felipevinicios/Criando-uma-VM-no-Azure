# Criando-uma-VM-no-Azure
Como criar uma maquina virtual do windows no portal Azure.

## 🚀 Passo a passo:

**Acesse o portal do Azure**  
   👉 [https://portal.azure.com](https://portal.azure.com)  
   Faça login com sua conta Microsoft.

   **Vá em “Máquinas Virtuais”**  
   Menu lateral → clica em **“Criar”** → **“Máquina Virtual”**

   **Configurações básicas**  
   - **Nome da VM**: escolha algo tipo `minha-vm-java`
   - **Região**: escolha uma próxima (ex: `Brazil South`)
   - **Imagem (SO)**: selecione o sistema operacional (ex:  Windows Server)
   - **Tamanho**: escolha algo leve (ex: **B1s**) se for só pra testar

   - **Usuário e autenticação**  
   - Crie um **usuário e senha**, ou use uma **chave SSH** (recomendado no Linux)

   - **Disco e armazenamento**  
   Pode deixar o disco padrão (SSD = mais rápido / HDD = mais barato)

**Rede e acesso**  
   - Ative o **IP público**  
   - Libere a porta **22 (SSH)** se for Linux  
   - Libere a porta **3389 (RDP)** se for Windows

   - **Revisar e criar**  
   Clica em **“Revisar + Criar”**, espera validar, e depois em **“Criar”**
