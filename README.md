# Adnírcio Inocêncio

**Full Stack Developer** — Luanda, Angola

Estudante de Engenharia Informática, à procura de uma primeira oportunidade júnior.

Escrevo software que se pode abrir e usar. Cada projeto abaixo está no ar, com contas de
demonstração, testes automatizados e documentação — não são exercícios de portefólio com
capturas de ecrã bonitas e nada por trás.

---

## FinTrack Angola — finanças pessoais em Kwanzas

**[Abrir a aplicação](https://fintrack-angola.vercel.app)** · [código](https://github.com/keny343/fintrack-angola)

Entra com `adnircio@fintrack.ao` / `senha-forte-2026` — a conta tem três meses de histórico.

Orçamentos, objetivos de poupança, despesas recorrentes, importação e exportação de CSV, e um
resumo mensal escrito por um modelo de linguagem. Esse resumo tem uma particularidade: **os
números são verificados antes de chegar ao ecrã**. O backend calcula as métricas, o modelo só
pode usar essas, e se inventar ou arredondar um valor a resposta é descartada em favor de um
resumo determinístico.

O dinheiro é guardado em centavos inteiros — nunca em vírgula flutuante — e formatado em pt-AO.

TypeScript de ponta a ponta · React · Express · PostgreSQL · Vitest com Postgres em WebAssembly · Vercel + Render

---

## Colégio Mara & Lu — gestão escolar com quatro papéis

**[Abrir a aplicação](https://colegio-mara-lu.vercel.app)** · [código](https://github.com/keny343/colegio-mara-lu)

Quatro contas, todas com a senha `demo1234`:
`admin.demo@colegio.ao` · `coordenador.demo@colegio.ao` · `professor.demo@colegio.ao` · `aluno.demo@colegio.ao`

O ciclo completo: candidatura pública → análise pela direção → matrícula → ano letivo com
pautas, faltas, horários e mensagens. O que o torna interessante não é a lista de funcionalidades,
é o controlo de acessos: o coordenador vê o mesmo sistema estreitado ao seu curso e nível, e essa
fronteira é imposta na API, não escondida na interface.

React · Node/Express · MySQL · JWT em cookies httpOnly · Jest + Playwright · CI no GitHub Actions

---

## SimpleScript — uma linguagem e o seu interpretador

[código](https://github.com/keny343/simplescript) · [documentação da linguagem](https://github.com/keny343/simplescript/tree/main/docs)

Lexer → parser → AST → análise semântica → interpretador, escrito de zero em TypeScript e sem
uma única dependência de execução. Tem CLI, exemplos e um playground no browser. Fi-lo para
deixar de tratar compiladores como magia.

---

## SIGDoc — gestão documental e controlo de acesso

[código](https://github.com/keny343/sigdoc)

Ciclo de vida de documentos com classificação de acesso, 2FA por email, tokens CSRF em todas as
ações destrutivas e limitação de tentativas de login por conta e por IP. É o projeto mais antigo
e o único em PHP, e foi onde aprendi segurança web a corrigir os meus próprios erros.

PHP 8.2 · MySQL · Docker · API REST

> A instância pública está sem base de dados desde que o serviço gratuito expirou, por isso não
> publico um link que dê erro. O código e as decisões de segurança estão todos no repositório.

---

## Como trabalho

Testes onde o custo de um erro é real: o domínio financeiro, as regras de acesso, a política de
senhas, os filtros de upload. CI que corre instalação, testes e build a cada push. Documentação
que explica decisões em vez de repetir o código. Segredos só em variáveis de ambiente.

Segurança não é uma secção no fim do README: sessões em cookies httpOnly, hashing com bcrypt,
CSRF, limitação de tentativas, SQL sempre parametrizado, headers e filtros de upload.

## Contacto

GitHub [@keny343](https://github.com/keny343) · aberto a oportunidades júnior em Full Stack,
Backend ou Software Development.
