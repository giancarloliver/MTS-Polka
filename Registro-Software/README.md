# MTS-PolKA — v1.0

**Weighted Multipath Traffic Splitting With Source Routing for Elephant and Mice Flows**

Implementação e documentação do **MTS-PolKA**, uma abordagem para divisão de tráfego multicaminho baseada em pesos e roteamento na fonte, utilizando identificadores de rota e de perfil de pesos e operações sobre polinômios em aritmética de corpos finitos.

## Versão do software

**MTS-PolKA v1.0**

> **Nota de versionamento:** `v1.0` identifica a versão do software. Eventuais referências a `V5.3` nos documentos identificam a versão do **processo/dossiê de auditoria documental**, e não a versão do software.

## Sobre o projeto

O MTS-PolKA combina:

- roteamento na fonte;
- divisão de tráfego multicaminho por pesos;
- identificadores `routeID` e `weightID`;
- processamento no plano de dados;
- perfis estáticos de distribuição de tráfego;
- cálculo baseado em polinômios e aritmética modular;
- encaminhamento sem necessidade de reconfiguração dinâmica dos switches de núcleo para cada fluxo.

A arquitetura é organizada conceitualmente em **plano de controle** e **plano de dados**.

### Plano de controle

Responsável, entre outras funções, por:

1. determinar caminhos;
2. calcular identificadores de rota;
3. selecionar perfis de distribuição;
4. associar os identificadores aos fluxos;
5. instalar as regras necessárias nos dispositivos de ingresso.

### Plano de dados

Responsável por:

1. interpretar os identificadores transportados pelo pacote;
2. determinar as portas de saída;
3. selecionar o perfil de distribuição;
4. realizar a seleção do caminho conforme o perfil de pesos;
5. encaminhar o pacote sem manter estado específico por fluxo nos switches de núcleo.

## Estrutura do repositório

Os diretórios existentes no projeto contêm o código-fonte, experimentos, configurações P4, materiais do artigo e documentação técnica.

A documentação relacionada ao **registro do programa de computador** deve ser mantida separada do código operacional, preferencialmente em:

`audit/V5.3/`

## Dossiê documental — MTS-PolKA v1.0

O dossiê consolidado contém documentos técnicos, matrizes de rastreabilidade, documentos formais e instrumentos de saneamento documental, incluindo:

| Arquivo | Finalidade |
|---|---|
| `01_Oficio_Comunicacao_Inovacao_MTS-PolKA.docx` | Ofício de comunicação |
| `02_Pedido_Registro_Programa_Computador_MTS-PolKA.docx` | Pedido de registro |
| `03_Formulario_Criacao_Software_MTS-PolKA.docx` | Formulário de criação |
| `04_Termo_Cessao_Direitos_MTS-PolKA.docx` | Termo de cessão de direitos |
| `05_Memorial_Descritivo_Tecnico_MTS-PolKA-v6.docx` | Memorial técnico |
| `06_Matriz_Autores_Contribuicoes_MTS-PolKA.docx` | Autoria e contribuições |
| `07_Checklist_Documentos_Autores_MTS-PolKA.docx` | Checklist documental |
| `08_Matriz_Titularidade_Ifes_Ufes_MTS-PolKA.docx` | Matriz de titularidade |
| `09_Diligencia_Parceria_Ifes_Ufes_MTS-PolKA.docx` | Diligência de parceria |
| `10_Diligencia_Financiamento_Fapes_Capes_MTS-PolKA.docx` | Diligência de financiamento |
| `11_Matriz_Financiamento_PI_MTS-PolKA.docx` | Matriz de financiamento |
| `12_Checklist_Final_SIPAC_AGIFES_MTS-PolKA.docx` | Checklist final |
| `13_Inventario_Final_Dossie_MTS-PolKA.xlsx` | Inventário final de evidências |
| `14_Matriz_Rastreabilidade_MTS-PolKA.xlsx` | Rastreabilidade documental |
| `15_Relatorio_Saneamento_Final_V5.3_MTS-PolKA.docx` | Relatório de saneamento |
| `16_Matriz_Fechamento_Final_MTS-PolKA.docx` | Matriz final de fechamento |
| `README_Versao_Final.txt` | Nota de organização da versão final |
| `NOTA_VERSAO_v1.0.txt` | Regra de versionamento |

## Estado documental

### Documentação técnica

- [x] Software identificado: **MTS-PolKA**
- [x] Finalidade e problemas identificados
- [x] Funcionalidades de controle e dados identificadas
- [x] Arquitetura geral dividida entre controle e dados
- [x] Código-fonte localizado no GitHub
- [x] Localização da pasta do servidor documentada
- [x] Evidência da pasta no servidor institucional documentada
- [x] Linguagens identificadas: Python 87,4%, P4 9,0% e Shell 2,8%
- [x] Componentes e módulos identificados
- [x] Autores vinculados ao código
- [x] Contribuições técnicas individualizadas
- [x] Desenvolvimento documentado
- [x] Individualização e originalidade caracterizadas pela abordagem matemática baseada em CRT/RNS
- [x] Documentação técnica complementar consolidada

### Documentação formal

- [x] Ofício de Comunicação
- [x] Pedido de Registro
- [x] Formulário de Criação
- [ ] Documentos formais de parceria Ifes/Ufes
- [ ] Documentação Fapes e Termos de Outorga

Os itens ainda não concluídos permanecem explicitamente identificados como **pendências documentais**, não sendo tratados como fatos comprovados.

## Autoria e versionamento

O código e a documentação técnica devem preservar a rastreabilidade dos autores, contribuições e histórico de desenvolvimento.

A versão de referência para o **registro do programa de computador** é:

**MTS-PolKA — v1.0**

## Artigo relacionado

O projeto está associado ao trabalho:

**Weighted Multipath Traffic Splitting With Source Routing for Elephant and Mice Flows**

O material científico e os experimentos correspondentes permanecem nos diretórios próprios do repositório.

## Licença

Consulte os arquivos de licença e as condições de uso presentes neste repositório antes de reutilizar o código.

---

**Repositório:** https://github.com/giancarloliver/MTS-PolKA
