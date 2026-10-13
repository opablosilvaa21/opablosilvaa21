# Olá, eu sou o Pablo

Sou estudante de Análise e Desenvolvimento de Sistemas na FAM e técnico em Desenvolvimento de Sistemas pelo Senac. Hoje me dedico ao back-end com Java e Spring Boot, e estou em busca da minha primeira oportunidade como desenvolvedor ou estagiário de engenharia de software.

O que mais me atrai no back-end é a parte que ninguém vê, mas que precisa funcionar sempre: garantir que um valor não se perca numa transferência, que dois pedidos ao mesmo tempo não quebrem o sistema e que os dados das pessoas fiquem protegidos. Foi isso que me levou a construir o projeto abaixo.

[Portfólio](https://portifolio-pablo.lovable.app) · [LinkedIn](https://www.linkedin.com/in/pablo-ara%C3%BAjo-silva/) · pablosilvaaraujo21@gmail.com

---

## Projeto principal

### [DevBank API](https://github.com/opablosilvaa21/bank-backend-practice)

Uma API que simula o dia a dia de um banco digital: contas, depósitos, saques, transferências, extrato e Pix. Construí com Java 21 e Spring Boot e aproveitei o projeto para estudar os problemas reais desse tipo de sistema:

- os valores são tratados com `BigDecimal` e nunca são arredondados, e o saldo nunca fica negativo;
- as transferências travam as contas sempre na mesma ordem, o que evita deadlock quando duas operações acontecem ao mesmo tempo, e há um teste que prova isso;
- o CPF nunca aparece completo na API, e os logs não guardam dados pessoais;
- tudo é coberto por testes automatizados que rodam a cada push no GitHub Actions.

## Outros projetos

**[SmartAI Assistant](https://github.com/opablosilvaa21/SmartAI-Assistante)**: um assistente com IA generativa (Gemini) que transforma anotações soltas em resumos, listas de tarefas e planos de ação. Foi meu primeiro projeto com arquitetura em camadas, feito em Python com FastAPI.

**[User Registration API](https://github.com/opablosilvaa21/user-registration-api)**: minha primeira API em Spring Boot, um CRUD de usuários com JPA. Simples, mas foi onde comecei a entender como as peças do Spring se encaixam.

## Com o que trabalho

Java, Spring Boot, Spring Data JPA, Hibernate, APIs REST, Python, FastAPI, MySQL, PostgreSQL, JUnit, Mockito, Postman, Git, GitHub Actions e Maven.

## O que estou estudando agora

Spring Security com JWT, PostgreSQL com Docker e inglês técnico, que pratico um pouco todos os dias.
