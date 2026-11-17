# POP21 Produções

Site desenvolvido para apresentar a POP21 Produções e seu trabalho em casamentos, formaturas e eventos corporativos.

A ideia foi trazer um pouco da experiência de assistir à banda ao vivo para a navegação: fotografias de palco, vídeo de abertura, tipografia marcante e movimentos discretos. O chapéu fedora do vocalista também virou um detalhe visual em alguns botões.

## O que tem no site

- Apresentação da banda e dos formatos de show
- Galeria com fotos reais das apresentações
- Vídeo promocional com áudio original
- Avaliações de clientes fornecidas pela POP21
- Animações com GSAP e layout adaptado para celular
- Contato direto para solicitar orçamento

## Tecnologias

React, TypeScript, Vite, GSAP e CSS.

## Rodando localmente

Requer Node.js e npm.

```bash
npm install
npm run dev
```

Para conferir a versão de produção:

```bash
npm run build
npm run preview
```

## Decisões de desenvolvimento

O maior cuidado foi equilibrar movimento e desempenho. Optei por animações de transformações leves, sem prender os efeitos à rolagem da página. O vídeo curto da abertura fica sem áudio para reprodução automática; o vídeo completo do show mantém o som e os controles de reprodução.

A navegação leva aos títulos das seções, evitando que o espaçamento interno faça o conteúdo aparecer longe do topo da tela.

## Materiais e créditos

As fotografias, gravações, identidade e avaliações pertencem aos respectivos titulares e foram disponibilizadas para este projeto. O uso ou redistribuição desses materiais depende da autorização dos responsáveis.

Projeto de desenvolvimento web: [Dzelmee](https://github.com/Dzelmee).
