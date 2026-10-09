# Cola de referência do curl · curl Cheatsheet

> 🌍 [中文](README.md) · [Español](README.es.md)

Uma **cola de uma página só** com comandos curl: 29 comandos reais, e cada entrada responde a apenas três perguntas — **o que ele faz, um comando pronto para copiar e colar, e etiquetas de uso**. Sem parâmetro inventado nem sintaxe improvisada.

## Para quem é

Para desenvolvedores backend, engenheiros de operações (SRE/DevOps), quem integra APIs e qualquer pessoa que lide todo dia com APIs HTTP. Se você ainda testa endpoints clicando numa ferramenta gráfica, esta cola permite disparar uma requisição do terminal em três segundos.

## Como usar

1. Vá direto ao **[CHEATSHEET.md](CHEATSHEET.md)** — o corpo da referência, legível para desenvolvedores de qualquer idioma.
2. Verifique seu ambiente: o curl já vem instalado em quase todos os sistemas; rode `curl --version` (a versão 7.68+ cobre todos os comandos desta cola).
3. Troque o `https://example.com` dos exemplos pela sua URL real e teste cada entrada: em uma hora você domina tudo.

## O que está incluído

| Categoria | Conteúdo |
|---|---|
| 🌐 Requisições básicas | GET / POST / PUT / DELETE / PATCH / HEAD (6) |
| 🔑 Cabeçalhos e autenticação | Cabeçalhos próprios, Bearer Token, Basic Auth, User-Agent (4) |
| 📤 Enviar dados | JSON, codificação URL, upload multipart (3) |
| 📥 Tratar respostas | Ver cabeçalhos, salvar em arquivo, modo silencioso, medir tempo (5) |
| 🐞 Depuração | Detalhe com -v, trace, versão HTTP, ignorar certificado ⚠️ (4) |
| ⬇️ Downloads e limite de velocidade | Retomar download, limitar velocidade, tentativas (3) |
| 🍪 Cookies e sessão | Salvar / enviar cookies (2) |
| 🔀 Proxy | Proxy HTTP, proxy SOCKS5 (2) |

Todos os comandos usam sintaxe curl real (verificada com curl 8.5.0). Documentação oficial: https://curl.se/docs/.

## Por que estes 29

- **Cobrem todo o fluxo de integração com APIs**: de enviar a requisição, autenticar e mandar dados, até ler respostas, depurar problemas e baixar arquivos — 95 % do dia a dia numa só cola.
- **Cada comando funciona de verdade**: nada de pseudocódigo; copie, troque a URL e execute. Opções perigosas (como `-k`, que ignora a verificação do certificado) estão marcadas com ⚠️ e servem só para depuração.

## Contribuições são bem-vindas

Achou um comando errado, um parâmetro obsoleto ou uma tradução a melhorar? *Pull requests* são bem-vindos. Mantenha o formato de cada entrada (o que faz / comando / etiquetas) e **verifique cada comando com um curl real antes de enviar**.

## Licença

MIT © 2026 Guangyi Zhao. Veja [LICENSE](LICENSE).
