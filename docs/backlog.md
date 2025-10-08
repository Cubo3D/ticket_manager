# Backlog do Produto (Sistema de Vendas de Ingressos)

O foco do MVP (Mínimo Produto Viável) é garantir a **Segurança, a Criação de Eventos, a Compra/Pagamento e a Validação na Entrada**.

---

| Rank | User Story (US) | Prioridade |
| :--- | :--- | :--- |
| **1** | US-AUTH-001: Como Usuário, quero me **cadastrar** (email/senha) e **fazer login** no sistema para acessar a área de compra. | **MVP/Essencial** |
| **2** | US-ADM-001: Como Administrador, quero **fazer login** em uma página separada e segura, com **autenticação multifator (MFA)**, para gerenciar eventos e vendas. | **MVP/Essencial** |
| **3** | US-EVENT-001: Como Administrador, quero **adicionar um novo Evento** definindo nome, descrição, imagem/arte, **data do evento** e o **Lote 1** de ingressos (quantidade e preço). | **MVP/Essencial** |
| **4** | US-VENDAS-001: Como Usuário, quero **visualizar a lista de Eventos ativos**, com imagem, data e preço do lote atual, para escolher onde comprar. | **MVP/Essencial** |
| **5** | US-COMPRA-001: Como Usuário, quero **escolher a quantidade** de ingressos e ser direcionado para uma página de pagamento (checkout). | **MVP/Essencial** |
| **6** | US-COMPRA-002: Como Usuário, quero que o sistema **gere um QR Code dinâmico** via API externa (ex: Mercado Pago ou PagSeguro) para efetuar o pagamento da compra. | **MVP/Essencial** |
| **7** | US-INGRESSO-001: Como Sistema, quero **gerar um Ingresso digital** com uma **chave de autenticação única e exclusiva** após a confirmação do pagamento. | **MVP/Essencial** |
| **8** | US-INGRESSO-002: Como Usuário, quero ter uma área de **"Meus Ingressos"** onde possa visualizar o ingresso digital (com QR Code/chave) e ter a opção de **imprimir**. | **MVP/Essencial** |
| **9** | US-VALID-001: Como Porteiro, quero uma **interface web (compatível com mobile/tablet)** onde possa **ler a chave de autenticação** do ingresso para validá-lo. | **MVP/Essencial** |
| **10** | US-VALID-002: Como Porteiro, quero que o sistema **exiba o nome do comprador, a data e o valor** da compra ao validar o ingresso, e o marque como **"Utilizado"**. | **MVP/Essencial** |
| **11** | US-ADM-002: Como Administrador, quero **visualizar um Dashboard** que mostre em tempo real a **quantidade total de ingressos vendidos** por evento. | **Alta** |
| **12** | US-ADM-003: Como Administrador, quero poder **adicionar Lotes de Ingressos subsequentes (Lote 2, Lote 3, etc.)** definindo a quantidade e o preço para cada um. | **Alta** |
| **13** | US-ADM-004: Como Administrador, quero um **relatório detalhado** (tabela) que mostre **quem comprou, quando, quantidade, valor pago e data/hora** da transação para um evento específico. | **Alta** |
| **14** | US-ADM-005: Como Administrador, quero ter a opção de **remover um evento** e gerar uma **lista dos compradores afetados** para realizar o estorno manual em caso de cancelamento. | **Média** |
| **15** | US-ADM-006: Como Administrador, quero um **gráfico de performance** que mostre o **valor total arrecadado** e as **vendas por dia** para um evento. | **Média** |
| **16** | US-VENDAS-002: Como Usuário, quero que o sistema **limite a quantidade** de ingressos que posso selecionar de acordo com o estoque disponível no lote atual. | **Média** |
| **17** | US-AUTH-002: Como Usuário, quero um link de **"Esqueci a Senha"** para recuperar meu acesso ao sistema. | **Média** |
| **18** | US-EVENT-002: Como Administrador, quero poder **editar os detalhes de um evento** e seus lotes (preço, quantidade) mesmo após o início das vendas. | **Baixa** |
| **19** | US-VALID-003: Como Sistema, quero **computar o número de ingressos validados/utilizados** por evento para gerar estatísticas de comparecimento. | **Baixa** |