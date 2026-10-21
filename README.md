# GWD — Estudos de Análise de Dados de Ondas Gravitacionais

Repositório de notebooks Jupyter organizados para estudo, treinamento e orientação acadêmica em **análise de dados de ondas gravitacionais**.

**Organização e manutenção:** Ronai Lisboa — Universidade Federal do Rio Grande do Norte (UFRN).

> **Nota sobre autoria:** este repositório reúne materiais didáticos provenientes de diferentes projetos e autores. A organização desta coleção e sua manutenção **não implicam autoria original** dos notebooks. Os créditos, avisos de direitos autorais e condições de licenciamento estabelecidos pelos respectivos autores e projetos continuam aplicáveis.

## Objetivos

- Apoiar a formação de estudantes no uso de Python e JupyterLab para análise de dados de detectores de ondas gravitacionais.
- Estudar acesso a dados abertos, qualidade de dados, representação no domínio da frequência, espectrogramas, formas de onda, filtragem casada e inferência de parâmetros.
- Registrar exercícios, adaptações e contribuições desenvolvidos durante a orientação acadêmica.
- Facilitar a colaboração e a revisão de alterações por meio do GitHub.

## Organização do material e fontes

| Diretório | Conteúdo | Fonte e atribuição |
| --- | --- | --- |
| [`gwpy/`](gwpy/) | Exemplos de ciência aberta e filtragem casada usando GWpy. | Procedência e autores específicos dos notebooks **a confirmar**; consultar as referências e créditos contidos nos próprios arquivos. Informações sobre a biblioteca: [GWpy](https://gwpy.github.io/). |
| [`introduction_gwosc_data/`](introduction_gwosc_data/) | Introdução à obtenção, leitura e análise de dados abertos do GWOSC, incluindo qualidade dos dados, frequência e exemplos com GWpy. | Projeto original: [gwosc-tutorial/introduction_gwosc_data](https://github.com/gwosc-tutorial/introduction_gwosc_data), de seus respectivos autores e contribuidores. |
| [`lsc/`](lsc/) | Notebooks didáticos sobre sinais e observações de ondas gravitacionais. | Procedência e condições de licença específicas **a confirmar**; preservar os créditos presentes nos notebooks. |
| [`odw/`](odw/) | Tutoriais e tópicos avançados dos workshops de dados abertos, incluindo formas de onda, processamento de sinais, buscas e inferência de parâmetros. | Projeto original: [gw-odw/odw](https://github.com/gw-odw/odw), de seus respectivos autores e contribuidores. |

A estrutura das subpastas foi mantida para facilitar a localização dos materiais. Esta coleção inclui somente os notebooks selecionados: **não é uma cópia integral** dos projetos originais e pode não conter todos os arquivos auxiliares necessários à execução de cada exercício.

## Direitos autorais, atribuição e licenças

Os materiais de terceiros permanecem sujeitos aos direitos autorais e às licenças de seus projetos de origem. Em particular:

- **Introduction to GWOSC Data:** o projeto original informa **GPL-3.0 ou posterior**. Consulte o arquivo `LICENSE`, o documento de contribuidores e as informações no [repositório original](https://github.com/gwosc-tutorial/introduction_gwosc_data).
- **Gravitational Wave Open Data Workshop:** o projeto original disponibiliza licença **GPL-3.0**. Consulte seu arquivo `LICENSE` e o [repositório original](https://github.com/gw-odw/odw).
- **gwpy/ e lsc/:** a licença e a origem de cada notebook ainda devem ser verificadas; a inclusão nesta coleção não concede direitos adicionais de redistribuição ou modificação.

Sempre que um notebook for adaptado, devem ser preservados os créditos e avisos existentes, identificadas as mudanças realizadas e observados os termos de sua licença. O acesso privado ao repositório não elimina essas obrigações. Este README não substitui os textos integrais das licenças originais: **os arquivos LICENSE e demais documentos de atribuição pertinentes devem acompanhar os materiais redistribuídos**.

## Uso educacional e orientação

O repositório destina-se a apoiar atividades de estudo orientado, treinamento e desenvolvimento de competências em análise de dados de ondas gravitacionais. Estudantes colaboradores poderão executar notebooks, reproduzir exemplos, elaborar exercícios e propor adaptações, com acompanhamento do responsável pela manutenção.

As modificações realizadas durante a orientação devem ser registradas em commits claros, com reconhecimento das fontes e distinção entre conteúdo original e contribuições novas. Resultados de análises científicas devem ser documentados com parâmetros, versões de software e referências apropriadas.

## Fluxo de colaboração

O acesso ao repositório é privado e depende de convite do mantenedor.

```bash
git clone https://github.com/Ronai/gwd.git
cd gwd
git switch -c estudante-analises
```

Após editar e salvar os notebooks:

```bash
git add -- '*.ipynb'
git commit -m "Describe notebook changes"
git push -u origin estudante-analises
```

Abra um **Pull Request** no GitHub para revisão antes de incorporar as alterações à branch `main`. Antes de começar uma nova etapa, sincronize sua cópia com a versão mais recente do repositório.

## Dados e ambiente de execução

Os arquivos de dados volumosos (como `.hdf5` e `.gwf`), resultados intermediários e ambientes Python **não fazem parte desta coleção**. Alguns notebooks dependem de bibliotecas ou arquivos disponibilizados nos projetos de origem; consulte as instruções correspondentes antes de executá-los.

Não registre senhas, tokens, credenciais ou dados de acesso nos notebooks ou no histórico Git.

## Referências e recursos

- [Gravitational Wave Open Science Center (GWOSC)](https://gwosc.org/)
- [Tutoriais do GWOSC](https://gwosc.org/tutorials/)
- [Introduction to GWOSC Data — projeto original](https://github.com/gwosc-tutorial/introduction_gwosc_data)
- [Gravitational Wave Open Data Workshop — projeto original](https://github.com/gw-odw/odw)
- [GWpy — biblioteca de análise de dados](https://gwpy.github.io/)

---

**Manutenção e organização da coleção:** Ronai Lisboa (UFRN). **Autoria dos materiais de terceiros:** respectivos autores e colaboradores, conforme as fontes, avisos e licenças originais.
