---
title: "Cidade Neon — Ambiente 3D"
description: "Uma paisagem urbana cyberpunk renderizada no Blender, apresentando ruas iluminadas por néon, reflexos de chuva e névoa volumétrica."
date: 2025-08-22
image: "https://images.unsplash.com/photo-1514565131-fce0801e5785?w=800"
tags: ["Arte 3D", "Blender", "Cyberpunk", "Ambiente"]
category: "Arte 3D"
featured: false
media_type: "art"
tech: ["Blender", "Substance Painter", "After Effects"]
url: ""
repository: ""
gallery:
  - type: image
    url: "https://images.unsplash.com/photo-1514565131-fce0801e5785?w=1200"
    caption: "Cidade Neon — Render final"
    alt: "Uma rua de cidade cyberpunk à noite com letreiros de néon e reflexos molhados"
  - type: image
    url: "https://images.unsplash.com/photo-1545569341-9eb8b30979d9?w=1200"
    caption: "Detalhe do Beco — Teste de iluminação volumétrica"
    alt: "Um beco estreito com raios de luz volumétricos cortando a névoa"
  - type: image
    url: "https://images.unsplash.com/photo-1519608487953-e999c86e7455?w=1200"
    caption: "Vista do Terraço — Panorama grande angular"
    alt: "Vista aérea de uma cidade iluminada por néon à noite"
  - type: image
    url: "https://images.unsplash.com/photo-1493514789931-586cb221d7a7?w=1200"
    caption: "Nível da Rua — Chuva e reflexos"
    alt: "Rua encharcada de chuva refletindo luzes coloridas de néon"
---

## Conceito

**Cidade Neon** começou como um desafio pessoal para construir um ambiente cyberpunk completo no Blender em 30 dias. O objetivo era criar uma cena carregada de atmosfera que contasse uma história sem personagens — apenas arquitetura, luz e atmosfera.

![Visão geral do wireframe](https://images.unsplash.com/photo-1480944657103-7fed22359e1d?w=1000)

### Inspiração

O projeto busca referências em filmes como *Blade Runner 2049*, no jogo *Cyberpunk 2077* e na fotografia de Liam Wong. Eu queria capturar a sensação de caminhar por uma cidade encharcada de chuva às 2 da manhã — isolada, mas visualmente avassaladora.

### Fluxo de Trabalho

1. **Bloqueio** — Geometria bruta para definir a composição e ângulos de câmera
2. **Modelagem** — Fachadas detalhadas de prédios, letreiros, tubulações e objetos de rua
3. **Texturização** — Materiais PBR no Substance Painter com mapas emissivos pintados à mão
4. **Iluminação** — Mais de 40 luzes de área e shaders de emissão para o brilho do néon
5. **Renderização** — Cycles com 2048 amostras e denoising
6. **Pós-processamento** — Bloom, aberração cromática e ajuste de cor no After Effects

![Detalhamento da iluminação](https://images.unsplash.com/photo-1550745165-9bc0b252726f?w=1000)

### Detalhes Técnicos

- **Contagem de polígonos**: ~2,4 milhões de triângulos
- **Tempo de render**: 18 minutos por quadro (RTX 3080)
- **Resolução**: 3840 × 2160 (4K)
- **Resolução de texturas**: 4K para elementos principais, 2K para fundo

> "A cidade é um personagem. Cada mancha na parede, cada letreiro piscando — tudo contribui para a narrativa."

### Aprendizados

Este projeto me desafiou a otimizar cenas pesadas no Blender. Aprendi a usar **geometry nodes** para espalhar pequenos objetos (cabos, detritos, poças) e **light linking** para controlar exatamente quais objetos cada letreiro de néon ilumina.

O maior desafio foi equilibrar qualidade de render com tempo — névoa volumétrica fica incrível, mas multiplica o tempo de render por 3x.