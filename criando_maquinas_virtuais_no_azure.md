# 🖥️ Como Criar uma Máquina Virtual no Microsoft Azure (Passo a Passo)

Se você nunca criou uma máquina virtual (VM) antes, não se preocupe! Este guia vai te mostrar o processo de forma clara e simples, usando o **portal do Azure**, sem necessidade de comandos ou experiência prévia.

---

## ✅ O que é uma Máquina Virtual (VM)?

Uma **máquina virtual** é como um "computador dentro de outro computador", rodando na nuvem. Com ela, você pode:
- Instalar sistemas operacionais (como Windows ou Linux)
- Rodar aplicações
- Testar ambientes
- Simular servidores

---

## 📝 Pré-requisitos

- Uma **conta na Microsoft** (pode ser @hotmail, @outlook, etc)
- Uma conta no **Azure** (você pode criar uma em: https://azure.microsoft.com)
- Um **cartão de crédito** (somente para verificação, no plano gratuito você não será cobrado)

---

## 🚀 Passo a Passo: Criando uma VM no Portal do Azure

### 1. Acesse o Portal do Azure
👉 Vá para: https://portal.azure.com  
Faça login com sua conta Microsoft.

---

### 2. Pesquise por "Máquinas Virtuais"
Na barra de pesquisa do topo, digite **"Máquinas Virtuais"** ou **"Virtual Machines"** e clique na opção correspondente.

---

### 3. Clique em **"Criar"** > **"Máquina Virtual"**

Você verá um formulário com várias etapas. Preencha com atenção:

---

### 4. **Aba: Básico**

| Campo | O que preencher |
|-------|------------------|
| **Assinatura** | Use a padrão (geralmente "Pay-As-You-Go") |
| **Grupo de Recursos** | Crie um novo ou escolha um existente (ex: `meu-grupo-recursos`) |
| **Nome da VM** | Dê um nome para sua VM (ex: `minha-vm-windows`) |
| **Região** | Escolha a região mais próxima de você |
| **Imagem** | Escolha o sistema operacional (ex: Windows 11, Ubuntu 20.04, etc) |
| **Tamanho** | Escolha um tamanho gratuito ou básico (ex: `B1s` se estiver no plano gratuito) |
| **Usuário e Senha** | Defina um nome de usuário e uma senha para acessar a VM |

---

### 5. **Aba: Disco**
Você pode deixar as opções padrão. Se quiser mais desempenho, pode escolher disco SSD.

---

### 6. **Aba: Rede**
A configuração padrão já cria uma rede e IP público para você.

---

### 7. **Revisar + Criar**
Clique em **"Revisar + Criar"** para ver um resumo das configurações.

Se estiver tudo certo, clique em **"Criar"**.

---

## ⏳ Aguarde o Azure Criar sua VM

Esse processo pode levar **1 a 3 minutos**.

Quando finalizar, você verá um botão **"Ir para o recurso"**. Clique nele.

---

## 🔗 Acessando sua VM

### Se for Windows:
1. Clique em **"Conectar"** > **"RDP"**
2. Baixe o arquivo `.rdp` e abra no seu computador
3. Digite o **usuário e senha** que você definiu

### Se for Linux:
1. Clique em **"Conectar"** > **"SSH"**
2. Use o terminal do seu sistema para se conectar via SSH com o comando fornecido

---

## 🧼 Como parar ou excluir sua VM (para não gerar custos)

- Para **parar** (sem excluir): clique em **"Parar"** na barra superior da VM.
- Para **excluir**: clique em **"Excluir"** na barra superior da VM ou exclua o grupo de recursos.

---

## 🏁 Pronto!

Você criou sua primeira máquina virtual no Azure! Agora pode explorar, instalar softwares, testar scripts, ou usar como servidor pessoal.

---

## 📚 Dicas Finais

- VMs no plano gratuito só funcionam com alguns tamanhos (como `B1s`).
- Sempre **pare ou exclua** VMs que não estiver usando para evitar cobranças.
- Explore os **tutoriais e laboratórios gratuitos** que a Microsoft oferece na [documentação oficial](https://learn.microsoft.com/azure/virtual-machines/).

