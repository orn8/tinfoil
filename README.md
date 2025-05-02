<div align="center">
  <h1 align="center"><strong>oragne shop</strong></h1>
  <h3>A Tinfoil shop forwarder hosted on GitHub.</h3>
</div>

<br/>

<div align="center">
  <a href="https://github.com/orn8/tinfoil/stargazers"><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/orn8/tinfoil?style=for-the-badge"></a>
  <a href="https://github.com/orn8/tinfoil/blob/main/LICENSE"><img alt="License" src="https://img.shields.io/badge/license-EPLv2-purple?style=for-the-badge"></a>
</div>

<br/>

**oragne shop** is an All-in-one Tinfoil shop forwarder filled with the latest sources and games. Built with the [Tinfoil Documentation](https://blawar.github.io/tinfoil/custom_index/).

> [!WARNING]
> **oragne shop** acts solely as a forwarding service and is not responsible for the quality, safety, legality, or delivery of products from third-party shops.

---

## Prerequisites

* Nintendo Switch running CFW ([Atmosphere](https://github.com/Atmosphere-NX/Atmosphere/releases) with [Sigpatches](https://sigmapatches.su/) recommended).

* Relies on [Tinfoil](https://tinfoil.io) (self-installer build recommended).

* To avoid getting banned make sure you have already setup [Exosphere/DNS MITM](https://rentry.org/ExosphereDNSMITM).

> [!TIP]
> It is recommended to setup Google Drive OAuth to avoid receiving potential errors with Tinfoil shops.
> * Click [here](https://rentry.co/reDUMPSHOPOAUTH) to follow setup instructions for Google Drive OAuth.

## Installation

Add this location to Tinfoil's file browser to use **oragne shop**:

```
Protocol: https
Host: tinfoil.oragne.dev
Path: tinfoil.json
Title: oragne shop
```
If the one above isn't functioning, try this one below:
```
Protocol: https
Host: raw.githubusercontent.com
Path: orn8/tinfoil/main/tinfoil.json
Title: oragne shop
```

## Current Shops:

> [!IMPORTANT]
> There are currrently no available shops with Switch games and software in **oragne shop**

* **Ghost eShop Retro NX:** This shop contains retro roms. ([View wiki](https://wiki.ghosteshop.com/docs/nx/retro))
```
Protocol: https
Host: nx-retro.ghostland.at
Title: Ghost eShop Retro NX
```

* **NX Shared Saves:** This database contains modified save files that are installable on many games.
```
Protocol: https
Host: nx-saves.ghostland.at
Title: NX Shared Saves
```

---

## Other Shops:
> ### This is a list of other shops you can manually add that aren't in **oragne shop**.

<br/>

### Free Shops:

* **notUltraNX (not on tinfoil - this shop is only installable on the Russian software [DBI](https://github.com/rashevskyv/dbi), sign-up required [here](https://not.ultranx.ru/en/register))**
```
Website: https://not.ultranx.ru/
Guide: https://not.ultranx.ru/en/howto
```

### Paid Shops:

* **Kronos Zenten Shop (monthly paid license at [their Discord server](https://discord.com/invite/kscctYj))**
```
Protocol: https
Host: myrincon.es
Path: net/Zenten
Title: Kronos Zenten Shop
```

* **Ghost eShop PRO (exclusive to donors - access available after donation, sign-up required [here](https://pro.nlib.cc/register))**
```
Website: https://pro.nlib.cc
Wiki: https://wiki.ghosteshop.com/docs/nx/pro
```

## N/A Shops:
> ### This is a backup of shops that have been discontinued or are unavailable.

<br/>

* **Stealth Shop**
```
Protocol: https
Host: stealthshop.cf
Title: Stealth Shop
```

* **Pengu Shop**
```
Protocol: https
Host: pengu.us
Title: Pengu Shop
```

* **QuotaShop**
```
Protocol: https
Host: quotanx.in
Title: QuotaShop
```

* **ReDUMP Shop**
```
Protocol: https
Host: redump.cf
Title: ReDUMP Shop
```

* **Voxhost Tinfoil Server**
```
Protocol: https
Host: tinfoilhost.voxhost.fr
Title: Voxhost Tinfoil Server
```

* **雷禪商店 Rayzen Shop**
```
Protocol: https
Host: tiny.cc
Path: Rayzen-vip
Title: Rayzen Shop
```

* **TITS**
```
Protocol: https
Host: titz.cf
Title: TITS
```

* **TITS 2**
```
Protocol: https
Host: tiny.cc
Path: turtleshop
Title: TITS 2
```

* **UnderPrivileged Shop**
```
Protocol: https
Host: cdn.discordapp.com
Path: attachments/531350560549634069/902073525370765352/Under.tfl
Title: UnderPrivileged Shop
```

* **A-Network Tinfoil Shop**
```
Protocol: nut
Host: a-network.ca
Port: 9000
Username: reddit
Password: reddit
Title: A-Network Tinfoil Shop
```

* **PixelShop**
```
Website: https://pixelshop.lol
```

* **RetroRom Shop**
```
Website: https://retrorom.shop
Guilded: https://www.guilded.gg/i/kbG8GnPp
```

* **Teknik**
```
Discord: https://discord.com/invite/teknik
```

* **Biscuit Shop**
```
Discord: https://discord.com/invite/Jx6CdxppM7
```

* **LiberaShop**
```
Protocol: https
Host: liberashop.rs
Title: LiberaShop
```

* **POCODA Shop**
```
Discord: https://discord.gg/kkKmDNyZgc
```

* **GratiSwitch**
```
Website: https://grat.pages.dev
Guilded: https://www.guilded.gg/gratiswitch
```

* **UltraNX:** This shop contains games and software.
```
Protocol: https
Host: tinfoil.ultranx.ru
Path: tinfoil
Title: UltraNX
```

* **Egg Fried Rice Shop:** This shop contains games and software.
```
Protocol: https
Host: cyrilz87.net
Title: Egg Fried Rice Shop
```

* **Ghost eShop** *(temporarily unavailable)*
```
Protocol: https
Host: nx.ghostland.at
Title: Ghost eShop PUBLIC
```

## FAQ

<details>
  <summary><strong>❌ "Unknown Frame descriptor" when opening Tinfoil</strong></summary>
  <blockquote>
    <p>This means your Tinfoil installation is corrupted.</p>
    <ul>
      <li>Delete the Tinfoil forwarder on your main screen.</li>
      <li>Remove the folder: <code>SD:/switch/tinfoil</code></li>
      <li>Open <strong>DBI → TOOLS</strong> and clean up orphaned files.</li>
      <li>Reinstall Tinfoil.</li>
    </ul>
  </blockquote>
</details>

<details>
  <summary><strong>🌀 Game icon is blank with spinning circle</strong></summary>
  <blockquote>
    <p>You're likely on the wrong firmware version.</p>
    <ul>
      <li>Update your Switch to the required firmware version.</li>
    </ul>
  </blockquote>
</details>

<details>
  <summary><strong>🎮 Retro Shop game won’t start</strong></summary>
  <blockquote>
    <p>This can happen for several reasons:</p>
    <ul>
      <li>Your firmware is too new for the forwarders used.</li>
      <li>Retroarch is not installed.</li>
      <li>A required Retroarch core is missing.</li>
    </ul>
    <p><strong>Fixes:</strong></p>
    <ul>
      <li>Downgrade one firmware version (if using emuMMC) or import the ROM directly into Retroarch.</li>
      <li>Install Retroarch via the Homebrew Store.</li>
      <li>Open Retroarch and download the needed core.</li>
    </ul>
  </blockquote>
</details>

<details>
  <summary><strong>🌐 Tinfoil shows "Network Error 28"</strong></summary>
  <blockquote>
    <p><strong>Possible Causes:</strong></p>
    <ul>
      <li>WiFi disabled.</li>
      <li>Incorrect source configuration.</li>
      <li>Shop server is down.</li>
      <li>Slow internet connection.</li>
    </ul>
    <p><strong>Fixes:</strong></p>
    <ul>
      <li>Enable WiFi.</li>
      <li>Check your credentials and source settings.</li>
      <li>Wait for the shop to come back online.</li>
      <li>Try again later.</li>
    </ul>
  </blockquote>
</details>

<details>
  <summary><strong>🌐 Tinfoil shows "Network Error 7"</strong></summary>
  <blockquote>
    <p>Your ISP is blocking access to the shop.</p>
    <ul>
      <li>Use a VPN for your modem or router.</li>
    </ul>
  </blockquote>
</details>

<details>
  <summary><strong>📅 Can’t sort by release date in Tinfoil</strong></summary>
  <blockquote>
    <p>Your database may be corrupted.</p>
    <ul>
      <li>Delete the <strong>DB</strong> folder inside Tinfoil.</li>
      <li>Restart the app.</li>
    </ul>
  </blockquote>
</details>

<details>
  <summary><strong>🔍 Can’t find a specific game</strong></summary>
  <blockquote>
    <p><strong>Tip:</strong></p>
    <ul>
      <li>Highlight <strong>"New Games"</strong> or <strong>"XCI"</strong> and press the <strong>"+"</strong> button.</li>
      <li>Use short keywords (e.g., <em>Mario</em>, <em>Zelda</em>, <em>Pokemon</em>).</li>
    </ul>
  </blockquote>
</details>

<details>
  <summary><strong>🈶 Game can’t be found by name</strong></summary>
  <blockquote>
    <p>It may have an Asian title.</p>
    <ul>
      <li>Go to <strong>"New Games/XCI"</strong>.</li>
      <li>Press <strong>"-"</strong> to search by icon instead.</li>
    </ul>
  </blockquote>
</details>

<details>
  <summary><strong>🚫 "Unsigned Code/Signature" error in Tinfoil</strong></summary>
  <blockquote>
    <p>Some dumps include custom tags—this is safe.</p>
    <ul>
      <li>Enable <strong>"Unsigned Signature"</strong> in settings.</li>
      <li>Use the following code: <code>Up Upp Down Down Left Right Left Right B A +</code></li>
    </ul>
  </blockquote>
</details>

<details>
  <summary><strong>🕹️ Retro ROM shows "Unable to start software"</strong></summary>
  <blockquote>
    <ul>
      <li>Update your Switch to the required firmware version.</li>
    </ul>
  </blockquote>
</details>

<details>
  <summary><strong>🌍 ISP is blocking the shop</strong></summary>
  <blockquote>
    <p><strong>Fixes:</strong></p>
    <ul>
      <li>Change DNS settings on your Switch:</li>
      <ul>
        <li>Primary: <code>1.1.1.1</code></li>
        <li>Secondary: <code>8.8.8.8</code></li>
      </ul>
      <li>Or use a VPN.</li>
    </ul>
  </blockquote>
</details>

<details>
  <summary><strong>🌐 Tinfoil shows "Network Error 6"</strong></summary>
  <blockquote>
    <p><strong>Possible Causes:</strong></p>
    <ul>
      <li>Incorrect shop config.</li>
      <li>WiFi is off or not configured.</li>
      <li>DNS settings are wrong.</li>
    </ul>
    <p><strong>Fixes:</strong></p>
    <ul>
      <li>Compare your config with the correct settings.</li>
      <li>Turn WiFi on.</li>
      <li>Set DNS to <strong>Auto</strong>.</li>
    </ul>
  </blockquote>
</details>

<details>
  <summary><strong>🔐 Tinfoil shows "Network Error 35 (SSL Handshake)"</strong></summary>
  <blockquote>
    <p>Your system clock is out of sync.</p>
    <ul>
      <li>Install the Homebrew app <strong>DBI</strong>.</li>
      <li>Use <strong>Tools → Sync Clock via NTP</strong>.</li>
    </ul>
  </blockquote>
</details>

<details>
  <summary><strong>💾 “Corrupted Data” error in Tinfoil</strong></summary>
  <blockquote>
    <p><strong>Causes:</strong></p>
    <ul>
      <li>Damaged sectors on your SD card.</li>
      <li>Corrupted Tinfoil installation.</li>
    </ul>
    <p><strong>Fixes:</strong></p>
    <ul>
      <li>Delete Tinfoil and the <code>SD:/switch/tinfoil</code> folder.</li>
      <li>Reinstall Tinfoil.</li>
      <li>In Hekate: <strong>Console Info → microSD</strong> to check for SD card issues.</li>
    </ul>
  </blockquote>
</details>

---

## Contributing

**oragne-shop** would like to get notified of issues and new shops.

If you'd like to contribute, please report an issue, or fork the repo and create a PR.

### Our Contributors ✨

<a href="https://github.com/orn8/tinfoil/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=orn8/tinfoil"/>
</a>

<br/>
<br/>
<br/>

<blockquote>
<h3>Also check out:</h3>

- <a href="https://github.com/carcaschoi/tinfoil-json">tinfoil-json</a> - The inspiration for this project
- <a href="https://github.com/melogabriel/tinfoil-shops">tinfoil-shops</a> - Another Tinfoil shop library
</blockquote>
