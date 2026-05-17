# PRD - LF PAK Equipamentos Industriais

## 1. Visao geral

Criar um novo projeto institucional e comercial para a LF PAK Equipamentos Industriais usando Laravel, Inertia.js com Vue, Tailwind CSS, Laravel Boost e PostgreSQL.

O projeto deve partir do template aprovado `phactorize`, preservando a identidade visual da LF PAK, os assets gerados, a estrutura de conteudo validada e o design system presente em `phactorize/design-system-branded.html`.

O foco principal da empresa deve ficar claro em toda a experiencia: automacao industrial aplicada a envasadoras, equipamentos de inicio e final de linha, PLC / CLP, paineis eletricos, retrofit, integracao de sistemas, manutencao industrial e suporte tecnico.

## 2. Objetivos do produto

- Apresentar a LF PAK como fornecedora tecnica de automacao industrial para processos mais eficientes, seguros e produtivos.
- Gerar contatos comerciais via telefone, WhatsApp e e-mail.
- Transformar o HTML estatico aprovado em uma base moderna, componentizada e facil de evoluir.
- Preservar o design aprovado no template `phactorize`, mantendo consistencia com o design system branded.
- Organizar o conteudo institucional da empresa em uma secao unica "Quem somos", incluindo descricao da empresa, missao, visao, valores e fluxo de atendimento.
- Preparar a base Laravel/Inertia para conteudo versionado em codigo inicialmente, com possibilidade futura de painel administrativo.

## 3. Stack tecnica

- Backend: Laravel
- Frontend: Inertia.js com Vue
- Estilizacao: Tailwind CSS
- Banco de dados: PostgreSQL
- Assistencia de desenvolvimento: Laravel Boost
- Assets de referencia: pacote exportado do template `phactorize`

## 4. Publico-alvo

- Industrias com linhas de envase, embalagem e final de linha.
- Empresas que precisam modernizar maquinas existentes.
- Operacoes industriais que utilizam PLC / CLP, sensores, inversores, IHMs, paineis eletricos e sistemas de controle.
- Gestores, engenheiros, equipes de manutencao e decisores de compra que buscam confiabilidade operacional.
- Industrias de cosmeticos, produtos de limpeza e higiene, perfumaria, farmaceutica e outros segmentos com processos repetitivos de dosagem, embalagem e movimentacao.

## 5. Identidade visual e design system

Usar obrigatoriamente os arquivos de logo fornecidos:

- Logo horizontal: `lfpack_logo_horizontal.png`
- Logo vertical: `lfpack_logo.png`

Nao substituir os logos por texto. Sempre usar as imagens oficiais.

Paleta principal:

- Azul primario: `#005B9F`
- Azul secundario: `#0077C3`
- Azul de destaque: `#0090E6`
- Cinza escuro: `#666666`
- Cinza medio: `#8C8C8C`
- Cinza claro: `#D9D9D9`
- Fundo neutro: `#F7F8FA`
- Texto principal: `#333333`
- Branco: `#FFFFFF`

O arquivo `phactorize/design-system-branded.html` deve ser usado como referencia para:

- Tipografia
- Cores e superficies
- Uso dos logos
- Botoes e estados de hover/focus
- Cards de servico
- Cards institucionais
- Grids responsivos
- Rodape
- Overlays azuis sobre imagens industriais
- Iconografia baseada no Font Awesome do template original, podendo ser migrada para uma biblioteca Vue se mantida equivalencia visual

## 6. Estrutura da home

A pagina inicial deve conter as secoes do HTML aprovado:

- Header fixo com barra superior de contatos
- Hero com imagem realista de ambiente industrial com envasadora
- Card de destaque sobre controle industrial e continuidade operacional
- Diferenciais
- Solucoes
- Aplicacoes industriais
- Como trabalhamos
- Quem somos
- Chamada para contato
- Rodape com links rapidos e contatos
- Botao flutuante de WhatsApp

## 7. Conteudo aprovado

### 7.1 Hero

Titulo:

`Automacao industrial para processos mais eficientes, seguros e produtivos`

Texto:

`A LF PAK desenvolve solucoes em PLC, integracao de sistemas e modernizacao de maquinas para empresas que precisam de controle, confiabilidade e performance na producao.`

CTAs:

- Solicitar orcamento
- Conhecer solucoes

### 7.2 Destaque do hero

Titulo:

`Controle industrial com foco em continuidade operacional`

Texto:

`Projetos orientados a reduzir paradas, organizar comandos e dar mais previsibilidade ao processo produtivo.`

### 7.3 Diferenciais

- Projetos sob medida
- Especialistas em PLC / CLP
- Modernizacao de maquinas
- Integracao industrial
- Suporte tecnico
- Produtividade e seguranca

Os cards devem manter altura padronizada e alinhamento correto em desktop, tablet e mobile.

### 7.4 Solucoes

- Programacao de PLC / CLP
- Paineis eletricos
- Automacao de maquinas
- Retrofit de equipamentos
- Sensores, inversores e IHMs
- Diagnostico e manutencao

As imagens dos cards devem ser realistas e priorizar envasadoras, linha final, equipamentos industriais, paineis eletricos e manutencao tecnica.

### 7.5 Aplicacoes industriais

- Linhas de producao
- Maquinas de embalagem
- Esteiras transportadoras
- Sistemas de envase
- Controle de motores
- Processos repetitivos
- Celulas industriais
- Monitoramento

### 7.6 Processo de trabalho

- Diagnostico tecnico
- Planejamento da solucao
- Implementacao e testes
- Entrega e suporte

### 7.7 Quem somos

Texto institucional:

`A LF PAK e uma empresa voltada a automacao de processos de inicio e final de linha de producao, servicos de manutencao industrial, comercio de pecas, usinagem, solda e maquinas industriais.`

`Atua em Uberaba e regiao, com especialidade em processos de final de linha para operacoes que precisam de produtividade, repetibilidade e suporte tecnico.`

`A empresa atende industrias de cosmeticos, produtos de limpeza e higiene, perfumaria, farmaceutica, entre outras.`

Blocos de apoio:

- Inicio e final de linha
- Uberaba e regiao
- Segmentos atendidos

### 7.8 Missao, visao e valores

Missao:

`Criar sistemas e solucoes em automacao industrial que promovam a melhoria da produtividade, a reducao de custos e a qualidade das operacoes e dos produtos de nossos clientes.`

Visao:

`Ser reconhecida como empresa de automacao referencia em prover solucoes integradas as necessidades das industrias, com diferencial tecnico e operacional.`

Valores:

- Inovacao
- Melhoria continua
- Integridade
- Etica
- Comprometimento

### 7.9 Fluxo de atendimento

- Consultoria personalizada
- Orcamento
- Fabricacao
- Manutencao e assistencia

O fluxo deve ser implementado como HTML/CSS responsivo, nao como imagem fixa, para preservar legibilidade, acessibilidade e adaptacao a mobile.

## 8. Contatos e links

Telefone:

- Texto: `(34) 3322-2612`
- Link: `tel:+553433222612`

WhatsApp:

- Texto: `(34) 98817-6301`
- Link: `https://wa.me/5534988176301`

E-mails:

- Comercial: `comercial@lfpak.com.br`
- Assistencia tecnica: `assistenciatecnica@lfpak.com.br`
- Financeiro: `financeiro@lfpak.com.br`

Links de e-mail recomendados:

- `mailto:comercial@lfpak.com.br?subject=Contato%20comercial`
- `mailto:assistenciatecnica@lfpak.com.br?subject=Solicitacao%20de%20assistencia%20tecnica`
- `mailto:financeiro@lfpak.com.br?subject=Contato%20financeiro`

No header, exibir apenas o e-mail comercial para evitar quebra visual. No rodape, cada e-mail deve aparecer em linha propria.

Localidade atual:

- `Uberaba / MG`

## 9. Requisitos funcionais

- O usuario deve conseguir navegar pelas secoes via menu.
- O header deve permanecer fixo apos rolagem.
- Links ancora devem respeitar o offset do header fixo sem esconder titulos.
- O botao flutuante de WhatsApp deve abrir conversa em nova aba.
- Links de telefone e e-mail devem usar protocolos nativos (`tel:` e `mailto:`).
- A pagina deve carregar corretamente usando assets locais.
- O layout deve ser responsivo nos principais viewports desktop, tablet e mobile.
- Cards de diferenciais, solucoes, missao/visao/valores e fluxo de atendimento devem manter alinhamento e altura visual consistente.
- A secao "Quem somos" deve ser editavel via dados estruturados no Vue, mesmo que a primeira versao use conteudo estatico.

## 10. Requisitos nao funcionais

- Performance: otimizar imagens e entregar assets com cache adequado.
- Acessibilidade: usar textos alternativos em imagens, estados de foco visiveis, contraste adequado e conteudo textual real em vez de textos dentro de imagem.
- SEO: estruturar headings, metadados, descricao da empresa e textos focados em automacao industrial, envasadoras e final de linha.
- Manutenibilidade: componentizar secoes em Vue com props ou dados configuraveis.
- Consistencia visual: seguir `design-system-branded.html` e `color_palette.json`.
- Compatibilidade: validar em desktop, tablet e mobile.

## 11. Modelo de dados inicial sugerido

Mesmo que a primeira versao seja majoritariamente institucional, preparar o PostgreSQL para evolucao:

- `pages`: paginas editaveis como home, sobre e contato.
- `sections`: blocos de conteudo ordenaveis por pagina.
- `services`: solucoes oferecidas com titulo, subtitulo, descricao, imagem e ordem.
- `applications`: aplicacoes industriais com titulo, descricao, icone e ordem.
- `features`: diferenciais com titulo, descricao, icone e ordem.
- `process_steps`: etapas do processo de trabalho.
- `service_flow_steps`: etapas do fluxo de atendimento.
- `institutional_values`: missao, visao e valores.
- `contacts`: telefones, WhatsApp, e-mails e localidade.
- `media`: imagens usadas nas secoes.

A primeira entrega pode usar dados estaticos em Vue ou seeders, deixando o banco preparado para administracao futura.

## 12. Componentizacao recomendada em Inertia/Vue

- `AppLayout`
- `SiteHeader`
- `TopContactBar`
- `HeroSection`
- `HeroFeatureCard`
- `FeatureGrid`
- `FeatureCard`
- `ServicesSection`
- `ServiceCard`
- `ApplicationsSection`
- `ApplicationCard`
- `ProcessSection`
- `ProcessCard`
- `AboutSection`
- `InstitutionalCards`
- `ServiceFlow`
- `CtaSection`
- `SiteFooter`
- `FloatingWhatsappButton`

Os dados dos cards devem ficar em arrays/objetos para facilitar edicao e futura migracao para banco.

## 13. Tailwind e tokens

Configurar tokens do Tailwind com a paleta LF PAK:

- `brand.primary`: `#005B9F`
- `brand.secondary`: `#0077C3`
- `brand.accent`: `#0090E6`
- `brand.gray.dark`: `#666666`
- `brand.gray.medium`: `#8C8C8C`
- `brand.gray.light`: `#D9D9D9`
- `brand.background`: `#F7F8FA`
- `brand.text`: `#333333`

Preservar o visual industrial limpo: azul institucional, superficies brancas, fundos claros, overlays azuis em imagens e cards com hierarquia forte.

## 14. Assets de referencia

Assets principais do pacote exportado:

- `landing_page_phactorize.html`
- `phactorize/design-system-branded.html`
- `phactorize/assets/lfpak_envasadora_hero_bg.jpg`
- `phactorize/assets/lfpak_envasadora_card.jpg`
- `phactorize/assets/lfpak_service_plc_clp.jpg`
- `phactorize/assets/lfpak_service_paineis_eletricos.jpg`
- `phactorize/assets/lfpak_service_automacao_maquinas.jpg`
- `phactorize/assets/lfpak_service_retrofit_equipamentos.jpg`
- `phactorize/assets/lfpak_service_sensores_ihm_inversores.jpg`
- `phactorize/assets/lfpak_service_diagnostico_manutencao.jpg`
- `phactorize/assets/lfpak_favicon_gears.png`
- `phactorize/assets/lfpak_apple_touch_gears.png`
- `lfpack_logo.png`
- `lfpack_logo_horizontal.png`
- `color_palette.json`
- `AGENTS.md`

## 15. Criterios de aceite

- A home em Laravel/Inertia reproduz a estrutura visual e o conteudo aprovado no HTML `phactorize`.
- Logos oficiais aparecem como imagem, nunca como texto.
- Header fixo funciona em desktop e mobile.
- Cliques no menu rolam para a secao correta sem esconder os titulos atras do header.
- Cards permanecem alinhados e com padrao de altura em todos os viewports configurados.
- Contatos usam links corretos de telefone, WhatsApp e e-mail.
- Header exibe apenas o e-mail comercial.
- O rodape exibe cada e-mail em linha propria.
- As imagens de solucoes representam envasadoras, linhas finais e automacao industrial realista.
- A secao "Quem somos" exibe descricao, missao, visao, valores e fluxo de atendimento sem depender das imagens originais enviadas pela cliente.
- O projeto usa tokens de cor alinhados a `color_palette.json`.
- O design system exportado esta disponivel para consulta e configuracao no Laravel Boost.

## 16. Pendencias conhecidas

- Confirmar se o cliente deseja fotos reais das maquinas ou manter imagens realistas geradas.
- Definir se havera painel administrativo na primeira versao ou apenas conteudo versionado no codigo.
- Confirmar textos finais de SEO e metadados quando houver mais informacoes institucionais.
