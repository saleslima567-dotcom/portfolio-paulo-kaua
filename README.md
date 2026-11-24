# Portfólio — Paulo Kauã

Portfólio pessoal de um estudante de **Análise e Desenvolvimento de Sistemas** e desenvolvedor web em formação. O site reúne projetos selecionados, tecnologias que venho utilizando e formas de contato.

**[Acessar portfólio](https://portfolio-paulo-kaua.paulokauan.workers.dev/)** · **[Perfil no GitHub](https://github.com/saleslima567-dotcom)**

## Projetos apresentados

| Projeto | Descrição | Tecnologias |
| --- | --- | --- |
| **[LearnPlay](https://github.com/saleslima567-dotcom/Learn-Play)** | Plataforma acadêmica de cursos online com catálogo, autenticação por sessão e CSRF, perfis de acesso, matrículas, favoritos, aulas, avaliações, certificados imprimíveis e gráfico de progresso. | React 19, TypeScript, Flask, PostgreSQL, Tailwind CSS, Docker, GitHub Actions |
| **[Inventário de Softwares de TI](https://github.com/saleslima567-dotcom/Cadastro-de-Inventario-de-Softwares-de-TI.)** | Sistema de gestão de licenças com contas individuais, API REST, autenticação por sessão, CRUD, dashboard de vencimentos, filtros e exportações CSV/JSON; dados armazenados no Cloudflare D1. | HTML, CSS, JavaScript puro, Cloudflare Workers, D1 (SQLite), GitHub Actions |

O **LearnPlay é um protótipo acadêmico**: pagamento e reprodução de vídeo são demonstrativos; não há cobrança real ou streaming. O **Inventário** utiliza backend em Cloudflare Workers e persistência no banco D1. A versão atual não envia alertas automáticos por e-mail nem oferece recuperação de senha.

**Demonstrações:** [LearnPlay](https://learnplay-lzk9.onrender.com/) · [Inventário de Softwares — versão com D1](https://cadastro-de-inventario-de-softwares-de-ti.lokokaua567.workers.dev/)

## Como executar o portfólio

O portfólio é um site estático escrito em HTML, CSS e JavaScript, sem bundler, dependências npm ou backend.

```text
portfolio-paulo-kaua/
├── index.html   # Conteúdo, projetos e links
├── style.css    # Layout, estilo visual e responsividade
├── script.js      # Menu móvel e animações de entrada
├── wrangler.jsonc # Configuração de deploy e previews Cloudflare
├── .assetsignore  # Exclui arquivos internos da publicação
└── README.md
```

Clone o repositório e abra `index.html` no navegador. Não é necessário executar `npm install` nem configurar banco de dados.

## Interface e acessibilidade

- Layout responsivo para desktop e celular.
- Identidade visual do portfólio em tons de creme e verde.
- Prévias ilustrativas de ambos os projetos, com informações alinhadas às suas implementações atuais; os números mostrados nas ilustrações são demonstrativos.
- Menu móvel acessível, navegação por âncoras e efeitos de entrada com respeito à preferência por movimento reduzido.

## Publicação

**URL cadastrada no projeto:** https://portfolio-paulo-kaua.paulokauan.workers.dev/

O portfólio está hospedado no **Cloudflare Workers** e possui integração **Cloudflare Workers Builds com a branch `main` do GitHub**. Após um commit integrado à `main`, a Cloudflare executa o build e o deploy; confira o resultado no histórico de builds antes de considerar a versão publicada. Pull Requests podem receber versões de preview. A configuração está em `wrangler.jsonc`, e `.assetsignore` exclui os arquivos internos do Git e documentos que não pertencem ao site.

## Atualização dos projetos

Os dois projetos exibidos estão definidos no `index.html`. Se os recursos, links ou tecnologias mudarem, atualize a descrição, os destaques, as tecnologias, os links e, quando necessário, as representações visuais. A implementação do portfólio permanece em HTML, CSS e JavaScript sem frameworks.

Os links de demonstração devem ser conferidos antes de divulgar o portfólio em currículos ou candidaturas.

---

Feito por **Paulo Kauã** · [Contato por e-mail](mailto:saleslima567@gmail.com)
