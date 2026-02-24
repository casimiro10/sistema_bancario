# 💰 Sistema Bancário em Python

Este projeto é um sistema bancário simples desenvolvido em Python com o objetivo de praticar:

- Programação Orientada a Objetos (POO)
- Controle de saldo
- Registro de extrato com data e hora
- Limite de transações diárias

---

# 🚀 Funcionalidades do Sistema

O sistema permite:

✔ Criar uma conta bancária  
✔ Depositar dinheiro  
✔ Sacar dinheiro  
✔ Mostrar saldo  
✔ Mostrar extrato com data e hora  
✔ Limitar número de transações por dia  

---

# 🧠 Estrutura do Código

O sistema utiliza uma classe principal:

## Classe `ContaBancaria`

Ela contém:

- `saldo`
- `extrato`
- controle de transações diárias
- limite máximo de transações

### Métodos principais:

- `depositar(valor)`
- `sacar(valor)`
- `mostrar_saldo()`
- `mostrar_extrato()`

O extrato registra:

- Tipo da operação
- Valor
- Data
- Hora

---

# 📅 Controle de Limite Diário

O sistema:

- Conta quantas transações foram feitas no dia
- Bloqueia novas operações quando o limite é atingido
- Reinicia automaticamente quando muda a data




