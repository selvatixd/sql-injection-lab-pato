# 💼 SQL Injection Lab – Pato Academy com Caido.io

Este projeto documenta a exploração de uma vulnerabilidade de **SQL Injection** em um ambiente simulado da **Pato Academy**, utilizando a ferramenta **Caido.io** para interceptação e manipulação de requisições.

🔗 **Acesse o relatório online:**  
[https://selvatixd.github.io/sql-injection-lab-pato](https://selvatixd.github.io/sql-injection-lab-pato)

---

## 🧠 Objetivo

Identificar e explorar vulnerabilidades de SQL Injection em uma aplicação web simulada, mapeando a estrutura interna do banco de dados e extraindo informações sensíveis.

---

## 🛠️ Tecnologias e Ferramentas

| Ferramenta     | Função                                      |
|----------------|---------------------------------------------|
| Caido.io       | Interceptação e manipulação de requisições |
| SQLite         | Banco de dados utilizado pela aplicação     |
| Pato Academy   | Ambiente de simulação para testes de segurança |

---

## ⚙️ Técnicas Utilizadas

- Reconhecimento de endpoints dinâmicos
- Testes com payloads básicos (`'`, `--`, `AND 1=1`)
- Enumeração com `UNION SELECT` e `group_concat`
- Leitura de `sqlite_master` e `PRAGMA table_info`
- Extração de dados sensíveis (e-mail, senha, nickname)

---

## 📸 Evidências Visuais

O projeto inclui prints que comprovam a exploração bem-sucedida, como:
- Identificação de colunas sensíveis
- Execução de payloads SQL
- Extração da flag do banco de dados

---

## 🎯 Resultado Final

A exploração foi concluída com sucesso, demonstrando domínio de técnicas de SQL Injection, análise manual de aplicações web e uso de ferramentas profissionais de interceptação.

---

## 📚 Autor

**Selvati**  
Pentester em formação | Segurança ofensiva
