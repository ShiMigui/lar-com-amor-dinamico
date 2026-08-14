# Lar com Amor — Dinâmico

Versão dinâmica do projeto de **TCC da Etec Aristóteles Ferreira**: plataforma para dar um lar com amor a todos os animais.

Aplicação em **ASP.NET Web Forms (C#)** com banco de dados, em substituição à versão estática em HTML.

## Funcionalidades

- Cadastro e login de usuários
- Páginas de **animais**, **eventos** e **organizações**
- Perfil do usuário e formulários de adoção
- Painel (*dashboard*) para administração

## Estrutura

```
lar_com_amor/
├── *.aspx + code-behind     # páginas (animais, eventos, organizações, perfil...)
├── classes/                 # classes de apoio
├── bd/                      # banco de dados
└── script/, style/, img/    # recursos estáticos
```

## Executando

Abra `lar_com_amor.sln` no Visual Studio e configure a conexão em `Web.config`.
