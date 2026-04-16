# PollenHours

**PT-BR:** Pipeline em Termux para criar vídeos automaticamente com IA: gera prompts, gera imagens e monta o vídeo final.  
**EN:** A Termux pipeline to create AI videos automatically: generates prompts, generates images, and renders the final video.

Built with Pollinations.ai.

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
