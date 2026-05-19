# PRD - LF PAK Equipamentos Industriais

## 1. Visao geral

Criar um novo projeto institucional e comercial para a LF PAK Equipamentos Industriais usando Laravel, Inertia.js com Vue, Tailwind CSS, Laravel Boost e PostgreSQL.

O projeto deve partir da landing page aprovada no template `phactorize`, preservando a identidade visual da LF PAK, os assets gerados, a estrutura de conteudo validada e o design system presente em `phactorize/design-system-branded.html`.

O foco principal da empresa deve ficar claro em toda a experiencia: automacao industrial aplicada a envasadoras, produtos de inicio e final de linha, PLC / CLP, paineis eletricos, retrofit, integracao de sistemas, manutencao industrial e suporte tecnico.

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
- Processo tecnico de trabalho
- Quem somos
- Chamada para contato
- Rodape com links rapidos e contatos

## 7. Conteudo aprovado

### Header

Contatos visiveis no topo:

- Telefone: `(34) 3322-2612`
- WhatsApp: `(34) 98817-6301`
- E-mail principal no header: `comercial@lfpak.com.br`

Todos os contatos devem ter links funcionais:

- `tel:+553433222612`
- `https://wa.me/5534988176301`
- `mailto:comercial@lfpak.com.br?subject=Contato%20comercial`

### Hero

Titulo:

`Automacao industrial para processos mais eficientes, seguros e produtivos`

Texto:

`A LF PAK desenvolve solucoes em PLC, integracao de sistemas e modernizacao de maquinas para empresas que precisam de controle, confiabilidade e performance na producao.`

CTA principal:

`Solicitar orcamento`

CTA secundario:

`Conhecer solucoes`

Imagem de fundo:

- `phactorize/assets/lfpak_envasadora_hero_bg.jpg`

Imagem do card inicial:

- `phactorize/assets/lfpak_hero_card_envasadora_cliente.png`
- Descricao: envasadora de perfumes LF PAK com 16 bicos em ambiente industrial.

Card do hero:

- Titulo: `Controle industrial com foco em continuidade operacional`
- Texto: `Projetos orientados a reduzir paradas, organizar comandos e dar mais previsibilidade ao processo produtivo.`

### Diferenciais

Cards de diferenciais:

- Engenharia aplicada a producao
- Especialistas em PLC / CLP
- Modernizacao de maquinas
- Integracao industrial
- Suporte tecnico
- Produtividade e seguranca

### Solucoes

Lista de solucoes:

- Programacao de PLC / CLP
- Paineis eletricos
- Automacao de maquinas
- Retrofit de equipamentos
- Sensores, inversores e IHMs
- Diagnostico e manutencao

As imagens dos cards de solucoes devem ser realistas e alinhadas ao foco de envasadoras e final de linha. Os cards devem manter largura consistente em todos os viewports e altura padronizada.

Assets usados:

- `phactorize/assets/lfpak_service_plc_clp.jpg`
- `phactorize/assets/lfpak_service_paineis_eletricos.jpg`
- `phactorize/assets/lfpak_service_automacao_maquinas.jpg`
- `phactorize/assets/lfpak_service_retrofit_equipamentos.jpg`
- `phactorize/assets/lfpak_service_sensores_ihm_inversores.jpg`
- `phactorize/assets/lfpak_service_diagnostico_manutencao.jpg`

### Aplicacoes

Aplicacoes industriais:

- Linhas de producao
- Maquinas de embalagem
- Esteiras transportadoras
- Sistemas de envase
- Controle de motores
- Processos repetitivos
- Celulas industriais
- Monitoramento

### Processo tecnico

Etapas:

- Diagnostico tecnico
- Planejamento da solucao
- Implementacao e testes
- Entrega e suporte

### Quem somos

Usar uma unica secao "Quem somos" para agrupar os conteudos institucionais, missao, visao, valores e fluxo de atendimento.

Texto institucional:

`A LF PAK e uma empresa voltada para automacao de processos de inicio e final de linha de producao, servicos de manutencao industrial, comercio de pecas, usinagem, solda e maquinas industriais.`

Complementos:

- Empresa de automacao em Uberaba e regiao, especializada em processos de final de linha.
- Atua em industrias de cosmeticos, produtos de limpeza e higiene, perfumaria, farmaceutica, entre outras.

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

Fluxo de atendimento:

- Consultoria personalizada
- Orcamento
- Fabricacao
- Manutencao e assistencia

### Rodape

Texto institucional:

`Automacao industrial, PLC / CLP, paineis eletricos, integracao de sistemas e modernizacao de maquinas para operacoes que precisam de confiabilidade.`

Contatos no rodape:

- Telefone: `(34) 3322-2612`
- WhatsApp: `(34) 98817-6301`
- E-mail comercial: `comercial@lfpak.com.br`
- E-mail assistencia tecnica: `assistenciatecnica@lfpak.com.br`
- E-mail financeiro: `financeiro@lfpak.com.br`
- Cidade/Estado: manter como `informar localidade` ate confirmacao do cliente.

Cada e-mail no rodape deve ficar em linha propria e usar `mailto:` com assunto condizente:

- Comercial: `Contato comercial`
- Assistencia tecnica: `Assistencia tecnica`
- Financeiro: `Contato financeiro`

## 8. Requisitos funcionais

- A home deve renderizar como uma landing page unica.
- O menu deve rolar para as secoes corretas: Inicio, Solucoes, Aplicacoes, Quem somos e Contato.
- O header deve permanecer fixo apos a rolagem, sem cobrir o conteudo ancorado.
- Os links de telefone, WhatsApp e e-mail devem funcionar.
- O botao flutuante de WhatsApp deve apontar para `https://wa.me/5534988176301`.
- A navegacao mobile deve abrir e fechar corretamente.
- As imagens devem usar `alt` descritivo.
- Os cards de solucoes devem manter largura consistente em todos os breakpoints.
- O favicon deve usar apenas as engrenagens da logomarca: `phactorize/assets/lfpak_favicon_gears.png`.

## 9. Requisitos nao funcionais

- Layout responsivo para mobile, tablet e desktop.
- Boa performance de carregamento de imagens.
- HTML sem dependencias desnecessarias depois da migracao para Vue.
- Acessibilidade basica: contraste adequado, foco visivel, labels/aria onde necessario e textos alternativos para imagens.
- SEO basico: title, description, headings semanticos e metadados Open Graph quando possivel.
- Estrutura preparada para deploy em ambiente Laravel.

## 10. Arquitetura sugerida no Laravel/Inertia

### Rotas

- `GET /` -> `Home/Index`
- `GET /obrigado` -> pagina simples futura apos envio de formulario, se houver formulario backend.

### Componentes Vue sugeridos

- `AppHeader.vue`
- `HeaderTopBar.vue`
- `MainNav.vue`
- `HeroSection.vue`
- `FeatureGrid.vue`
- `ServiceCards.vue`
- `ApplicationsSection.vue`
- `ProcessSection.vue`
- `AboutSection.vue`
- `MvvCards.vue`
- `ServiceFlow.vue`
- `CtaSection.vue`
- `FooterSection.vue`
- `WhatsappFloatingButton.vue`

### Dados em codigo

Inicialmente, manter arrays de conteudo em arquivos TypeScript/JavaScript, por exemplo:

- `resources/js/data/navigation.ts`
- `resources/js/data/contact.ts`
- `resources/js/data/services.ts`
- `resources/js/data/applications.ts`
- `resources/js/data/about.ts`

### PostgreSQL

Banco de dados pode ser preparado para fases futuras. Entidades opcionais:

- `contacts` para leads recebidos por formulario.
- `site_settings` para contatos e dados institucionais editaveis.
- `service_categories` e `services` se o conteudo de solucoes se tornar administravel.

Na primeira versao, o PostgreSQL pode ser usado apenas para estrutura base e migrations iniciais, sem painel administrativo obrigatorio.

## 11. Orientacoes para Laravel Boost

Ao configurar o Laravel Boost, usar o design system branded como referencia principal:

- Ler `phactorize/design-system-branded.html`.
- Migrar as decisoes visuais para tokens Tailwind.
- Preservar logos oficiais como imagens.
- Preservar hierarquia visual e espacamentos do HTML aprovado.
- Evitar recriar uma landing generica; o primeiro viewport deve continuar sendo a experiencia aprovada da LF PAK.
- Manter foco visual em envasadoras, final de linha e ambiente industrial realista.

Tokens sugeridos para `tailwind.config.js`:

- `brand.primary`: `#005B9F`
- `brand.secondary`: `#0077C3`
- `brand.accent`: `#0090E6`
- `brand.text`: `#333333`
- `brand.muted`: `#666666`
- `brand.surface`: `#F7F8FA`
- `brand.border`: `#D9D9D9`

## 12. Assets obrigatorios no projeto Laravel

Copiar para `public/assets/lfpak` ou estrutura equivalente:

- `lfpack_logo.png`
- `lfpack_logo_horizontal.png`
- `phactorize/assets/lfpak_favicon_gears.png`
- `phactorize/assets/lfpak_apple_touch_gears.png`
- `phactorize/assets/lfpak_envasadora_hero_bg.jpg`
- `phactorize/assets/lfpak_hero_card_envasadora_cliente.png`
- Todos os assets `phactorize/assets/lfpak_service_*.jpg`
- Imagens de fundo e dependencias visuais usadas pelo template `phactorize`

Tambem manter no pacote de referencia:

- `landing_page_phactorize.html`
- `phactorize/design-system-branded.html`
- `color_palette.json`
- `AGENTS.md`

## 13. Criterios de aceite

- A home em Laravel/Inertia reproduz a landing aprovada visualmente.
- Header fixo e ancoras funcionam em mobile, tablet e desktop.
- Cards de solucoes mantem largura consistente em todos os viewports.
- Contatos usam links corretos de telefone, WhatsApp e mailto.
- Secao "Quem somos" inclui texto institucional, missao, visao, valores e fluxo de atendimento.
- Favicon de engrenagens aparece no navegador.
- Nenhuma logo oficial e substituida por texto puro.
- Imagens usadas sao realistas e coerentes com envasadoras/final de linha.
- O design system branded foi considerado na implementacao Tailwind.

## 14. Fora de escopo da primeira versao

- Painel administrativo completo.
- Blog.
- Area de clientes.
- Catalogo detalhado de maquinas.
- Integracao com CRM.
- Envio real de formulario por e-mail, salvo se solicitado em etapa posterior.

## 15. Pacote de handoff

O pacote ZIP de handoff deve incluir:

- HTML aprovado: `landing_page_phactorize.html`
- Pasta `phactorize/assets`
- Design system: `phactorize/design-system-branded.html`
- Logos oficiais
- Paleta: `color_palette.json`
- Este PRD: `PRD_LF_PAK_Laravel_Inertia.md`

O ZIP deve ser usado como fonte de referencia para a implementacao no novo projeto Laravel/Inertia.
