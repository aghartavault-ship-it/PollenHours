# PollenHours

**EN:** A Termux pipeline to create AI videos automatically: generates prompts, generates images, and renders the final video.  
**PT-BR:** Pipeline em Termux para criar vídeos automaticamente com IA: gera prompts, gera imagens e monta o vídeo final.

Built with Pollinations.ai.

---

## 🇺🇸 English

### What it is
**PollenHours** is a pipeline designed to run on **Termux (Android)**.  
It automates three main steps:

1. generate prompts from a script  
2. generate AI images  
3. edit and export the final MP4 video

### Workflow
- `roteiro.txt` → base script
- `gerar_prompts.py` → creates the prompts
- `gerar_imagens_g4f.py` → generates/downloads the images
- `editar_video.py` → renders the final video

### Features
- Automatic prompt generation
- Batch image generation
- Per-image time logging
- 16:9 image preparation
- MP4 video export
- Pipeline designed for mobile use through Termux

### Structure
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
---

## 🇧🇷 Português

### O que é
O **PollenHours** é uma pipeline feita para rodar no **Termux (Android)**.  
Ela automatiza três etapas:

1. gerar prompts a partir do roteiro  
2. gerar imagens com IA  
3. editar e exportar o vídeo final em MP4

### Fluxo
- `roteiro.txt` → texto base
- `gerar_prompts.py` → cria os prompts
- `gerar_imagens_g4f.py` → baixa/gera as imagens
- `editar_video.py` → monta o vídeo final

### Recursos
- Geração automática de prompts
- Geração de imagens em lote
- Log de tempo por imagem
- Preparação de imagens em 16:9
- Exportação de vídeo em MP4
- Pipeline pensada para uso no celular via Termux

### Estrutura
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
