# VETUSTUS Quick Start

## 1. Download and install

Official downloads are distributed from:

https://www.vxd.mobi/vetustus/download/

Download the current Windows x64 package, verify the published SHA-256 when possible, extract the ZIP and run the setup.

The installer detects the Windows language and allows manual language selection. VETUSTUS can be installed in a custom directory, for example `D:\VETUSTUS`.

## 2. Choose your IRC identity

Open the Presence / Away area and configure, if desired:

- global primary nickname
- global alternate nickname
- `Use global nicknames for all networks`

This override is optional. If disabled, each network keeps its own identity.

## 3. Connect to a network

Open **Network Manager**, select or configure a network profile and connect.

After IRC registration completes, VETUSTUS can automatically request the server channel list. You do not need to know or type `/list` manually.

## 4. Join a channel

Open the **Channel List** under the connected network.

You can filter by channel name or topic. Double-click a channel, or select it and press Enter, to join.

## 5. Chat and private queries

Open joined channels from the network tree. Double-click a nickname to open a private query. Nick context actions include WHOIS, DCC Send, Ignore, CTCP commands and privilege-aware moderation controls.

## 6. Search XDCC packages

Open **XDCC Search**, enter a query, apply filters, select a bot/package and request the file.

VETUSTUS keeps provider popularity (`Gets`) separate from live queue state.

## 7. Follow transfers

Open **Transfers** to monitor:

- download/upload state
- progress
- ETA
- XDCC queue information when available
- resumable states
- completed-file actions

Supported media can be opened directly in the internal VETUSTUS Player.

## 8. Player

Use **Player** from the sidebar or the Play action on a completed media transfer.

The internal player supports playlists, folders/library, previous/next, shuffle, repeat and optional autoplay. Codec support depends on the runtime and system environment.

## 9. AI Center

AI is optional.

Open **Settings → AI Center** to configure a cloud provider, Ollama, LM Studio or a custom endpoint. VETUSTUS does not provide third-party API keys.

Never publish your API keys in screenshots, issues or diagnostics.

## 10. Beta notice

VETUSTUS is currently free Beta / Pre-Beta software and may contain bugs or unexpected behaviour. Users remain responsible for their API keys, configuration, automation, plug-ins, files and commands.

Project: https://www.vxd.mobi/vetustus/
