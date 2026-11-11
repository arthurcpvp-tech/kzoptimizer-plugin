# 🚀 KZOPTIMIZER
### Optimize Your Server. Experience Better Performance.

**KZOPTIMIZER** is a Minecraft server optimization and lag machine detection plugin developed by **KAIZEN**. It is designed for server owners who want better server stability, advanced monitoring, and protection against harmful lag machines.

Built for modern Minecraft servers running Paper and Leaf, KZOPTIMIZER combines performance-focused systems with configurable detection and Discord Bot integration.

---

# ✨ FEATURES

## ⚡ Advanced Server Optimization
KZOPTIMIZER is designed to help server administrators maintain a smoother and more stable server environment.

- Performance-focused background processing.
- Efficient resource management.
- Configurable optimization settings.
- Lightweight plugin architecture.
- Designed to minimize unnecessary server workload.

## 🔍 Advanced Lag Machine Detection
Identify suspicious redstone activity and potential lag machines.

- Fast detection system.
- Event-driven activity monitoring.
- Suspicious redstone activity analysis.
- Machine activity investigation.
- Detection across connected chunks.
- Configurable detection settings.
- Duplicate detection prevention.

## 🧊 Automatic Lag Machine Freeze
Help administrators respond to confirmed harmful lag machines.

- Automatic freeze system.
- Fast response after detection confirmation.
- Verification of freeze results.
- Protection against unnecessary freezing.
- Avoids targeting normal farms and harmless redstone builds.

## 🤖 Discord Bot Integration
Connect KZOPTIMIZER to your Discord server using a real Discord Bot.

Receive lag machine detection notifications directly in your configured Discord channel.

Notification information includes:

- Player
- Location
- World
- Detection Reason
- Freeze Status

Additional features:

- Configurable Bot Token.
- Configurable Discord Server ID.
- Configurable Channel ID.
- Asynchronous message processing.
- Connection error handling.
- Secure token handling.

**Important:** Never share your Discord Bot Token publicly.

## ⚙️ Configuration System
Customize plugin behavior through configuration files.

- `config.yml` — Main plugin settings.
- `message.yml` — Player-facing messages.
- `discord.yml` — Discord Bot configuration.

Configuration is designed to make plugin management easier without requiring Java code modifications.

---

# 📦 REQUIREMENTS

| Requirement | Version |
|---|---|
| Minecraft | 1.21.11 |
| Server Software | Paper / Leaf |
| Java | 21 |
| Plugin Version | 1.1.3 |

---

# 📥 INSTALLATION

1. Download the latest KZOPTIMIZER release.
2. Download `kzoptimize.jar`.
3. Open your Minecraft server directory.
4. Locate the `plugins` folder.
5. Upload `kzoptimize.jar`.
6. Restart your Minecraft server.
7. Open the generated KZOPTIMIZER configuration files.
8. Customize your settings.
9. Configure Discord Bot integration if needed.
10. Restart or reload the plugin as supported.

---

# 🤖 DISCORD BOT SETUP

To enable Discord notifications:

1. Create a Discord application.
2. Create a Bot inside the application.
3. Configure the required bot permissions.
4. Invite the bot to your Discord server.
5. Copy your Discord Server ID.
6. Copy your notification Channel ID.
7. Add your Bot Token and IDs to `discord.yml`.
8. Enable Discord integration.
9. Restart the plugin.
10. Verify that the bot connects and can send messages.

Keep your Bot Token private. Never upload it to a public GitHub repository.

---

# 🔧 COMMANDS

Use the plugin's help command to view available commands and descriptions.

```text
/kzoptimizer help
/kzoptimizer reload
