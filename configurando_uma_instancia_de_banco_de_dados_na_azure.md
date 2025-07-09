# 🗄️ Como Criar um Banco de Dados na Nuvem com o Microsoft Azure (Passo a Passo)

Se você está começando agora no Azure, este guia vai te mostrar como **criar um banco de dados na nuvem**, sem complicações. Vamos usar o **Azure SQL Database**, uma opção prática e gerenciada para armazenar dados relacionais (como num SQL Server).

---

## ✅ O que é o Azure SQL Database?

O **Azure SQL Database** é um serviço de banco de dados na nuvem oferecido pela Microsoft. Ele roda o mesmo mecanismo do SQL Server, mas **você não precisa instalar nada** — a Microsoft cuida da manutenção, backup, atualizações e infraestrutura.

Você só se preocupa com os **dados e a conexão com o banco**.

---

## 📝 Pré-requisitos

- Uma **conta no Azure** (https://azure.microsoft.com)
- Um **cartão de crédito** (para verificação, não será cobrado no plano gratuito)
- Acesso ao **portal do Azure**: https://portal.azure.com

---

## 🚀 Passo a Passo: Criando um Banco de Dados no Azure

### 1. Acesse o Portal do Azure

Vá para: [https://portal.azure.com](https://portal.azure.com)  
Faça login com sua conta Microsoft.

---

### 2. Procure por **"SQL Database"**

Na barra de busca superior, digite **"SQL Database"** e clique no serviço correspondente.

---

### 3. Clique em **"Criar"**

Você verá um formulário com várias etapas. Vamos preencher os principais campos:

---

### 4. **Aba: Básico**

| Campo                  | O que preencher                                            |
|------------------------|-------------------------------------------------------------|
| **Assinatura**         | Use a padrão (geralmente "Pay-As-You-Go")                  |
| **Grupo de Recursos**  | Crie um novo ou escolha um já existente                    |
| **Nome do banco**      | Dê um nome para seu banco (ex: `meuBancoTeste`)            |
| **Servidor**           | Clique em **"Criar novo"**                                 |
|                        | - Dê um nome ao servidor (ex: `servidor-banco-sql`)        |
|                        | - Escolha uma região (ex: Brazil South)                    |
|                        | - Defina um **login de administrador** e **senha forte**   |
| **Camada de preço**    | Clique em **"Configurar banco de dados"** e escolha:       |
|                        | - Se estiver testando, use **Basic** ou **Free Tier**      |

---

### 5. **Aba: Rede**

- Por padrão, o acesso ao banco é restrito.
- Você pode **permitir acesso à sua máquina local** clicando em **"Adicionar meu IP atual"**.
- Deixe a opção de **ponto de extremidade público** ativada (se for um teste simples).

---

### 6. **Aba: Segurança (opcional)**

- Pode deixar as opções padrão.
- O Azure já aplica criptografia em repouso automaticamente.

---

### 7. Clique em **"Revisar + Criar"**

Revise todas as configurações e clique em **"Criar"**.

A criação pode levar **1 a 2 minutos**.

---

## 🔗 Como se conectar ao banco de dados

Depois de criado:

1. Vá até o recurso do **SQL Database**
2. Copie a **string de conexão**
3. Use essa string no seu aplicativo ou conecte-se via:

### ▶️ SQL Server Management Studio (SSMS) ou Azure Data Studio:

- Servidor: `nomedoservidor.database.windows.net`
- Login: o que você criou na etapa anterior
- Senha: a que você definiu
- Banco: o nome do banco que você escolheu

---

## ⚠️ Dicas Importantes

- **Atenção à camada de preço:** escolha a mais básica para testes.
- **Segurança:** só permita IPs confiáveis.
- **Backups e replicação** são gerenciados automaticamente pelo Azure.
- Você pode **criar tabelas e inserir dados** como em um SQL Server tradicional, via SSMS, Azure Data Studio ou comandos SQL no próprio portal.

---

## ✅ Conclusão

Agora você tem um **banco de dados relacional funcional na nuvem**, sem precisar instalar nada! Você pode usá-lo para conectar aplicações web, sistemas internos ou apenas para aprendizado.

> Quer testar agora mesmo? Acesse o banco via SSMS, crie uma tabela e insira alguns dados!

---

## 📚 Recursos adicionais

- [Documentação oficial - Azure SQL Database](https://learn.microsoft.com/azure/azure-sql/database/)
- [Como usar o Azure Data Studio](https://learn.microsoft.com/sql/azure-data-studio/)
