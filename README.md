<p align="center">
  <img src="https://raw.githubusercontent.com/Regirako/Magnet2URL/refs/heads/main/main-banner.png" alt="Magnet2URL Banner" width="100%" />
</p>

# 🎯 Magnet2URL

Transforme **magnet links** em **URLs clicáveis via HTTPS** para usar com segurança e praticidade no **Notion**, **Discord**, **Telegram** ou qualquer outro lugar onde magnet links normais não são reconhecidos!

---

## 🚀 Funcionalidade

Este projeto converte magnet links em URLs HTTPS que, ao serem clicadas, redirecionam para o cliente .torrent instalado (como **qBittorrent**, **Deluge**, entre outros).

➡️ Ideal para:
- 🗂️ Compartilhar conteúdo via Magnet de forma amigável
- 🧠 Colar em notas no Notion
- 💬 Enviar em grupos no Discord e outras redes

---

## ⚙️ Como usar 

1. Copie o link da página publicada no GitHub Pages:
> https://regirako.github.io/Magnet2URL/#

2. Adicione o magnet link após o caractere `#`. Exemplo:
> https://regirako.github.io/Magnet2URL/#magnet:?xt=urn:btih:b0aaad320310d1d1205d509b6589352da6bf0b16&dn=linuxmint-21.1-xfce-64bit.iso&tr=udp://tracker.openbittorrent.com:6969&tr=udp://tracker.opentrackr.org:1337/announce&tr=udp://tracker.leechers-paradise.org:6969&tr=udp://tracker.coppersurfer.tk:6969&tr=udp://exodus.desync.com:6969

3. **Lembre-se:** quanto mais informações seu Magnet Link tiver (**HASH + NAME + TRACKER**), mais fácil será de reconhecer ele no aplicativo de gerenciamente de torrent do seu PC-Desktop.

🔗 Ao clicar nesse link:
- O navegador tenta abrir o link no seu cliente torrent
- Se não for redirecionado automaticamente, uma mensagem explicativa com um tutorial aparecerá com a opção de tentar novamente
- Você pode acionar a música enquanto lê o tutorial clicando em "Music ON/OFF"
 
 ---

## 🧪 Exemplo de uso

🔸 **Link formatado para Notion/Discord**:
> [Baixar Linux Mint 💻](https://regirako.github.io/Magnet2URL/#magnet:?xt=urn:btih:b0aaad320310d1d1205d509b6589352da6bf0b16&dn=linuxmint-21.1-xfce-64bit.iso&tr=udp://tracker.openbittorrent.com:6969&tr=udp://tracker.opentrackr.org:1337/announce&tr=udp://tracker.leechers-paradise.org:6969&tr=udp://tracker.coppersurfer.tk:6969&tr=udp://exodus.desync.com:6969)

🔸 O que o link faz:
- Abre o navegador
- Redireciona para o seu cliente de torrent com o arquivo magnet

---

## 📦 Compatibilidade

✅ Testado com:
- qBittorrent  
- Deluge  
- Transmission  
- WebTorrent  
- Navegadores Chrome, Firefox e Edge

---

## 🛠️ Tecnologias utilizadas

- HTML + JavaScript (puro)
- GitHub Pages (deploy gratuito)

---

## 📙 Ferramenta Adicional (Torrent to Magnet)
Caso necessite transformar arquivos Torrents em Magnet Links válidos com facilidade, você pode utilizar esse projeto do usuário @nutbread (https://github.com/nutbread/t2m) como auxilio.
- **Página para conversão:** https://nutbread.github.io/t2m/

 ---
 
## 🧊 Licença

Este projeto é apenas para uso pessoal e não possui licença comercial.

---

Criado com 🧡 por [@regirako](https://github.com/regirako)
