# PollenHours

**EN:** A Termux pipeline to create AI videos automatically: generates prompts, generates images, and renders the final video.  
**PT-BR:** Pipeline em Termux para criar vídeos automaticamente com IA: gera prompts, gera imagens e monta o vídeo final.

Built with Pollinations.ai.

---

## 🇺🇸 English

### What it is
**PollenHours** is a mobile-first AI video pipeline designed to run on **Termux (Android)**.  
It helps automate the creation of short AI videos directly on a phone.

The pipeline is organized into three main steps:

1. generate prompts from a script  
2. generate AI images in batch  
3. edit and export the final MP4 video  

### Workflow
- `roteiro.txt` → base script
- `gerar_prompts.py` → creates image prompts from the script
- `gerar_imagens_g4f.py` → generates/downloads images
- `editar_video.py` → renders the final video

### Features
- Automatic prompt generation from a text script
- Batch image generation
- Per-image time logging
- 16:9 image preparation
- MP4 video export
- Mobile-friendly workflow built for Termux
- Simple pipeline for content creation on Android

### Project structure
```bash
video_ai/
├── gerar_prompts.py
├── gerar_imagens_g4f.py
├── editar_video.py
├── roteiro.txt
├── prompts_imagem.txt
├── images/
├── images_prep_16x9/
└── README.md
```

### Use case
This project is useful for creators who want to:
- write or paste a script
- convert it into visual prompts
- generate a sequence of AI images
- assemble everything into a final video on mobile

### Status
Current pipeline includes:
- prompt generation
- image generation
- image preparation
- video rendering

### Notes
This project is focused on **automation, speed, and mobile usability**.  
It is designed to help build AI-assisted video workflows directly inside Termux.

---

## 🇧🇷 Português

### O que é
O **PollenHours** é uma pipeline mobile-first de vídeo com IA feita para rodar no **Termux (Android)**.  
Ela ajuda a automatizar a criação de vídeos curtos com IA diretamente no celular.

A pipeline é organizada em três etapas principais:

1. gerar prompts a partir de um roteiro  
2. gerar imagens com IA em lote  
3. editar e exportar o vídeo final em MP4  

### Fluxo
- `roteiro.txt` → texto base
- `gerar_prompts.py` → cria os prompts de imagem a partir do roteiro
- `gerar_imagens_g4f.py` → baixa/gera as imagens
- `editar_video.py` → monta o vídeo final

### Recursos
- Geração automática de prompts a partir de texto
- Geração de imagens em lote
- Log de tempo por imagem
- Preparação de imagens em 16:9
- Exportação de vídeo em MP4
- Fluxo pensado para celular via Termux
- Pipeline simples para criação de conteúdo no Android

### Estrutura do projeto
```bash
video_ai/
├── gerar_prompts.py
├── gerar_imagens_g4f.py
├── editar_video.py
├── roteiro.txt
├── prompts_imagem.txt
├── images/
├── images_prep_16x9/
└── README.md
```

### Caso de uso
Este projeto é útil para criadores que querem:
- escrever ou colar um roteiro
- transformar o roteiro em prompts visuais
- gerar uma sequência de imagens com IA
- montar tudo em um vídeo final no celular

### Status
A pipeline atual inclui:
- geração de prompts
- geração de imagens
- preparação das imagens
- renderização do vídeo

### Observações
Este projeto é focado em **automação, velocidade e usabilidade no celular**.  
Ele foi pensado para ajudar na construção de fluxos de vídeo com IA diretamente dentro do Termux.

---

## License

MIT
