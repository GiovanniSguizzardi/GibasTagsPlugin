![minecraft_tags](https://github.com/user-attachments/assets/52630bf7-b6c6-4a87-b0be-11079fce5066)

<h1 align="center">GibasTags</h1>

<p align="center">
  Um plugin leve e funcional para gerenciamento de tags personalizadas no Minecraft! Ideal para servidores que querem permitir que jogadores escolham suas tags ou que a staff defina manualmente.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Minecraft-1.21%2B-blue?style=for-the-badge&logo=minecraft" />
  <img src="https://img.shields.io/badge/Java-21+-orange?style=for-the-badge&logo=openjdk" />
  <img src="https://img.shields.io/badge/API-Paper%20%2F%20Spigot-yellow?style=for-the-badge" />
</p>

---

## ✨ Funcionalidades

- 📁 Configuração simples via `config.yml`
- 🎮 Comando `/tag` para visualizar, aplicar ou remover tags
- 🔐 Permissões por tag (`gibastags.vip`, `gibastags.yt`, etc.)
- 🛠️ Comando `/gibastags reload` para recarregar configurações em tempo real
- 🧑‍⚖️ Comando `/tag set <jogador> <tag>` para staff
- 💾 Persistência automática da tag escolhida
- 🔌 Integração com **PlaceholderAPI**: `%gibastags_tag%`

---

## 📦 Instalação

1. Baixe o plugin `.jar` e coloque em sua pasta `plugins/`
2. Instale também o plugin [PlaceholderAPI](https://www.spigotmc.org/resources/placeholderapi.6245/)
3. Reinicie o servidor
4. Configure as tags no arquivo `config.yml`

---

## ⚙️ Exemplo de `config.yml`

```yaml
tags:
  vip:
    prefix: "&6[VIP]"
    permission: "gibastags.vip"
  yt:
    prefix: "&c[YOUTUBER]"
    permission: "gibastags.yt"
  builder:
    prefix: "&b[BUILDER]"
    permission: "gibastags.builder"
  membro:
    prefix: "&7[MEMBRO]"
    permission: "gibastags.membro"

default-tag: "membro"
