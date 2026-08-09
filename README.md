# Sistema de Carteirinhas de Associação

![Java](https://img.shields.io/badge/Java-17-blue?logo=java)
![License](https://img.shields.io/badge/license-MIT-green?logo=github)
![Version](https://img.shields.io/badge/version-1.0.0-orange?logo=semantic-release)
![Build](https://img.shields.io/github/actions/workflow/status/jphs682/poo/build.yml?logo=githubactions&label=build)
![Last Commit](https://img.shields.io/github/last-commit/jphs682/poo?logo=git)
![Repo Size](https://img.shields.io/github/repo-size/jphs682/poo?logo=github)
![Stars](https://img.shields.io/github/stars/jphs682/poo?logo=github)
--- 

Projeto desenvolvido para a disciplina de Programação Orientada a Objetos (POO) em Java.  
O objetivo é criar um sistema simples de gerenciamento de associados e carteirinhas, utilizando os pilares da POO.

## 🎯 Objetivos
- Aplicar os conceitos de **abstração, encapsulamento, herança e polimorfismo**.
- Criar classes que representem **Associados** e suas **Carteirinhas**.
- Implementar um menu interativo no terminal para cadastrar e listar associados.

## 🛠️ Tecnologias
- **Java 25+**
- Paradigma: **Programação Orientada a Objetos (POO)**

## 📂 Estrutura do Projeto
- `Associado.java` → Classe que representa o associado.
- `Carteirinha.java` → Classe que representa a carteirinha.
- `Associacao.java` → Classe que gerencia a lista de associados.
- `Main.java` → Classe principal com menu no terminal.

```
carteirinhas-poo/
│
├── README.md              # Documentação do projeto
├── LICENSE                # Licença (ex.: MIT)
├── .gitignore             # Arquivos a ignorar no Git
│
├── src/                   # Código-fonte principal
│   ├── Main.java          # Classe principal com menu
│   ├── associacao/        # Pacote para lógica da associação
│   │   ├── Associacao.java
│   │   ├── Associado.java
│   │   └── Carteirinha.java
│
├── data/                  # Dados persistidos
│   └── associados.csv     # Arquivo para salvar associados
│
└── test/                  # Testes unitários (se quiser usar JUnit)
    └── AssociadoTest.java
```

---

## 🚀 Como executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/jphs682/poo.git
   ```
2. Compile os arquivos:
   ```bash
   javac *.java
   ```
3. Execute o programa:
   ```bash
   java Main
   ```

---

## 📌 Funcionalidades
- Cadastrar associado com nome e CPF.
- Gerar carteirinha com código e validade.
- Listar associados e suas carteirinhas.
- Renovar carteirinha.

---

## 📖 Conceitos aplicados
- **Abstração**: modelagem de entidades reais (Associado, Carteirinha).
- **Encapsulamento**: atributos privados com métodos de acesso.
- **Herança**: possibilidade de criar tipos específicos de associados.
- **Polimorfismo**: sobrescrita de métodos para diferentes tipos de associados.

---

## 🔮 Planos futuros

Este projeto foi pensado de forma **genérica**, para que possa ser expandido além da versão inicial em terminal.  
Algumas melhorias previstas para versões futuras incluem:

- **Sistema de cadastro completo**  
  - Menu interativo para cadastrar, buscar e remover associados.  
  - Diferentes tipos de associados (morador, estudante, agricultor).  

- **Integração com banco de dados SQLite**  
  - Substituir o armazenamento em arquivo `.csv` por um banco de dados real.  
  - Tabelas para `associados` e `carteirinhas`, com relacionamento entre elas.  

- **Validação de dados**  
  - Verificação de CPF único.  
  - Controle de validade das carteirinhas.  

- **Testes automatizados**  
  - Implementação de testes unitários para garantir qualidade do código.  

- **Escalabilidade**  
  - Possibilidade de adaptar o sistema para outras associações comunitárias ou estudantis.  
  - Estrutura genérica que facilita a criação de novos tipos de associados sem alterar a lógica central.  

---

## 📌 Visão


A ideia é que este projeto seja um **protótipo inicial** de um sistema de gestão de associados, que pode evoluir para uma solução mais completa e profissional, servindo como base para comunidades, escolas, clubes ou qualquer organização que precise de carteirinhas de associação.

---

## 👨‍🏫 Autor

[GitHub - jphs682/poo](https://github.com/jphs682/poo)

