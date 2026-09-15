# hello-java

Um projeto simples em Java criado para praticar fundamentos de desenvolvimento e, principalmente, explorar o fluxo de trabalho com **Git e GitHub**.

## Sobre

Este projeto começa como uma aplicação Java simples e será utilizado como um pequeno laboratório para experimentar conceitos como:

* Java e Maven
* Estrutura de um projeto Java
* Git
* Commits
* Branches
* Merge
* Conflitos
* GitHub
* Repositórios remotos
* SSH

A ideia é manter o projeto pequeno e utilizar sua evolução para entender, na prática, como o Git funciona.

## Tecnologias

* Java
* Maven
* Git
* GitHub

## Estrutura

```text
hello-java/
├── .gitignore
├── pom.xml
└── src/
    ├── main/
    │   └── java/
    │       └── dev/
    │           └── ronald/
    │               └── App.java
    └── test/
        └── java/
            └── dev/
                └── ronald/
                    └── AppTest.java
```

## Executando

Para compilar o projeto:

```bash
mvn package
```

Para executar os testes:

```bash
mvn test
```

O arquivo `.jar` gerado será encontrado em:

```text
target/
```

## Git

O projeto utiliza Git para controle de versão.

Fluxo básico:

```bash
git status
git add .
git commit -m "mensagem"
git push
```

O repositório remoto está hospedado no GitHub.

## Objetivo

O objetivo principal deste projeto não é criar uma aplicação complexa, mas utilizar um projeto pequeno para compreender e praticar um fluxo de desenvolvimento real com Git e GitHub.

---

**Autor:** Ronald Hiedley
