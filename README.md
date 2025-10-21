# DIO - 🏦 Sistema Bancário – Avançado

Este complemento descreve as funcionalidades adicionadas ao sistema bancário 3, mantendo a estrutura orientada a objetos e o uso via terminal.

---

## 🚀 Funcionalidades adicionadas

### 🔟 Limite diário de transações
Cada cliente pode realizar até 10 transações por dia. A partir da 11ª tentativa, o sistema bloqueia novas operações automaticamente.

### 🔁 Iterador personalizado para contas
A classe `ContaIterador` foi criada para permitir a navegação estruturada na listagem de contas, seguindo o protocolo de iteradores do Python.

### 🧠 Log automático de operações
Cada ação executada (depósito, saque, criação de cliente ou conta) é registrada com tipo de transação, data e hora por meio de um decorador chamado `log_transacao`.

### 📄 Gerador de relatório de transações
A classe `Historico` agora possui o método `gerar_relatorio`, que permite iterar sobre as transações de uma conta. É possível filtrar por tipo de operação, como apenas saques ou apenas depósitos.

### 🧱 Centralização da lógica de transações
O método `realizar_transacao()` passou a controlar todo o fluxo de verificação e execução, garantindo consistência e evitando duplicação de lógica.

---

Essas melhorias mantêm a compatibilidade com o projeto original e reforçam a robustez da aplicação.
