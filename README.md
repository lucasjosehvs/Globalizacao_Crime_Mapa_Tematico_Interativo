<div align="center">

# 🌐 Globalização do Crime e das Atividades Ilegais

### Mapa temático interativo sobre fixos e fluxos do crime transnacional

![HTML5](https://img.shields.io/badge/HTML5-single--file-e34f26?logo=html5&logoColor=white)
![D3.js](https://img.shields.io/badge/D3.js-v7.8.5-f9a03c?logo=d3dotjs&logoColor=white)
![TopoJSON](https://img.shields.io/badge/topojson--client-v3.1.0-2f7fc1)
![Dados](https://img.shields.io/badge/dados-UNODC%20%C2%B7%20GI--TOC-7e63c9)
![Status](https://img.shields.io/badge/depend%C3%AAncias-nenhuma-3aa86b)

**Seminário Geopolítica do Poder · Geografia · 4º bimestre de 2026**
CEFET-MG, Campus Divinópolis · Curso Técnico Integrado

</div>

---

## Sumário

1. [Sobre o projeto](#1-sobre-o-projeto)
2. [Contexto acadêmico](#2-contexto-acadêmico)
3. [Funcionalidades](#3-funcionalidades)
4. [Estrutura da narrativa](#4-estrutura-da-narrativa)
5. [Rotas representadas](#5-rotas-representadas)
6. [Dados e metodologia](#6-dados-e-metodologia)
7. [Como executar](#7-como-executar)
8. [Arquitetura técnica](#8-arquitetura-técnica)
9. [Limitações e ressalvas](#9-limitações-e-ressalvas)
10. [Referências](#10-referências)
11. [Autoria e licença](#11-autoria-e-licença)

---

## 1. Sobre o projeto

Este repositório contém o **produto final** do Grupo 1 no Seminário *Geopolítica do Poder*: um **mapa temático comentado e interativo**, em formato de globo, que representa espacialmente a expansão das redes criminosas no contexto da globalização.

O mapa articula dois conceitos centrais da Geografia:

- **Fixos:** infraestruturas que sustentam os fluxos, como portos, fronteiras, zonas econômicas especiais e complexos fortificados.
- **Fluxos:** o que circula por essas infraestruturas, como cocaína, opiáceos, pessoas, capitais e informações.

A tese que organiza o trabalho é que as mesmas redes técnicas que viabilizam o comércio lícito (contêineres, sistema financeiro, internet) são aproveitadas por redes ilícitas, e que o crime se adapta: **quando uma rota é fechada, outra se abre**.

## 2. Contexto acadêmico

| Item | Descrição |
|---|---|
| **Componente curricular** | Geografia |
| **Instituição** | CEFET-MG, Campus Divinópolis (Campus V) |
| **Curso** | Técnico Integrado |
| **Professora** | Samara Mirelly da Silva |
| **Atividade** | Seminário *Geopolítica do Poder* (4º bimestre de 2026) |
| **Tema do Grupo 1** | Globalização do crime e das atividades ilegais |
| **Modalidade do produto** | Mapa temático comentado |

**Questão norteadora (proposta no enunciado):**

> Por que a globalização, ao mesmo tempo em que amplia a circulação de pessoas, mercadorias e informações, também favorece a expansão das redes criminosas internacionais?

**Escopo do tema, conforme o enunciado:** tráfico de drogas, armas e pessoas, contrabando e lavagem de dinheiro, com atuação transnacional, principais agentes e impactos sociais, econômicos e territoriais.

> O mapa aprofunda, em especial, o tráfico de **cocaína**, de **ópio e sintéticas**, de **pessoas** (incluindo os centros de golpe digitais) e a **lavagem de dinheiro**. Armas e contrabando em geral são abordados apenas de forma transversal, e não possuem camada própria.

## 3. Funcionalidades

- **Globo interativo** em projeção ortográfica: arraste para girar e use a roda do mouse (ou o gesto de pinça) para aproximar.
- **Narrativa guiada em 11 slides**, com voo animado da câmera até a região de cada tema.
- **Dossiê por país:** clique em qualquer país (ou busque pelo nome) para ver posição no ranking, as quatro pontuações do Índice GI-TOC, indicadores comparativos, papel nos fluxos ilegais e marcos recentes.
- **Camadas ativáveis:** rotas da cocaína, do ópio/sintéticas, do tráfico de pessoas e o mapa coroplético do Índice.
- **Rotas animadas** (partículas ao longo dos arcos), com sub-rotas de deslocamento em traço largo.
- **Painel por rota:** clique em um arco para ler explicação, **fixos**, **fluxos** e **dinâmica recente**, com fontes numeradas.
- **Citações numeradas** no texto, ligadas à lista de referências no último slide.
- **Responsivo:** layout adaptado para telas estreitas (largura menor que 800 px).

### Controles

| Ação | Como fazer |
|---|---|
| Girar o globo | Arrastar |
| Aproximar / afastar | Roda do mouse |
| Próximo / anterior slide | Botões `→` `←` ou teclas de seta |
| Voltar do dossiê ao slide | Botão "Voltar aos slides" ou tecla `Esc` |
| Ativar / desativar camadas | Botões Cocaína, Ópio/sintéticas, Pessoas, Índice |
| Buscar país | Campo "Buscar país…" |
| Voltar à tela inicial | Botão ⌂ |

## 4. Estrutura da narrativa

| # | Slide | Foco |
|---|---|---|
| 0 | **Introdução** | Pergunta norteadora e instruções de uso |
| 1 | **Conceitos** | Castells (redes), Milton Santos (meio técnico-científico-informacional) e Paoli (crime organizado) |
| 2 | **1 · Origem da cocaína** | Colômbia, Peru e Bolívia: concentração da oferta |
| 3 | **2 · Rotas da cocaína** | Portos, contêineres e deslocamento das rotas |
| 4 | **3 · Ópio e sintéticas** | Do Afeganistão a Mianmar; rotas dos Bálcãs, do Norte e do Sul |
| 5 | **4 · Tráfico de pessoas** | Panorama global e perfil das vítimas |
| 6 | **5 · Mapa do crime organizado** | Índice GI-TOC 2025 em mapa coroplético |
| 7 | **6 · Centros de golpe** | Tráfico para criminalidade forçada no Sudeste Asiático |
| 8 | **7 · Dinheiro** | Lavagem de dinheiro |
| 9 | **Síntese** | Resposta à questão norteadora e impactos sociais, econômicos e territoriais |
| 10 | **Referências** | Fontes utilizadas |

## 5. Rotas representadas

Cada rota possui descrição, fixos, fluxos e dinâmica recente. As rotas marcadas como *sub-rota* **não representam fluxo de carga**, e sim deslocamentos estratégicos (mudança de ponto de entrada ou de local de operação).

| Tema | Rota | Tipo |
|---|---|---|
| Cocaína | Pacífico e Caribe → América do Norte | Rota |
| Cocaína | Equador → Antuérpia e Roterdã | Rota |
| Cocaína | Brasil → Península Ibérica | Rota |
| Cocaína | Brasil → África Ocidental | Rota |
| Cocaína | Pacífico → Oceania | Rota |
| Cocaína | Antuérpia → portos menores | Sub-rota (deslocamento) |
| Ópio | Rota dos Bálcãs | Rota |
| Ópio | Rota do Norte | Rota |
| Ópio | Rota do Sul (Oceano Índico) | Rota |
| Ópio | Mianmar → Europa | Sub-rota emergente |
| Pessoas | África Subsaariana → Europa | Rota |
| Pessoas | China → Mianmar (centros de golpe) | Rota |
| Pessoas | Etiópia → Mianmar | Rota |
| Pessoas | Deslocamento dos centros de golpe | Sub-rota (deslocamento) |

> ⚠️ Os arcos são **traçados esquemáticos**, não percursos exatos. O painel de cada rota informa isso explicitamente.

## 6. Dados e metodologia

### 6.1 Fontes principais

| Fonte | Uso no mapa |
|---|---|
| **GI-TOC, Global Organized Crime Index 2025** | Pontuações de criminalidade (mercados e atores) e resiliência de 193 países; coroplético; ranking |
| **UNODC, World Drug Report 2026** | Usuários, produção de cocaína, países de partida, ópio e sintéticas |
| **UNODC, Global Report on Trafficking in Persons 2024** | Vítimas detectadas, perfil e criminalidade forçada |
| **UNODC, Myanmar Opium Survey 2025** e **Afghanistan Opium Survey 2025** | Área, produção, preço e renda do ópio |
| **UNODC e OHCHR (ACNUDH)** | Centros de golpe, lucros e estimativas de vítimas |
| **Castells; Milton Santos; Paoli** | Base conceitual |
| Reportagens (VRT NWS, Brussels Times, bne IntelliNews, Dawn, DVB, Kun.uz, InSight Crime) | Dados recentes e comparações por país |

A lista completa, com 24 entradas, está na [seção 10](#10-referências) e no último slide do mapa.

### 6.2 Como o Índice GI-TOC é usado

- O Índice atribui notas de **1 a 10** a 193 países. A nota de **criminalidade** é a média das notas de **mercados criminosos** e de **atores criminosos**; a **resiliência** mede a capacidade do Estado e da sociedade de responder.
- No arquivo, **165 países** têm as cinco colunas (criminalidade, mercados, atores, resiliência e variação 2023–2025) e geram dossiê completo. Outros **28 países** (os de menor pontuação) entram apenas com a nota de criminalidade, para que o **ranking de 193** seja calculado corretamente.
- A cor do mapa varia em escala sequencial de amarelo a vermelho-escuro conforme a criminalidade.
- Referências globais usadas nos comparativos: média de criminalidade **5,08** e média de resiliência **4,78**.

### 6.3 Indicadores derivados pelo grupo

Para cada país, o dossiê calcula diferenças simples a partir das notas do GI-TOC:

- variação 2023–2025;
- criminalidade em relação à média mundial;
- resiliência em relação à média mundial;
- **lacuna** resiliência − criminalidade.

O texto "Leitura do grupo" é uma **regra de classificação própria** do grupo (por exemplo, criminalidade ≥ 6 com resiliência < 5 sugere pouca capacidade de resposta do Estado). **Não** é uma classificação oficial do GI-TOC.

### 6.4 Exemplos de dados verificados

Valores conferidos nas publicações originais ou em sua cobertura jornalística, em novembro de 2026:

| Dado | Valor | Fonte |
|---|---|---|
| 1º, 2º e 3º no Índice 2025 | Mianmar (8,08), Colômbia (7,82), México (7,68) | GI-TOC 2025 |
| Brasil no Índice 2025 | 7,07 (14º) | GI-TOC 2025 |
| Usuários de drogas em 2024 | 331 milhões (6,2% da população de 15 a 64 anos) | UNODC, WDR 2026 |
| Produção de cocaína em 2024 | cerca de 4.100 t (pureza total), mais de quatro vezes a de dez anos antes | UNODC, WDR 2026 |
| Ópio em Mianmar, 2025 | 53.100 ha (+17%) e cerca de 1.010 t | UNODC, Myanmar Opium Survey 2025 |
| Ópio no Afeganistão, 2025 | 10.200 ha (−20%) e 296 t (−32%) | UNODC, Afghanistan Opium Survey 2025 |
| Vítimas de tráfico detectadas | +25% em 2022 vs. 2019; 38% crianças; 61% mulheres e meninas | UNODC, GLOTIP 2024 |
| Criminalidade forçada | de 1% (2016) a 8% (2022) das vítimas detectadas | UNODC, GLOTIP 2024 |

## 7. Como executar

O projeto é um **arquivo único** (`index.html`), sem build, sem instalação e sem dependências externas: D3.js e topojson-client estão embutidos, assim como a geometria dos países.

**Opção 1: abrir direto no navegador**

```bash
git clone https://github.com/<usuario>/<repositorio>.git
cd <repositorio>
# abra index.html no navegador (duplo clique ou arraste para a janela)
```

**Opção 2: servidor local (opcional)**

```bash
python3 -m http.server 8000
# acesse http://localhost:8000
```

**Opção 3: GitHub Pages**

1. Em *Settings → Pages*, escolha a branch principal e a pasta `/ (root)`.
2. Aguarde a publicação e acesse o endereço gerado pelo GitHub.

> Navegadores modernos (Chrome, Edge, Firefox, Safari) são suficientes. A experiência foi pensada para desktop e celular.

## 8. Arquitetura técnica

```text
.
├── index.html     # produto completo: estilos, dados, lógica e bibliotecas embutidas
└── README.md
```

Dentro do `index.html`, o código se organiza assim:

| Bloco | Conteúdo |
|---|---|
| **Estilos (CSS)** | Globo, painéis, legenda, animações (arcos, pulsos, tela de abertura) e *media query* para telas estreitas |
| **Bibliotecas** | D3.js 7.8.5 e topojson-client 3.1.0 |
| **Geometria** | Países em TopoJSON e tabela de nomes em português |
| **Dados** | `RAW` e `EXTRA` (Índice GI-TOC), `R` (referências), `N` e `CUR` (textos por país), `ROUTES` (rotas) e `S` (slides) |
| **Renderização** | Projeção `d3.geoOrthographic`, `d3.geoPath`, escala de cor sequencial e camadas SVG |
| **Interação** | Arrastar, zoom, busca, teclado, voo animado entre pontos e animação das partículas via `d3.timer` |

**Para atualizar dados ou textos**, edite as constantes do bloco de dados: notas do Índice em `RAW`, referências em `R`, textos por país em `N` e `CUR`, rotas em `ROUTES` e slides em `S`. As citações no formato `[n]` apontam para as chaves de `R`.

## 9. Limitações e ressalvas

Esta seção existe por rigor acadêmico. Convém apresentá-la junto com o produto.

1. **O Índice GI-TOC não é estatística oficial de crime.** É uma ferramenta analítica baseada em avaliação de especialistas, dados e análise. As notas medem a **força das redes criminosas e a capacidade de resposta**, e não o número de crimes nem a segurança pública cotidiana. Comparações entre países devem ser lidas com essa cautela.
2. **Rotas esquemáticas.** Os arcos ligam pontos de referência para indicar sentido e escala geográfica; não reproduzem trajetos reais.
3. **Estimativas com incerteza.** Produção de ópio e de cocaína, lucros dos centros de golpe e número de vítimas são estimativas, algumas com faixa de variação ampla. Os valores do mapa são pontuais e devem ser citados com sua fonte e ano.
4. **Datas diferentes.** Os dados têm anos distintos (2024 para produção de cocaína, 2022 para vítimas de tráfico, 2025 para ópio e Índice). A descrição de partes das rotas do ópio se apoia em publicações mais antigas da UNODC e do GI-TOC (2010, 2015, 2016), que podem não refletir a situação atual.
5. **Cobertura da Colômbia.** A estimativa de 2,6 mil toneladas de cocaína potencial (levantamento de 2023) foi contestada pelo governo colombiano, e o levantamento de 2024 não divulgou estimativa de produção. O mapa registra esse contexto no dossiê do país.
6. **Fontes jornalísticas.** Parte dos dados recentes (por exemplo, apreensões em Antuérpia e posições nacionais no Índice) vem de reportagens. O ideal é substituí-las por relatórios primários quando disponíveis.
7. **Base teórica.** Castells, Milton Santos e Paoli são citados de forma conceitual, **sem indicação de páginas**; o relatório escrito deve acrescentá-las.
8. **Lacunas temáticas.** Tráfico de armas e contrabando em geral não têm camada própria, embora façam parte do escopo do tema.
9. **Geometria simplificada.** O mapa de fundo é uma simplificação cartográfica: territórios pequenos podem ter representação aproximada, e alguns não possuem pontuação no Índice (o dossiê avisa quando isso ocorre).

## 10. Referências

> Lista conforme consta no último slide do mapa (formato próximo à ABNT). Para o relatório final, complete com a data de acesso de cada fonte online.

1. UNODC. **World Drug Report 2026**. Viena: UNODC, 2026.
2. UNODC. **Global Report on Trafficking in Persons 2024**. Viena: UNODC, 2024.
3. GI-TOC. **Global Organized Crime Index 2025**. Genebra: GI-TOC, nov. 2025.
4. UNODC. **Money Laundering – Overview**.
5. UNRIC. **Drug use in Europe – World Drug Report 2026**.
6. VRT NWS. **55 tonnes of cocaine seized at the port of Antwerp in 2025**. 21 jan. 2026.
7. CASTELLS, M. **Fim de Milênio**. São Paulo: Paz e Terra, 1999.
8. SANTOS, M. **A Natureza do Espaço**. São Paulo: Edusp, 2002.
9. PAOLI, L. (Org.). **The Oxford Handbook of Organized Crime**. Oxford: OUP, 2014.
10. UNODC. **Colombia: Potential cocaine production increased by 53 per cent in 2023, according to new UNODC survey**. Bogotá, 18 out. 2024.
11. UNODC. **Myanmar Opium Survey 2025: Cultivation, Production and Implications**. Bangkok, 3 dez. 2025.
12. UNODC. **Afghanistan Opium Survey 2025**. Viena: UNODC, nov. 2025.
13. UNODC. **Afghan Opiate Trafficking through the Southern Route**. Viena: UNODC, 2015.
14. UNODC. **Central Asia – drug trafficking** (cita World Drug Report 2016); GI-TOC. **The Afghan opiate trade and Africa: a baseline assessment**, 2010.
15. UNODC. **Inflection Point: Global Implications of Scam Centres, Underground Banking and Illicit Online Marketplaces in South-East Asia**. Bangkok, abr. 2025.
16. ONU, Escritório de Direitos Humanos (OHCHR). **Online scam operations and trafficking into forced criminality in Southeast Asia**. 2023.
17. BRUSSELS TIMES. **Over a quarter of cocaine seized in Latin American ports destined for Antwerp**.
18. bne IntelliNews. **Turkey world's 10th most criminalised country**. 19 nov. 2025.
19. DVB. **Myanmar ranked number one in Global Organized Crime Index** (edição 2023).
20. KUN.UZ. **Uzbekistan ranks below global average for organized crime**. 7 jul. 2026.
21. DAWN. **Asian crime syndicates expanding globally (UNODC)**. 22 abr. 2025.
22. INSIGHT CRIME. **Can a New President's Hard-Line Approach Stop the Spread of Coca in Colombia?** 2026.
23. BRUSSELS TIMES. **Drop in cocaine seizures but more cannabis found at Belgian ports**. 2026.
24. ACNUDH/OHCHR. **A wicked problem** (tráfico de pessoas para centros de golpe). Genebra, 20 fev. 2026.

## 11. Autoria e licença

**Autoria:** Grupo 1, Seminário *Geopolítica do Poder*, Geografia, 2º ano do Curso Técnico Integrado, CEFET-MG, Campus Divinópolis, 2026.

**Integrantes:** _preencher com os nomes do grupo_

**Orientação:** Profa. Samara Mirelly da Silva

**Licença:** _definir antes de publicar_ (sugestão: [MIT](https://choosealicense.com/licenses/mit/) para o código; [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.pt-br) para o conteúdo autoral).

**Bibliotecas de terceiros:** [D3.js](https://d3js.org/) (ISC) e [topojson-client](https://github.com/topojson/topojson-client) (ISC), embutidas no arquivo.

**Como citar:**

> GRUPO 1. **Globalização do crime e das atividades ilegais: mapa temático interativo**. Divinópolis: CEFET-MG, 2026. Trabalho de Geografia (Seminário Geopolítica do Poder).

---

<div align="center">

*Os dados refletem as publicações disponíveis até novembro de 2026.*

</div>
