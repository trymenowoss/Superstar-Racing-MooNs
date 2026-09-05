# Superstar Racing MooNs

Rediscover the paddock. Build your racing identity. Chase your next podium.

**Superstar Racing MooNs** is a free-to-play community racing project with a hosted server, social 3D lounges, circuit racing, character customization, and tournament progression.

> Download the client, start the launcher, and create an account or sign in inside the game.

**[Download the latest release](https://github.com/trymenowoss/Superstar-Racing-MooNs/releases/latest)** · **[Release notes](https://github.com/trymenowoss/Superstar-Racing-MooNs/releases)**

## Your next race starts here

- **Meet in the paddock:** explore the 3D lounges, chat, and connect with friends and teammates.
- **Make it yours:** customize your driver with racing gear, hairstyles, and available event jackets; tune and personalize your car.
- **Race and progress:** drive circuits, record lap times, and build your profile through race results and leaderboards.
- **Enter tournaments:** Daily Tournaments, Mini GP, Race Arena, and Star Tournament systems are available as the community rebuild continues.
- **Keep your progress:** accounts, inventory, results, and awarded prizes are stored on the server.
- **One launcher:** launch the game, check for updates, and see multiplayer connection status in the same window. Keep it open while playing.

## Version 1.4.48

This update includes fixes for Star Tournament track entry and prize matching, a shared pre-race waiting phase, and podium-ring selection based on earned individual GP results rather than country jackets. It also removes the first-launch marker dependency and separate default-settings file from new packages, and includes a shop confirmation-button compatibility patch.

Race Arena now has hour-scoped results and 50/30/25 CR$ top-three payouts. This version also adds a daily winners-board reset, profile-based winner flags, and first-device approval after authentication. Additional devices require administrator approval; multiple approved devices are supported.

**Active development:** this is a community compatibility rebuild, not a promise of flawless retail behavior. First-launch/relogin connectivity, guest signup presentation, remote movement, two-player race synchronization, the shop patch, and visible arena rollover still need wider live testing. Please report reproducible issues with your version and screenshots.

<table>
  <tr>
    <td width="33.33%"><img src="docs/game-lobby.png" alt="Superstar Racing MooNs main lobby"></td>
    <td width="33.33%"><img src="docs/mini-gp-lobby.png" alt="Superstar Racing MooNs Mini GP lobby"></td>
    <td width="33.33%"><img src="docs/circuit-race.png" alt="Superstar Racing MooNs circuit race"></td>
  </tr>
  <tr align="center">
    <td><strong>Main Lobby</strong></td>
    <td><strong>Mini GP Lobby</strong></td>
    <td><strong>Circuit Racing</strong></td>
  </tr>
</table>

## Quick start

### 1. Download the installer

1. Open this repository's [Releases](../../releases/latest) page.
2. Download **Superstar.Racing.MooNs.Launcher.exe** from the latest release.
3. Run it and select **Install Game**. The launcher downloads, verifies, and installs the current game automatically.

### 2. Start the player launcher

Run the installed **Superstar Racing MooNs** launcher. Do not start `Superstar Racing.exe` directly.

Select **Play Now**. Use the native game screen to create an account or sign in
with your username/email and password.

### Verify your download

Use the SHA-256 checksum published with the matching release. Extract the full package before starting the launcher; do not mix files from different versions.

## Every time you play

1. Make sure your computer is connected to the internet.
2. Run `superstar-racing-launcher.exe`.
3. Select **Play Now** and sign in through the native game login screen.

## Updates and player requests

The launcher checks this repository for new releases. When an update is available,
select **Update** in `superstar-racing-launcher.exe`; it verifies the published
SHA-256 digest, installs the package, preserves local settings, and restarts itself.

Every updated client version, compatibility improvement, and new gameplay patch
will also be published in this repository's [Releases](../../releases/latest)
section. Download updates only from this official repository.

Superstar Racing MooNs is free to play. Players never need to pay real money to request available in-game content or currency or for servers. You may privately request:

- Outfits and character items
- Car bodies and available vehicle content
- Additional CR$

Send the request with your exact in-game name to Discord `@iamsicknow` or Telegram `@wanderbotnow`. Valid requests will be added within 24 hours. Never include your password in a content request.

### Want your own private setup?

If you are interested in running a separate private game setup with its own server, contact the owner on Discord `@iamsicknow` or Telegram `@wanderbotnow`. We can discuss whether a private setup is suitable for you, and the owner may help guide you through the setup process. Availability and requirements are discussed privately.

## Troubleshooting

### Player login failed: server is offline

- Confirm your internet connection is working.
- Allow the launcher and game through local firewall or antivirus prompts.
- Ask the owner to check the AWS game service status.

### The game asks for the official retail launcher

Close the message and start `superstar-racing-launcher.exe` from the extracted game folder.

### Windows SmartScreen appears

The community launcher is not code-signed and performs runtime compatibility patching, which can trigger security warnings. A warning should be investigated rather than assumed harmless. Check the release notes for any scan results provided for that particular build.

No developer can guarantee identical results from every antivirus engine or future signature update. Do not disable antivirus protection. Verify the SHA-256 checksum shown on the GitHub release, download only from this repository, and contact the owner if security software blocks the client.

## Security and privacy

- The published player package contains no database credentials, admin interface, or server source code.
- Public access is limited to the game, account, and read-only player-state services. The admin interface and database are not exposed publicly.
- Native game passwords remain private and are not included in the downloadable package.
- Hardware enforcement uses a one-way pseudonymous device digest; raw Windows machine identifiers are not transmitted or stored.
- Race rewards, progression, and leaderboard submissions are validated server-side. Client integrity signals are supporting evidence and are retained for administrator review.

Please report security concerns privately as described in [SECURITY.md](SECURITY.md).

## License and game content

Original repository documentation and supporting project material are licensed under the [MIT License](LICENSE).

Superstar Racing game executables, data files, artwork, names, trademarks, and other third-party material included in downloadable release assets are **not relicensed under MIT**. They remain the property of their respective owner(s) and are redistributed with permission. See [THIRD_PARTY_NOTICE.md](THIRD_PARTY_NOTICE.md).
