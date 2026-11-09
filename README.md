# Spotifast (Fox Edition) 🎵

Versão customizada do **Spotifast (v0.17.1)** para Linux e Windows, incluindo todas as skins clássicas do Winamp, presets MilkDrop e temas personalizados pré-configurados.

---

## 📥 Downloads Prontos (Releases)

Baixe os executáveis prontos para uso direto na aba de [Releases](https://github.com/dossantosdouglas/spotifast/releases):

- **🪟 Windows (Portátil):** [`spotifast-v0.17.1-windows-portable-fox.zip`](https://github.com/dossantosdouglas/spotifast/releases/latest)  
  *Basta descompactar no notebook/PC e executar `spotifast.exe`. Já vem com as skins Zelda, Winamp3 e temas incluídos!*
- **🐧 Linux (x86_64):** [`spotifast-v0.17.1-linux-fox.tar.gz`](https://github.com/dossantosdouglas/spotifast/releases/latest)  
  *Binário standalone compilado para Linux com suporte a Wayland e X11.*

---

## 🎨 Personalizações Inclusas

- **Skins do Winamp:**
  - `Winamp3_Classified_v5.5.wsz`
  - `Zelda_Amp_3.wsz`
- **Temas:**
  - `Tokyo Night`
  - `Catppuccin` / `Catppuccin Latte`
  - `Nord`
  - `Rose Pine` / `Rose Pine Moon` / `Rose Pine Dawn`
  - `Ristretto`
- **Configuração de Áudio:** Bitrate 320 kbps, gapless playback, cache de áudio ativo.

---

## 🐧 Instalação no Linux (CachyOS / Arch)

Para instalar o binário e os atalhos no seu sistema Linux:

```bash
# 1. Copiar binário
cp spotifast-linux-x86_64 ~/.local/bin/spotifast
chmod +x ~/.local/bin/spotifast

# 2. Copiar configurações e skins
mkdir -p ~/.config/spotifast
cp -r custom-config/* ~/.config/spotifast/

# 3. Instalar atalho desktop e ícone
cp spotifast.desktop ~/.local/share/applications/
cp spotifast.svg ~/.local/share/icons/hicolor/scalable/apps/
update-desktop-database ~/.local/share/applications/
```

---

## 🪟 Instalação no Windows

1. Baixe o arquivo `spotifast-v0.17.1-windows-portable-fox.zip`.
2. Extraia para uma pasta (ex: `C:\Spotifast` ou na sua área de trabalho).
3. Execute `spotifast.exe`.
4. Conecte sua conta do Spotify via navegador quando solicitado.
