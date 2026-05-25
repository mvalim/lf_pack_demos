# PRD - LF PAK Equipamentos Industriais

## 1. Visao geral

Criar um novo projeto institucional e comercial para a LF PAK Equipamentos Industriais usando Laravel, Inertia.js com Vue, Tailwind CSS, Laravel Boost, FilamentPHP e PostgreSQL.

O projeto deve partir da landing page aprovada no template `phactorize`, preservando a identidade visual da LF PAK, os assets gerados, a estrutura de conteudo validada e o design system presente em `phactorize/design-system-branded.html`.

O foco principal da empresa deve ficar claro em toda a experiencia: automacao industrial aplicada a envasadoras, produtos de inicio e final de linha, PLC / CLP, paineis eletricos, retrofit, integracao de sistemas, manutencao industrial e suporte tecnico.

## 2. Objetivos do produto

- Apresentar a LF PAK como fornecedora tecnica de automacao industrial para processos mais eficientes, seguros e produtivos.
- Gerar contatos comerciais via telefone, WhatsApp e e-mail.
- Transformar o HTML estatico aprovado em uma base moderna, componentizada e facil de evoluir.
- Preservar o design aprovado no template `phactorize`, mantendo consistencia com o design system branded.
- Organizar o conteudo institucional da empresa em uma secao unica "Quem somos", incluindo descricao da empresa, missao, visao, valores e fluxo de atendimento.
- Preparar a base Laravel/Inertia com painel administrativo em FilamentPHP para atualizar contatos, textos, imagens e cards da landing page sem editar codigo.

## 3. Stack tecnica

- Backend: Laravel
- Frontend: Inertia.js com Vue
- Estilizacao: Tailwind CSS
- Banco de dados: PostgreSQL
- Painel administrativo: FilamentPHP
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
- Cidade/Estado: `Uberaba / MG`

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
- Deve existir painel administrativo em FilamentPHP, protegido por autenticacao, no caminho sugerido `/admin`.
- O painel administrativo deve permitir atualizar informacoes de contato sem deploy: telefone, WhatsApp, e-mail principal do header, e-mails do rodape, cidade/estado, textos de assunto dos links `mailto:` e texto institucional do rodape.
- O painel administrativo deve permitir editar os cards da landing page, mantendo organizacao por secao e ordenacao manual.
- Cards editaveis devem ter campos de status ativo/inativo e ordem de exibicao.
- Quando um card possuir imagem, o painel deve permitir upload/substituicao da imagem e preenchimento do texto alternativo.
- Quando um card usar icone, o painel deve permitir selecionar ou informar a classe do icone, mantendo a equivalencia visual do design system.
- O conteudo inicial do painel deve ser populado por seeders a partir da landing page aprovada.

## 9. Painel administrativo FilamentPHP

O FilamentPHP deve ser usado para criar um painel simples, orientado a conteudo, com recursos agrupados por area da landing page. O objetivo e permitir que a LF PAK atualize textos, imagens e cards principais sem depender de alteracao manual no HTML ou em componentes Vue.

### 9.1 Organizacao sugerida do menu

- Configuracoes do site
- Contatos
- Hero
- Cards da landing page
- Imagens e midia
- Usuarios administrativos

### 9.2 Configuracoes do site

Recurso sugerido: `SiteSettingsPage` ou `SiteSettingResource`.

Campos:

- Nome da empresa
- Texto institucional curto do rodape
- Cidade/Estado
- Logo horizontal
- Logo principal
- Favicon
- Status de publicacao da landing

Observacao: logos oficiais devem continuar sendo imagens. Nao permitir substituicao por texto puro.

### 9.3 Contatos

Recurso sugerido: `ContactSettingsPage`.

Campos:

- Telefone principal
- Link `tel:` gerado automaticamente ou armazenado como campo separado
- WhatsApp
- Link `wa.me` gerado automaticamente ou armazenado como campo separado
- E-mail principal do header
- E-mail comercial
- E-mail assistencia tecnica
- E-mail financeiro
- Assunto padrao do e-mail comercial
- Assunto padrao do e-mail de assistencia tecnica
- Assunto padrao do e-mail financeiro
- Cidade/Estado

Regras:

- Validar formato de e-mail.
- Normalizar telefone e WhatsApp para gerar links corretamente.
- Header deve exibir apenas o e-mail principal para evitar quebra visual.
- Rodape deve exibir cada e-mail em uma linha.

### 9.4 Hero

Recurso sugerido: `HeroSectionPage`.

Campos:

- Titulo
- Destaque do titulo
- Texto de apoio
- CTA principal: texto e destino
- CTA secundario: texto e destino
- Imagem de fundo
- Alt da imagem de fundo
- Card do hero: imagem, alt, titulo e texto

Imagens necessarias:

- Imagem de fundo industrial com envasadora.
- Imagem do card inicial com envasadora/equipamento LF PAK.

### 9.5 Cards da landing page

Usar um recurso principal `LandingCardResource`, com agrupamento por `section_key`, ou recursos separados quando isso facilitar a experiencia no painel. Todos os cards devem ter:

- Secao
- Titulo
- Texto ou descricao
- Ordem
- Status ativo/inativo
- Icone, quando aplicavel
- Imagem, quando aplicavel
- Texto alternativo da imagem, quando aplicavel
- Link/CTA, quando aplicavel

Secoes recomendadas:

- `features`: Diferenciais. Cards com icone, titulo e descricao. Nao exigem imagem.
- `services`: Solucoes. Cards com imagem obrigatoria, alt, titulo, subtitulo, CTA e ordem.
- `applications`: Aplicacoes industriais. Cards com icone, titulo e descricao. Nao exigem imagem.
- `process`: Processo tecnico. Cards com numero, titulo e descricao. Nao exigem imagem.
- `about_proofs`: Cards de apoio da secao Quem somos. Cards com icone, titulo e descricao. Nao exigem imagem.
- `mvv`: Missao, visao e valores. Cards com icone, titulo e texto; para valores, permitir lista de itens.
- `service_flow`: Fluxo de atendimento. Cards com numero, icone, titulo e descricao. Nao exigem imagem.

Cards com imagem obrigatoria:

- Solucoes:
  - Programacao de PLC / CLP
  - Paineis eletricos
  - Automacao de maquinas
  - Retrofit de equipamentos
  - Sensores, inversores e IHMs
  - Diagnostico e manutencao
- Card do hero:
  - Controle industrial com foco em continuidade operacional

Cards sem imagem, baseados em icones:

- Diferenciais
- Aplicacoes industriais
- Processo tecnico
- Cards institucionais de Quem somos
- Missao, visao e valores
- Fluxo de atendimento

### 9.6 Secoes textuais

Recurso sugerido: `LandingSectionResource`.

Campos:

- Chave da secao
- Kicker/rotulo
- Titulo
- Texto introdutorio
- Ordem
- Status ativo/inativo

Secoes esperadas:

- Diferenciais
- Solucoes
- Aplicacoes industriais
- Como trabalhamos
- Quem somos
- Fluxo de atendimento
- CTA final

### 9.7 Midia

O painel deve permitir upload de imagens para cards e secoes com imagem. Pode usar o armazenamento padrao do Laravel em `storage/app/public` com `php artisan storage:link`.

Recomendacoes:

- Validar extensoes `jpg`, `jpeg`, `png` e `webp`.
- Limitar tamanho de upload conforme ambiente.
- Gerar preview no painel.
- Exigir campo `alt` para imagens publicadas.
- Manter assets iniciais aprovados como seeders ou arquivos copiados para `public/assets/lfpak`.

### 9.8 Usuarios administrativos

O acesso ao Filament deve exigir login. Criar ao menos um usuario administrador inicial por seeder ou comando documentado.

Permissoes podem ser simples na primeira versao:

- Administrador: acesso completo.
- Editor: acesso a contatos, textos, cards e imagens, sem gerenciar usuarios.

## 10. Requisitos nao funcionais

- Layout responsivo para mobile, tablet e desktop.
- Boa performance de carregamento de imagens.
- HTML sem dependencias desnecessarias depois da migracao para Vue.
- Acessibilidade basica: contraste adequado, foco visivel, labels/aria onde necessario e textos alternativos para imagens.
- SEO basico: title, description, headings semanticos e metadados Open Graph quando possivel.
- Estrutura preparada para deploy em ambiente Laravel.

## 11. Arquitetura sugerida no Laravel/Inertia

### Rotas

- `GET /` -> `Home/Index`
- `GET /admin` -> painel FilamentPHP protegido por autenticacao
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

### Dados e conteudo

O conteudo inicial deve ser cadastrado por seeders no PostgreSQL a partir da landing page aprovada. Componentes Vue devem receber dados do backend via Inertia, evitando hardcode permanente dos cards.

Arquivos de apoio ainda podem existir para constantes visuais e fallbacks, por exemplo:

- `resources/js/data/navigation.ts`
- `resources/js/constants/sectionKeys.ts`
- `resources/js/constants/iconOptions.ts`

### PostgreSQL

Entidades sugeridas:

- `contacts` para leads recebidos por formulario.
- `site_settings` para dados globais do site, logos, favicon, textos institucionais curtos e cidade/estado.
- `contact_settings` para telefone, WhatsApp, e-mails e assuntos dos links.
- `landing_sections` para metadados editaveis de cada secao da landing.
- `landing_cards` para cards editaveis, agrupados por secao.
- `media_assets` ou uso do sistema de arquivos do Laravel para imagens enviadas pelo painel.
- `users` para administradores do Filament.

Campos recomendados para `landing_cards`:

- `id`
- `section_key`
- `title`
- `subtitle`
- `body`
- `icon`
- `image_path`
- `image_alt`
- `cta_label`
- `cta_url`
- `metadata` em JSONB para campos especificos como numero do processo ou lista de valores
- `sort_order`
- `is_active`

Na primeira versao, o PostgreSQL deve sustentar o conteudo editavel do painel FilamentPHP e fornecer os dados renderizados pela home Inertia.

## 12. Orientacoes para Laravel Boost

Ao configurar o Laravel Boost, usar o design system branded como referencia principal:

- Ler `phactorize/design-system-branded.html`.
- Migrar as decisoes visuais para tokens Tailwind.
- Preservar logos oficiais como imagens.
- Preservar hierarquia visual e espacamentos do HTML aprovado.
- Evitar recriar uma landing generica; o primeiro viewport deve continuar sendo a experiencia aprovada da LF PAK.
- Manter foco visual em envasadoras, final de linha e ambiente industrial realista.
- Considerar o FilamentPHP como parte do escopo desde o inicio, criando resources/pages para contatos, secoes, cards e midia.
- Garantir que os dados renderizados na home venham do PostgreSQL, com seeders reproduzindo o conteudo aprovado do HTML.

Tokens sugeridos para `tailwind.config.js`:

- `brand.primary`: `#005B9F`
- `brand.secondary`: `#0077C3`
- `brand.accent`: `#0090E6`
- `brand.text`: `#333333`
- `brand.muted`: `#666666`
- `brand.surface`: `#F7F8FA`
- `brand.border`: `#D9D9D9`

## 13. Assets obrigatorios no projeto Laravel

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

## 14. Criterios de aceite

- A home em Laravel/Inertia reproduz a landing aprovada visualmente.
- Header fixo e ancoras funcionam em mobile, tablet e desktop.
- Cards de solucoes mantem largura consistente em todos os viewports.
- Contatos usam links corretos de telefone, WhatsApp e mailto.
- Secao "Quem somos" inclui texto institucional, missao, visao, valores e fluxo de atendimento.
- Favicon de engrenagens aparece no navegador.
- Nenhuma logo oficial e substituida por texto puro.
- Imagens usadas sao realistas e coerentes com envasadoras/final de linha.
- O design system branded foi considerado na implementacao Tailwind.
- FilamentPHP esta instalado e acessivel em rota administrativa protegida.
- Contatos podem ser atualizados pelo painel e refletidos no header, rodape e botao de WhatsApp.
- Cards das secoes Diferenciais, Solucoes, Aplicacoes, Processo, Quem somos, MVV e Fluxo de atendimento podem ser editados, ordenados, ativados e desativados pelo painel.
- Cards que usam imagem permitem upload/substituicao da imagem e texto alternativo.
- Seeders criam o conteudo inicial igual ao da landing aprovada.

## 15. Fora de escopo da primeira versao

- Blog.
- Area de clientes.
- Catalogo detalhado de maquinas.
- Integracao com CRM.
- Envio real de formulario por e-mail, salvo se solicitado em etapa posterior.
- Permissoes administrativas avancadas alem dos perfis basicos de Administrador e Editor.

## 16. Pacote de handoff

O pacote ZIP de handoff deve incluir:

- HTML aprovado: `landing_page_phactorize.html`
- Pasta `phactorize/assets`
- Design system: `phactorize/design-system-branded.html`
- Logos oficiais
- Paleta: `color_palette.json`
- Este PRD: `PRD_LF_PAK_Laravel_Inertia.md`

O ZIP deve ser usado como fonte de referencia para a implementacao no novo projeto Laravel/Inertia.
