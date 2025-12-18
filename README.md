
---

## ⚡ Objetivo

O objetivo deste script é:

1. Validar se o **lexer** do Minishell interpreta corretamente aspas simples (`'`) e duplas (`"`).  
2. Comparar a saída do Minishell com o Bash para identificar diferenças.  
3. Facilitar o desenvolvimento e depuração do Minishell, automatizando os testes.

---

## 🛠️ Pré-requisitos

- **Minishell compilado** (executável `./minishell`)  
- **Bash** instalado no sistema  
- Sistema Linux/Unix (testado no Ubuntu)

> ❗ O script **não funciona** se o executável do Minishell não estiver presente.  
> Execute `make` antes de rodar os testes.

---

## 🏃 Como usar

1. Compile seu Minishell:

```bash
make
ls -l test_quotes.sh
chmod +x test_quotes.sh
./test_quotes.sh
