Documentação — Landing Page Zepp Moments Personalizados
Esta documentação dividida em duas seções para apresentar o projeto acadêmico e comercial da Zepp Moments Produtos Personalizados.
---
PÁGINA 1: Apresentação, Objetivos e Identidade Visual
1. Contexto Acadêmico e Profissional
Instituição: Faculdade Municipal de Palhoça (FMP)
Curso: Análise e Desenvolvimento de Sistemas (ADS)
Fase: 1ª Fase
Disciplina: Programação Web
Empresa / Projeto: Zepp Moments (Produtos Personalizados)
---
2. Objetivo da Landing Page
A landing page tem como propósito principal servir de página de conversão e vitrine digital para a empresa Zepp Moments. Seus objetivos específicos incluem:
Apresentação de Marca: Comunicar a proposta de valor focada em afeto, memória e atenção aos detalhes.
Vitrine do Produto: Exibir o produto principal (caneca em cerâmica personalizada).
Geração de Leads e Vendas (CTA): Encaminhar potenciais clientes diretamente para o canal oficial de atendimento via WhatsApp.
Engajamento em Redes Sociais: Facilitar o acesso direto ao perfil do Instagram através de botão flutuante.
---
3. Identidade Visual e Paleta de Cores
A paleta de cores foi desenvolvida utilizando variáveis CSS (`:root`), priorizando tons suaves e marcantes que remetem a afeto e elegância.
Tabela de Cores da Aplicação
Nome da Variável	Código Hexadecimal	Função / Aplicação no Layout
`--primary-bg`	`#FDF0F3`	Fundo principal da página (Rosa bem claro/pastel)
`--secondary-bg`	`#FFFFFF`	Fundo de cards, cabeçalho e seções de contraste
`--purple-dark`	`#3F1C43`	Títulos principais, botões, rodapé e banner
`--pink-accent`	`#E85B88`	Botões secundários, destaques e estado `:hover`
`--pink-soft`	`#F9CBD8`	Borda da logo e tag superior da hero section
`--text-dark`	`#2B162D`	Cor base para o texto do corpo da página
`--text-muted`	`#6B5B6D`	Subtítulos e textos secundários
WhatsApp	`#25D366`	Botão de ação (CTA) principal de conversão
---
PÁGINA 2: Arquitetura Técnica, Tags HTML e Estrutura do Código
4. Estrutura de Arquivos do Repositório
```text
.
├── index.html          # Código-fonte principal (HTML5 + CSS Inline/Embedded)
├── logo2.png           # Logotipo oficial da Zepp Moments
├── caneca.jpg          # Foto de demonstração do produto principal
└── README.md           # Documentação completa do projeto
```
---
5. Mapeamento de Tags HTML5 Utilizadas
A página foi construída priorizando a semântica do HTML5, garantindo acessibilidade, bom ranqueamento (SEO) e organização estrutural.
Tag HTML	Função no Código
`<!DOCTYPE html>`	Declara o documento como HTML5.
`<html lang="pt-BR">`	Define o idioma principal do conteúdo como Português do Brasil.
`<head>`	Agrupa metadados, título da guia e links de fontes/estilos externos.
`<meta charset="UTF-8">`	Garante suporte a caracteres especiais e acentuação da língua portuguesa.
`<meta name="viewport">`	Garante a responsividade e ajuste automático da tela em dispositivos móveis.
`<link>`	Importa a biblioteca externa de ícones Font Awesome v6.5.1.
`<style>`	Bloco interno onde todo o CSS3 e Variáveis CSS foram estruturados.
`<header>`	Cabeçalho do site, contendo a logo, título da empresa e navegação inicial.
`<section>`	Agrupa blocos temáticos (Hero, Slogan Banner, Recursos/Features, Call to Action).
`<h1>` e `<h2>`	Hierarquia de títulos da página para leitura lógica e SEO.
`<p>`	Parágrafos com textos descritivos do produto e da empresa.
`<span>`	Utilizado para pequenas tags/badges estilizadas.
`<img>`	Exibição de imagens com atributos `alt` para acessibilidade.
`<a>`	Links de navegação interna e externa (WhatsApp, Instagram e links de âncora).
`<i>`	Renderização do ícone oficial do Instagram via Font Awesome.
`<footer>`	Rodapé com aviso de direitos autorais e ano corrente.
---
6. Estrutura Hierárquica do Layout (Árvore DOM)
A diagramação da página foi organizada nas seguintes seções ordenadas:
Header (`<header>`):
Logo circular (`.logo-img`)
Nome da Marca (`.site-title`)
Botão de Pedido Rápido (`.btn-header`)
Hero Section (`<section class="hero">`):
Tag de Destaque (`.hero-tag`)
Título de Impacto (`.hero-title`)
Texto de Apresentação (`.hero-subtitle`)
Botão Principal de Garantia do Produto (`.btn-cta2`)
Card com Imagem Real da Caneca (`.product-card` e `.product-img`)
Banner de Slogan (`<section class="slogan-banner">`):
Faixa em gradiente roxo destacando a frase "a diferença é encontrada nos detalhes!"
Seção de Recursos/Diferenciais (`<section class="features">`):
Título da seção (`.section-title`)
Grid em 3 colunas (`.grid-3`) contendo cards de Design Exclusivo, Alta Qualidade e Presente Inesquecível.
Seção de Chamada para Ação (`<section class="cta-section" id="pedidos">`):
Chamada direta de fechamento de venda.
Botão para envio de mensagem no WhatsApp com ícone/cor proprietária.
Rodapé (`<footer>`):
Informações de Copyright (2026).
Elemento Flutuante de Suporte (`<a class="btn-instagram-float">`):
Botão fixo no canto inferior da tela direcionando para a conta oficial no Instagram.
