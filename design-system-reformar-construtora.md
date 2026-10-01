# Design System - ReforMar Construtora (provisório)

A marca não tem logo nem paleta definidas. Este sistema parte do universo da obra: concreto, grafite e laranja de sinalização. Trocar os tokens quando o cliente enviar a identidade.

## Tom visual
- Sólido e técnico, como engenharia: grafite profundo, concreto claro e um único acento laranja.
- Títulos condensados e fortes; corpo limpo e legível.
- Fotos de obra reais em destaque, sem sombras pesadas e com cantos pouco arredondados.

## Cores
- Grafite 950 `#13161A` - fundo dos blocos escuros, hero, rodapé
- Grafite 700 `#2B3138` - títulos sobre fundo claro
- Aço 200 `#C9D0D6` - texto sobre fundo escuro, tags
- Laranja 600 `#C4560F` - botão primário (contraste AA com texto branco)
- Laranja 400 `#F08A3C` - destaques sobre fundo escuro
- Concreto 50 `#F6F5F2` - fundo padrão da página
- Concreto 100 `#ECEAE4` - seção alternada
- Concreto 200 `#D9D6CE` - bordas
- Tinta 600 `#555C63` - texto secundário
- Tinta 800 `#23282D` - texto de corpo
- Estrela `#E9B23A` - estrelas de avaliação
- Verde WhatsApp `#25D366` - exclusivo do botão de WhatsApp

## Tipografia (Google Fonts)
- Títulos: Barlow Condensed 600/700
- Corpo: Inter 400/500/600/700
- H1: 48px desktop / 32px mobile, peso 700, entrelinha 1.1, maiúsculas não
- H2: 40px / 30px, peso 700, entrelinha 1.15
- H3: 18px, Inter 700
- Corpo: 16px, entrelinha 1.7

## Componentes
- Botão primário: fundo Laranja 600, texto branco, raio 6px, altura mínima 56px, ícone em círculo branco. Hover sobe 2px.
- Botão WhatsApp: fundo verde `#25D366`, só no botão flutuante e no CTA de contato.
- Card: fundo branco, borda Concreto 200, raio 8px, sombra leve.
- Foco de teclado: contorno 3px Laranja 400.

## Estética
- Raios: 6px / 8px / 12px. Sem arredondamento exagerado.
- Sombras: apenas leves em cards; foto sem sombra.
- Espaçamento: escala de 8px (8, 16, 24, 40, 56, 80).

## Conversão para WhatsApp
- CTA no topo, após os serviços, após o passo a passo, na localização e na chamada final, com texto específico ("Pedir orçamento pelo WhatsApp").
- Mensagem pré-preenchida citando que a pessoa veio do site.
- Prova social com a nota real do Google (4,9 / 44 avaliações) perto dos CTAs.

## Tokens prontos (CSS)
```css
:root{
  --tom-950:#13161A; --tom-700:#2B3138; --tom-200:#C9D0D6;
  --acento-600:#C4560F; --acento-400:#F08A3C;
  --cream-50:#F6F5F2; --sand-100:#ECEAE4; --sand-200:#D9D6CE;
  --ink-600:#555C63; --ink-800:#23282D;
  --wa-500:#25D366; --gold-400:#E9B23A;
  --font-display:'Barlow Condensed','Arial Narrow',sans-serif;
  --font-body:'Inter',-apple-system,'Segoe UI',sans-serif;
  --r-sm:6px; --r-md:6px; --r-lg:8px; --r-xl:12px;
}
```
