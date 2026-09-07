# Análise de Dados de Transcriptômica Espacial

Este repositório reúne os materiais do curso **Análise de Dados de Transcriptômica Espacial**, dedicado aos fundamentos das tecnologias de transcriptômica de alta resolução e às estratégias de análise de dados espaciais. O curso combina aulas expositivas e atividades práticas em R, com ênfase em dados gerados pela plataforma Visium.

## Objetivos

Ao final do curso, espera-se que as pessoas participantes sejam capazes de:

-   compreender os conceitos fundamentais da transcriptômica espacial e suas aplicações nas Ciências da Saúde;
-   reconhecer as principais plataformas e a estrutura dos dados de transcriptômica espacial;
-   realizar etapas de controle de qualidade, normalização e redução de dimensionalidade com o pacote Seurat;
-   conhecer abordagens para deconvolução, comunicação celular, visualização contínua de sinal e outras análises secundárias;
-   discutir possibilidades de aplicação dessas técnicas em seus próprios contextos de pesquisa.

## Conteúdo programático

### 1. Introdução à transcriptômica espacial

-   fundamentos teóricos;
-   plataformas disponíveis;
-   estrutura dos dados.

### 2. Pré-processamento de dados

-   controle de qualidade;
-   normalização;
-   redução de dimensionalidade;
-   uso do pacote Seurat em R.

### 3. Análise de dados em transcriptômica espacial

-   técnicas de deconvolução;
-   análise de comunicação celular;
-   visualização contínua de sinal;
-   outras análises secundárias.

## Metodologia

O curso tem caráter teórico-prático. As exposições conceituais são seguidas de atividades práticas, tutoriais e exemplos desenvolvidos em R. As análises têm foco principal em dados de transcriptômica espacial produzidos pela plataforma Visium.

## Carga horária e programação

A carga horária total é de **8 horas**, distribuídas da seguinte forma:

| Data                  | Horário     |
|-----------------------|-------------|
| 07/09 (segunda-feira) | 18h30–20h30 |
| 08/09 (terça-feira)   | 18h30–21h30 |
| 09/09 (quarta-feira)  | 18h30–21h30 |

## Pré-requisitos

São recomendados conhecimentos básicos de biologia molecular e de tecnologias de sequenciamento. Experiência prévia com alguma linguagem de programação é desejável, mas não obrigatória.

## Vinhetas

1.  [Configuração do ambiente RStudio](https://flaviogckessler.github.io/Curso_ST/vinhetas/DOC1_Configuracao_do_ambiente_RStudio.html)
2.  [Controle de qualidade, pré-processamento e clusterização de dados espaciais](https://flaviogckessler.github.io/Curso_ST/vinhetas/Controle_de_qualidade_preprocessamento_clusterizacao_espacial.html) — Aula 2
3.  [Visualização contínua de dados espaciais com PathwaySpace](https://flaviogckessler.github.io/Curso_ST/vinhetas/Visualizacao_Continua_PathwaySpace.html) — Aula 2
4.  [Deconvolução com RCTD](https://flaviogckessler.github.io/Curso_ST/vinhetas/RCTD_Deconvolution_stxbrain.html)
5.  [Comunicação celular](https://flaviogckessler.github.io/Curso_ST/vinhetas/CellChat_Comunicacao_Celular_PathwaySpace.html)

## Leituras recomendadas

Os artigos científicos, capítulos, tutoriais, vídeos e repositórios citados nas apresentações estão reunidos em uma página pesquisável, organizada por tipo de material e vinculada aos slides correspondentes da Aula 1.

-   [Explorar as leituras recomendadas no GitHub Pages](https://flaviogckessler.github.io/Curso_ST/apresentacoes/LEITURA_RECOMENDADA.html)
-   [Consultar a lista em Markdown](apresentacoes/LEITURA_RECOMENDADA.md)

## Ministrante

**Flávio Gabriel Carazza-Kessler**

-   [Currículo Lattes](http://lattes.cnpq.br/0370990742893359)
-   [Google Scholar](https://scholar.google.com/citations?user=DYrSfHYAAAAJ&hl=en)
-   [LinkedIn](https://www.linkedin.com/in/flaviogckessler)
-   Contato: [flaviokessler\@ufpr.br](mailto:flaviokessler@ufpr.br)

## Histórico

Esse curso tem origem em um curso entitulado "Análise de Dados de Transcriptômica Single-Cell e Espacial" ministrado pela Dra. Carolina Saibro-Girardi e por mim, Flávio, durante o congresso X-meeting 2026. Lá, fui gentilmente convidado para ministrar o curso novamente. Dessa vez, porém, focado mais em transcriptômica espacial e (infelizmente) ministrado apenas por mim.

De toda maneira, a estrutura do curso, apresentações e códigos são oriundos (parcial ou majoritarimente) da primeira versão do curso. Por essa razão, alguns documentos contam com o nome da Dra. Carol.

*Deixo aqui meu agradecimento à Carol, querida amiga, por primeiro ter me convidado para participar da primeira versão como também por compartilhar o material do curso.*

## Licenças

O conteúdo de texto deste curso está disponível sob a licença [Creative Commons Atribuição-NãoComercial 4.0 Internacional (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/deed.pt-br). Os códigos-fonte estão disponíveis sob a licença MIT. Consulte o arquivo [LICENSE.md](LICENSE.md) para os termos aplicáveis.
