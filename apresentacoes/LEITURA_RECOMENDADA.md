---
title: "Leitura recomendada"
bibliography: ../bibliography.bib
link-citations: true
---

# Leitura recomendada

Este arquivo reúne os materiais citados nas apresentações do curso. As referências bibliográficas de artigos e livros estão cadastradas em [`bibliography.bib`](../bibliography.bib). Os números de slide indicam onde cada material aparece na apresentação original.

## Aula 1 — Introdução à transcriptômica espacial {#aula-1}

Apresentação: [`Aula1_Introducao_transcriptomica_espacial.pptx`](Aula1_Introducao_transcriptomica_espacial.pptx)

### Artigos científicos {#artigos-cientificos-aula-1}

- [**Full-length mRNA-Seq from single-cell levels of RNA and individual circulating tumor cells**](https://doi.org/10.1038/nbt.2282) — trabalho que apresenta o Smart-seq para obtenção de transcriptomas completos a partir de células individuais. [@Ramskold2012SmartSeq] *(slide 18)*
- [**Massively parallel digital transcriptional profiling of single cells**](https://doi.org/10.1038/ncomms14049) — descrição da plataforma Chromium para perfil transcricional de células individuais em grande escala. [@Zheng2017Chromium] *(slide 19)*
- [**Benchmarking full-length transcript single cell mRNA sequencing protocols**](https://doi.org/10.1186/s12864-022-09014-5) — comparação de protocolos de sequenciamento de RNA de célula única com cobertura do transcrito completo. [@Probst2022Benchmarking] *(slides 21 e 26)*
- [**A practical guide to single-cell RNA-sequencing for biomedical research and clinical applications**](https://doi.org/10.1186/s13073-017-0467-4) — guia introdutório para planejamento experimental, escolha de protocolo, controle de qualidade e análise de scRNA-seq. [@Haque2017PracticalGuide] *(slide 27)*
- [**A comprehensive analysis framework for evaluating commercial single-cell RNA sequencing technologies**](https://doi.org/10.1093/nar/gkae1186) — avaliação comparativa de tecnologias comerciais de scRNA-seq. [@DeSimone2025Commercial] *(slide 27)*
- [**Visualization of single RNA transcripts in situ**](https://doi.org/10.1126/science.280.5363.585) — trabalho fundador sobre detecção e quantificação de moléculas individuais de RNA por hibridização *in situ*. [@Femino1998SingleRNA] *(slide 29)*
- [**Gene expression profiles of laser-captured adjacent neuronal subtypes**](https://doi.org/10.1038/4806) — aplicação de microdissecção a laser e amplificação de RNA para comparar perfis de expressão de populações neuronais adjacentes. [@Luo1999LaserCapture] *(slide 29)*
- [**Visualization and analysis of gene expression in tissue sections by spatial transcriptomics**](https://doi.org/10.1126/science.aaf2403) — artigo seminal que introduziu a estratégia denominada *spatial transcriptomics*. [@Stahl2016SpatialTranscriptomics] *(slide 30)*
- [**Method of the Year: spatially resolved transcriptomics**](https://doi.org/10.1038/s41592-020-01033-y) — panorama da transcriptômica espacial como método do ano de 2020 pela *Nature Methods*. [@Marx2021MethodOfTheYear] *(slide 31)*
- [**Spatial transcriptomics: Technologies, applications and experimental considerations**](https://doi.org/10.1016/j.ygeno.2023.110671) — revisão comparativa de plataformas, aplicações e critérios para planejamento experimental. [@Wang2023SpatialTechnologies] *(slide 32)*
- [**High-definition spatial transcriptomic profiling of immune cell populations in colorectal cancer**](https://doi.org/10.1038/s41588-025-02193-3) — apresentação e avaliação do Visium HD em amostras de câncer colorretal. [@DeOliveira2025VisiumHD] *(slide 37)*
- [**The emerging landscape of spatial profiling technologies**](https://doi.org/10.1038/s41576-022-00515-3) — revisão das principais abordagens de perfil molecular espacial e de suas características técnicas. [@Moffitt2022SpatialProfiling] *(slide 39)*
- [**Current best practices in single-cell RNA-seq analysis: a tutorial**](https://doi.org/10.15252/msb.20188746) — tutorial de boas práticas para pré-processamento e análises posteriores de scRNA-seq. [@Luecken2019BestPractices] *(slide 42)*
- [**A comprehensive workflow for optimizing RNA-seq data analysis**](https://doi.org/10.1186/s12864-024-10414-y) — fluxo de trabalho para seleção e otimização das etapas de análise de RNA-seq. [@Jiang2024RNASeqWorkflow] *(slide 42)*

### Livro e capítulo on-line {#livro-e-capitulo-on-line-aula-1}

- [**Orchestrating Spatial Transcriptomics Analysis with Bioconductor — Reads to counts**](https://bioconductor.org/books/3.22/OSTA/pages/seq-reads-to-counts.html) — capítulo sobre a transformação das leituras de sequenciamento em matrizes de contagem, incluindo barcodes espaciais, alinhamento, controle de qualidade e contagem. [@Crowell2025OSTA] *(slide 44)*

### Tutoriais e documentação {#tutoriais-e-documentacao-aula-1}

- [**Tutorial do RStudio para iniciantes: um guia completo**](https://www.datacamp.com/pt/tutorial/r-studio-tutorial) — versão em português do tutorial introdutório do DataCamp. *(slide 9, hiperlink embutido)*
- [**Space Ranger Algorithms: Read Processing & Secondary Analysis**](https://www.10xgenomics.com/support/software/space-ranger/latest/algorithms-overview/gene-expression) — documentação oficial sobre processamento de leituras, alinhamento, barcodes, UMIs e análises secundárias do Space Ranger. *(slide 42, hiperlink embutido)*
- [**Configuração do ambiente do RStudio**](https://flaviogckessler.github.io/Curso_ST/vinhetas/DOC1_Configuracao_do_ambiente_RStudio.html) — vinheta do curso para preparar o ambiente das aulas práticas. *(slide 63, hiperlink embutido)*
- [**Tutorial: Getting Started with R and RStudio**](https://www.dataquest.io/blog/tutorial-getting-started-with-r-and-rstudio/) — introdução ao R e ao RStudio publicada pelo Dataquest. *(slide 67)*
- [**Introduction to renv**](https://rstudio.github.io/renv/articles/renv.html) — documentação sobre criação de ambientes reproduzíveis e isolamento das dependências de projetos em R. *(slide 67)*
- [**RStudio Tutorial for Beginners: A Complete Guide**](https://www.datacamp.com/tutorial/r-studio-tutorial) — versão em inglês do tutorial introdutório do DataCamp. *(slide 67)*

### Vídeos {#videos-aula-1}

- [**Single Cell Gene Expression Protocol v3.1: Assemble Chromium Next GEM Chip G**](https://www.youtube.com/watch?v=cH8ldAqKUzE) — demonstração da montagem do chip para o protocolo Chromium Single Cell Gene Expression. *(slide 27)*
- [**Visium Spatial Gene Expression Protocol**](https://www.youtube.com/playlist?list=PLfaSRwcfHcq1acX1nuTFcUGClpNRPEyHH) — série de vídeos sobre o protocolo Visium Spatial Gene Expression. *(slide 39)*

### Sites e repositórios {#sites-e-repositorios-aula-1}

- [**Perfil de Flávio Carazza-Kessler no GitHub**](https://github.com/flaviogckessler) *(slide 6, hiperlink embutido)*
- [**Perfil do SysBioLab no GitHub**](https://github.com/sysbiolab) *(slide 6, hiperlink embutido)*
- [**Repositório do curso no GitHub**](https://github.com/flaviogckessler/Curso_ST) — apresentações, vinhetas e materiais das atividades práticas. *(slide 62, hiperlink embutido)*

## Aula 2 — Pré-processamento e clusterização {#aula-2}

Apresentação: [`Aula2_Aula_PreProcessamento_Clusterizacao.pptx`](Aula2_Aula_PreProcessamento_Clusterizacao.pptx)

### Artigos científicos {#artigos-cientificos-aula-2}

- [**Review of single-cell RNA-seq data clustering for cell-type identification and characterization**](https://doi.org/10.1261/rna.078965.121) — revisão dos principais métodos de clusterização usados para identificar e caracterizar tipos celulares em dados de scRNA-seq. [@Zhang2023Clustering] *(slide 40)*
- [**SpatialExperiment: infrastructure for spatially-resolved transcriptomics data in R using Bioconductor**](https://doi.org/10.1093/bioinformatics/btac299) — apresenta a classe `SpatialExperiment` e sua infraestrutura para representar e manipular dados de transcriptômica espacial no Bioconductor. [@Righelli2022SpatialExperiment] *(slide 57)*
- [**Museum of spatial transcriptomics**](https://doi.org/10.1038/s41592-022-01409-2) — panorama comparativo das tecnologias de transcriptômica espacial e de suas resoluções, escalas e aplicações. [@Moses2022Museum] *(slide 57)*

### Livro e capítulo on-line {#livro-e-capitulo-on-line-aula-2}

- [**Biologia molecular da célula**](https://app.minhabiblioteca.com.br/books/9788582714232) — livro-texto de referência para os fundamentos de biologia celular e molecular abordados na aula. [@Alberts2017Biologia] *(slide 17)*

### Tutoriais e documentação {#tutoriais-e-documentacao-aula-2}

- [**Seurat — documentação e vinhetas**](https://satijalab.org/seurat/) — documentação oficial do pacote para controle de qualidade, análise, clusterização e exploração de dados de expressão gênica em célula única e no espaço. *(slide 13)*
- [**Seurat — Interaction Tips**](https://satijalab.org/seurat/archive/v4.3/interaction_vignette) — vinheta do Seurat 4.3 sobre identidades, metadados, seleção de células e inspeção de objetos. *(slide 14)*
- [**Understanding Seurat objects — simply explained!**](https://biostatsquid.com/seurat-objects-explained/) — explicação visual da estrutura interna de objetos Seurat e de seus principais componentes. *(slides 14 e 33)*
- [**Z-transformation**](http://www.statistics4u.info/fundstat_eng/ee_ztransform.html) — introdução à transformação em escore-z e à padronização de variáveis. *(slide 32)*
- [**What is Dimensionality Reduction? A Guide**](https://blog.roboflow.com/what-is-dimensionality-reduction/) — introdução conceitual à redução de dimensionalidade e às suas aplicações. *(slide 37)*
- [**RGraphSpace — Get started**](https://sysbiolab.github.io/RGraphSpace/articles/get-started.html) — guia inicial para representar redes e seus atributos gráficos com o pacote RGraphSpace. *(slide 94, hiperlink embutido)*
- [**PathwaySpace — Get started**](https://sysbiolab.github.io/PathwaySpace/articles/get-started.html) — guia inicial do pacote para projeção e visualização de sinais de redes em espaços bidimensionais. *(slides 107 a 109, hiperlink embutido)*
- [**Controle de qualidade, pré-processamento e clusterização espacial**](https://flaviogckessler.github.io/Curso_ST/vinhetas/Controle_de_qualidade_preprocessamento_clusterizacao_espacial.html) — vinheta prática da Aula 2 para preparar, avaliar e clusterizar dados de transcriptômica espacial. *(slide 5)*
- [**Visualização contínua com PathwaySpace**](https://flaviogckessler.github.io/Curso_ST/vinhetas/Visualizacao_Continua_PathwaySpace.html) — vinheta prática da Aula 2 para projetar e explorar sinais contínuos com PathwaySpace. *(slide 86)*

### Sites e repositórios {#sites-e-repositorios-aula-2}

- [**PathwaySpace**](https://sysbiolab.github.io/PathwaySpace/) — site oficial do pacote, com instalação, referência de funções e vinhetas. *(slides 84 e 85)*

## Referências {#referencias}

::: {#refs}
:::
