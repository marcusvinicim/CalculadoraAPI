# Calculadora RMI

## Descrição
Este projeto é uma aplicação de calculadora utilizando Java e RMI (Remote Method Invocation). Ele permite executar operações matemáticas remotamente entre um servidor e um cliente.

---

## Estrutura do Projeto
- `src/common/`: Contém as interfaces compartilhadas entre servidor e cliente.
- `src/server/`: Contém as classes para execução do servidor da calculadora.
- `src/client/`: Contém as classes para execução do cliente que se conecta ao servidor.
- `bin/`: Diretório onde os arquivos compilados (.class) serão armazenados.

---

## Pré-requisitos
Antes de rodar o projeto, certifique-se de ter instalado:
- **Java Development Kit (JDK)**: Versão 11 ou superior.
- Variável de ambiente `JAVA_HOME` configurada.

---

## Passos para Compilar e Rodar

### 1. Compilar o Código
Execute o comando abaixo para compilar todas as classes:
```bash
javac -d bin src/common/*.java src/server/*.java src/client/*.java
