```mermaid
graph TD
  A[Abertura do Requerimento <br>] -->|Triagem| B(SPU-SC-NUDEPU)
  B --> C{Checklist <br> da documentação}
  C -->|Completa| D[Elaborar NT]
  C -->|Incompleta| E[Notificar p/ <br> complementação]
  C -->|Não é área da União| F[Devolver]
```