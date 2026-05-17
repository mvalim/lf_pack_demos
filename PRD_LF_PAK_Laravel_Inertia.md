# PRD - LF PAK Equipamentos Industriais

## 1. Visao geral

Criar um novo projeto institucional e comercial para a LF PAK Equipamentos Industriais usando Laravel, Inertia.js com Vue, Tailwind CSS, Laravel Boost e PostgreSQL.

O projeto deve partir do template aprovado `phactorize`, preservando a identidade visual da LF PAK, os assets gerados, a estrutura de conteudo ja validada e o design system presente em `phactorize/design-system-branded.html`.

O foco principal da empresa deve ficar claro em toda a experiencia: automacao industrial aplicada a envasadoras, equipamentos de final de linha, PLC / CLP, paineis eletricos, retrofit, integracao de sistemas e suporte tecnico.

## 2. Objetivos do produto

- Apresentar a LF PAK como fornecedora tecnica de automacao industrial para processos mais eficientes, seguros e produtivos.
- Gerar contatos comerciais via telefone, WhatsApp e e-mail.
- Transformar o HTML estatico aprovado em uma base moderna, componentizada e facil de evoluir.
- Permitir que conteudos futuros, como missao, visao, valores e "quem somos", sejam inseridos sem recriar a pagina.
- Manter fidelidade visual ao template `phactorize` e ao design system branded.

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
- Grids responsivos
- Rodape
- Overlays azuis sobre imagens industriais
- Iconografia baseada em Font Awesome no template original, podendo ser migrada para uma biblioteca Vue se mantida a equivalencia visual

## 6. Estrutura de paginas

### 6.1 Pagina inicial

A pagina inicial deve conter as secoes do HTML aprovado:

- Header fixo com barra superior de contatos
- Hero com imagem realista de ambiente industrial com envasadora
- Card de destaque sobre controle industrial e continuidade operacional
- Diferenciais
- Solucoes
- Aplicacoes industriais
- Como trabalhamos
- Sobre a LF PAK
- Chamada para contato
- Rodape com links rapidos e contatos
- Botao flutuante de WhatsApp

### 6.2 Possiveis paginas futuras

Preparar a arquitetura para permitir futuras paginas ou areas:

- Quem somos
- Missao, visao e valores
- Solucoes detalhadas
- Cases ou projetos realizados
- Blog tecnico
- Area administrativa simples para edicao de conteudo, se necessario

## 7. Conteudo aprovado ate o momento

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

### 7.7 Sobre

Texto atual:

`A LF PAK Equipamentos Industriais atua no desenvolvimento de solucoes para automacao industrial, combinando conhecimento tecnico, precisao na execucao e foco nas necessidades reais da operacao.`

`O objetivo e entregar sistemas confiaveis, seguros e preparados para aumentar a eficiencia da producao, melhorar o controle dos processos e apoiar equipes industriais em demandas de modernizacao, integracao e suporte.`

Observacao: missao, visao, valores e texto final de "quem somos" serao enviados posteriormente pelo cliente.

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

No rodape, cada e-mail deve aparecer em uma linha propria.

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
- Cards de diferenciais e solucoes devem manter alinhamento e altura visual consistente.
- O conteudo institucional futuro deve poder ser atualizado sem quebrar layout.

## 10. Requisitos nao funcionais

- Performance: otimizar imagens e entregar assets com cache adequado.
- Acessibilidade: usar textos alternativos em imagens, estados de foco visiveis e contraste adequado.
- SEO: estruturar headings, metadados, descricao da empresa e textos focados em automacao industrial.
- Manutenibilidade: componentizar secoes em Vue com props ou dados configuraveis.
- Consistencia visual: seguir `design-system-branded.html` e `color_palette.json`.
- Compatibilidade: validar em desktop, tablet e mobile.

## 11. Modelo de dados inicial sugerido

Mesmo que a primeira versao seja majoritariamente institucional, preparar o PostgreSQL para evolucao:

- `pages`: paginas editaveis como home, sobre e contato.
- `sections`: blocos de conteudo ordenaveis por pagina.
- `services`: solucoes oferecidas com titulo, subtitulo, descricao, imagem e ordem.
- `applications`: aplicacoes industriais com titulo, descricao, icone e ordem.
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

Assets principais do template exportado:

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
- `lfpack_logo.png`
- `lfpack_logo_horizontal.png`
- `color_palette.json`

## 15. Criterios de aceite

- A home em Laravel/Inertia reproduz a estrutura visual e o conteudo aprovado no HTML `phactorize`.
- Logos oficiais aparecem como imagem, nunca como texto.
- Header fixo funciona em desktop e mobile.
- Cliques no menu rolam para a secao correta sem esconder os titulos atras do header.
- Cards permanecem alinhados e com padrao de altura em todos os viewports configurados.
- Contatos usam links corretos de telefone, WhatsApp e e-mail.
- O rodape exibe cada e-mail em linha propria.
- As imagens de solucoes representam envasadoras, linhas finais e automacao industrial realista.
- O projeto usa tokens de cor alinhados a `color_palette.json`.
- O design system exportado esta disponivel para consulta e configuracao no Laravel Boost.

## 16. Pendencias conhecidas

- Inserir missao, visao e valores quando o cliente enviar.
- Atualizar texto final de "quem somos" quando o cliente enviar.
- Confirmar se o cliente deseja fotos reais das maquinas ou manter imagens realistas geradas.
- Definir se havera painel administrativo na primeira versao ou apenas conteudo versionado no codigo.

