---
title: "Fluxograma"
author: "Droubi"
date: "19/08/2020"
output: 
  html_document:
    keep_md: yes
---



<!--html_preserve--><div id="htmlwidget-ce7c3be4e4bc5d659a6c" style="width:672px;height:480px;" class="DiagrammeR html-widget"></div>
<script type="application/json" data-for="htmlwidget-ce7c3be4e4bc5d659a6c">{"x":{"diagram":"\ngraph LR\n  A[Abertura do <br> Requerimento] -->|Triagem| B(SPU-SC-NUDEPU)\n  B --> C{<center>Caracterização <br> da Área<\/center>}\n  C -->|Área da União| D{<center>Análise Técnica<br><i>Checklist<\/i><\/center>}\n  C -->|Alodial| N(SPU-SC-NUGES)\n  C -->|Mudança de Natureza| R[<center>SPU-UC ou <br> Encaminhar como Cessão<\/center>]\n  D -->|Documentação OK!| E[Elaborar NT e <br> Minuta de Portaria]\n  D -->|Documentação incompleta!| M[Elaborar Notificação]\n  C -->|Desapropriações e/ou <br> cancelamento de RIPs?| S(SPU-SC-NUPRIV)\n  M -->|Tramitação| N\n  N -->|Informar| O{Interessado}\n  O -->|Ausência de resposta| P(SPU-SC-NUFIS)\n  O -->|Resposta| A\n  P -->|Infração| Q[Autuação]\n  P -->|Sem infração| F\n  Q --> F\n  E -->|PARA CJU/SC| I{Parecer Jurídico}\n  I -->|Favorável| J[Portaria]\n  J -->|Assinatura do Superintendente| K[DEDES]\n  I -->|Desfavorável| D\n  K -->|DOU| L[FIGEST]\n  L --> F[FIM!]\n"},"evals":[],"jsHooks":[]}</script><!--/html_preserve-->

[Fluxograma Marina](fluxogramaAutObras.pdf)
