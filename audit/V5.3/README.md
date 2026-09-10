# Auditoria V5.3 — MTS-PolKA

## Objetivo

Verificar a materialização, estrutura e consistência dos artefatos documentais da versão V5.3.

## Escopo principal

Os testes de fechamento concentram-se nos seguintes artefatos:

- docs/registro-programa-computador/13_Inventario_Final_Dossie_MTS-PolKA.xlsx
- docs/registro-programa-computador/14_Matriz_Rastreabilidade_MTS-PolKA.xlsx
- docs/registro-programa-computador/15_Relatorio_Saneamento_Final_V5.3_MTS-PolKA.docx

## Testes

### T01 — Materialização

Confirmar que os arquivos existem fisicamente no repositório.

### T02 — Integridade estrutural

Verificar se os arquivos DOCX e XLSX podem ser abertos e se possuem estrutura válida.

### T03 — Consistência Inventário × Rastreabilidade

Comparar o arquivo 13 com o arquivo 14.

### T04 — Consistência Inventário × Relatório

Comparar o arquivo 13 com o arquivo 15.

### T05 — Consistência Rastreabilidade × Relatório

Comparar o arquivo 14 com o arquivo 15.

### T06 — Contradições internas

Pesquisar afirmações incompatíveis, especialmente:

- 100% comprovado;
- autoria irrefutável;
- titularidade definitivamente comprovada;
- depósito já realizado sem evidência;
- SHA-512 já gerado sem evidência;
- assinaturas já realizadas sem evidência;
- documentação externa já recebida sem evidência.

## Regra de evidência

A existência de um arquivo no GitHub comprova sua materialização no repositório, mas não comprova automaticamente a correção ou consistência do seu conteúdo.

## Estado inicial

Pendente de auditoria de conteúdo.

## Relações

13 ↔ 14
13 ↔ 15
14 ↔ 15

## Artefatos auditáveis

| ID | Arquivo | Status |
|---|---|---|
| 13 | [Inventário Final](docs/registro-programa-computador/13_Inventario_Final_Dossie_MTS-PolKA.xlsx) | Materializado |
| 14 | [Matriz de Rastreabilidade](docs/registro-programa-computador/14_Matriz_Rastreabilidade_MTS-PolKA.xlsx) | Materializado |
| 15 | [Relatório de Saneamento V5.3](docs/registro-programa-computador/15_Relatorio_Saneamento_Final_V5.3_MTS-PolKA.docx) | Materializado |


### Regra de auditoria

A existência do arquivo no repositório comprova sua materialização no
commit correspondente. A existência do arquivo, isoladamente, não implica
consistência de conteúdo.

Os artefatos 13, 14 e 15 deverão ser submetidos à verificação estrutural
e à comparação cruzada:

13 ↔ 14
13 ↔ 15
14 ↔ 15
