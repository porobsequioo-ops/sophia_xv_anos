# ✦ Sophia Fontes • 15 Anos | O Encontro do Sol com a Lua ✦

Convite digital cerimonial e imersivo desenvolvido para a celebração de 15 Anos de Sophia Fontes.

---

## 🌟 Funcionalidades
- **Introdução em Vídeo Fullscreen:** Experiência cinematográfica inicial com transição suave.
- **Trilha Sonora Celestial:** Música temática com controle de reprodução/áudio no topo.
- **Órbita Celestial Interativa:** Botões orbitais com modais de Localização (Ballroom Solarium / Google Maps), Traje (Golden Hour & Noite Estrelada), Presença (WhatsApp), Presentes (PIX) e Cronograma.
- **Design Responsivo & Mobile First:** Otimizado com Tailwind CSS e fontes do Google Fonts (Cinzel, Playfair Display e Manrope).
- **Compartilhamento Otimizado:** Metatags Open Graph configuradas para gerar prévias no WhatsApp e redes sociais.

---

## 📁 Estrutura de Arquivos
```text
├── index.html        # Arquivo principal do site
├── vercel.json       # Configuração de cache e streaming de mídia na Vercel
├── .gitignore        # Arquivos ignorados pelo Git
├── README.md         # Documentação do projeto
└── public/           # Ativos locais (músicas, vídeos e imagens)
    ├── arte-principal.jpg
    ├── musica-sol-e-lua.mpeg
    └── video-intro.mp4
```

---

## 🚀 Como subir para o GitHub e Deploy na Vercel

### Passo 1: Subir para o GitHub

Se você utiliza o **GitHub Desktop**:
1. Abra o GitHub Desktop e clique em **File > Add Local Repository...**
2. Selecione esta pasta: `stitch_convite_sophiaXVanos`.
3. Clique em **Publish repository** para criar o repositório na sua conta do GitHub.

Se você utiliza o **Terminal com Git**:
```bash
git init
git add .
git commit -m "feat: convite sophia 15 anos pronto para deploy"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git
git push -u origin main
```

---

### Passo 2: Deploy na Vercel

1. Acesse [vercel.com](https://vercel.com) e faça login com sua conta do GitHub.
2. Clique no botão **"Add New..."** > **"Project"**.
3. Localize o repositório que você acabou de subir e clique em **"Import"**.
4. Nas configurações do projeto:
   - **Framework Preset:** `Other` (já selecionado por padrão)
   - **Root Directory:** `./`
   - Não é necessário preencher Build Command nem Output Directory (é um site estático puro).
5. Clique no botão **"Deploy"**.
6. Em menos de 1 minuto, seu convite estará online com link seguro (`https://...vercel.app`).
