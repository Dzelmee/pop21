# POP21 Produções

Site que desenvolvi para a POP21 Produções, banda que atua em casamentos, formaturas e eventos corporativos.

A proposta foi fugir de uma página institucional convencional e trazer um pouco da presença de palco para a navegação. Usei fotos das apresentações, vídeo na abertura, tipografia expressiva e transições discretas. O chapéu do vocalista acabou virando um detalhe dos botões.

**Site:** https://pop21.com.br

## O projeto

- Página responsiva para desktop e celular
- Vídeo de abertura com reprodução automática sem som
- Vídeo de apresentação incorporado do YouTube
- Galeria de fotos com visualização ampliada
- Formações musicais com mensagens de orçamento específicas pelo WhatsApp
- Seções de eventos, depoimentos e contato
- Animações de entrada e pequenos movimentos com GSAP

## Tecnologias

React, TypeScript, Vite, CSS e GSAP.

## Executar localmente

Com Node.js e npm instalados:

```bash
npm install
npm run dev
```

Para gerar e testar a versão de produção:

```bash
npm run build
npm run preview
```

## Algumas decisões

O vídeo da primeira tela fica sem áudio para permitir a reprodução automática nos navegadores. Já o vídeo de apresentação usa o player do YouTube, com controles próprios e áudio disponível quando o visitante inicia a reprodução.

Nas formações, preferi levar cada opção diretamente ao WhatsApp com uma mensagem pronta. Assim, quem entra em contato já informa qual formato de show procura.

Também procurei manter as animações leves e deixar a navegação confortável no celular, onde espaço e desempenho fazem mais diferença.

## Materiais

Este projeto foi desenvolvido para a POP21. Fotografias, vídeos, marca e depoimentos pertencem aos respectivos titulares. A disponibilização do código não concede autorização para reutilizar esses materiais em outros projetos.

Desenvolvimento: [Dzelmee](https://github.com/Dzelmee).
