### TESTE PRÁTICO PROGRAMAÇÃO - Iniflex

# 📊 Sistema de Funcionários em Java

Projeto em **Java** para gerenciamento de funcionários de uma indústria fictícia.  
O objetivo é praticar conceitos de **Programação Orientada a Objetos (POO)**, uso de **Collections**, **Streams** e formatações de dados.

---

## 📌 Funcionalidades Implementadas

### 1. Estrutura de Classes
- **Pessoa**: classe base com atributos `nome` e `dataNascimento`.
- **Funcionario**: herda de `Pessoa` e adiciona os atributos `salario` e `funcao`.
- **Principal**: classe com o método `main` para executar as operações solicitadas.

---

### 2. Operações realizadas (requisitos)

✔️ 3.1 Inserir todos os funcionários.  
✔️ 3.2 Remover o funcionário `João`.  
✔️ 3.3 Imprimir todos os funcionários formatados:  
   - Data no formato `dd/MM/yyyy`.  
   - Salário no formato brasileiro (`1.000,00`).

✔️ 3.4 Aplicar **10% de aumento** a todos os funcionários.  
✔️ 3.5 Agrupar funcionários por função (`Map<String, List<Funcionario>>`).  
✔️ 3.6 Imprimir funcionários agrupados por função.  
✔️ 3.8 Listar funcionários que fazem aniversário em **Outubro (10)** e **Dezembro (12)**.  
✔️ 3.9 Exibir o funcionário mais velho (nome e idade).  
✔️ 3.10 Ordenar e imprimir funcionários por ordem alfabética.  
✔️ 3.11 Calcular o **total da folha salarial**.  
✔️ 3.12 Exibir quantos **salários mínimos** cada funcionário recebe (considerando R$ 1.212,00).  

---

## 🛠️ Tecnologias Utilizadas
- **Java 8+**  
- `java.time.LocalDate` (API de datas)  
- `BigDecimal` (valores monetários)  
- `List`, `Map`, `Streams`  
- `DateTimeFormatter` e `NumberFormat` para formatação  

---

## ▶️ Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/sistema-funcionarios-java.git
    ```
2. Compile o projeto:
    ```bash
    javac *.java
    ```
3. Execute:
    ```bash
    java Principal
    ```

✍️ Autor

👤 Ruan Diego

💻 Full-stack developer

🌎 Foco em backend Java + frontend Angular/React

🎓 Engenheiro de Software (UFC)
