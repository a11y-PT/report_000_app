---
app: "Nome_do_aplicacao_movel"          # Entre as aspas escreve o nome da app
date: "31/12/1999"                    # Entre as aspas escreve a data de criação do 1º relatório. Os restantes estão no histórico
uri: "https://url_loja_app"   # Entre as aspas escreve o endereço da app na loja
a11y_statement: "https://dominio_sitio_web.pt/apps/acessibilidade-app1" # Entre as aspas escreve o URL da Declaração de Acessibilidade da App. A declaração da App está num URL público
owner: "Nome_do_proprietário"         # Entre as aspas escrever o nome do owner da app
seal: "qual_o_selo"                          # Entre as aspas escreve Bronze, Prata ou Ouro
---

# Relatório de auditoria

Aplicação móvel: {{ page.app }}

- Data de criação: {{ page.date }}
- URL: {{ page.uri }}
- Propriedade: {{ page.owner }}
- Candidatura: {{ page.seal }}

## Relatório {{ page.app }}

<p>O presente relatório resultou da auditoria da informação publicada na <a href="{{ page.a11y_statement }}">Declaração de Acessibilidade e Usabilidade</a>.</p>

Consulte aqui a última atualização: [Relatório {{ page.app }}](report.html)

<details>
  <summary>Histórico de atualizações</summary>
  <ul aria-label="lista de relatórios já efetuados">
    <li><a href="ddmmaaaa_report.html">(dd/mm/aaaa). Relatório {{ page.app }}</a></li>
  </ul>
</details>

<hr>

<p><small>2025 - 2026, GitTemplateReports Apps (v.1.0.0)</small></p>
