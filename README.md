<h1 align="right"><img src="https://raw.githubusercontent.com/daltonmenezes/discord-guardian-action/main/logo.svg" alt="a green shield with a check symbol in the center" align="left" />Discord Malicious Domains</h1>

<p align="right">
🤖 A list of <strong>malicious domains on Discord</strong> using the <a href="https://github.com/daltonmenezes/discord-guardian-action">Discord Guardian Action</a>
  <br><br>
  <!-- Patreon -->
  <a href="https://www.patreon.com/daltonmenezes">
    <img alt="patreon url" src="https://img.shields.io/badge/support%20on-patreon-1C1E26?style=for-the-badge&labelColor=1C1E26&color=61ffca">
  </a>
  <!-- License -->
  <a href="https://github.com/daltonmenezes/discord-malicious-domains/blob/main/LICENSE">
    <img alt="license url" src="https://img.shields.io/badge/license%20-MIT-1C1E26?style=for-the-badge&labelColor=1C1E26&color=61ffca">
  </a>
</p>
<br>

# Usage
You can download the [domains.json](https://raw.githubusercontent.com/daltonmenezes/discord-malicious-domains/main/domains/domains.json) or fetching it to get always the updated list version.

Example:
```js
const DISCORD_MALICIOUS_DOMAINS =
  'https://raw.githubusercontent.com/daltonmenezes/discord-malicious-domains/main/domains/domains.json'

axios.get(DISCORD_MALICIOUS_DOMAINS)
```

# Acknowledgment
This list is only possible thanks to the following projects:
> ✨ Don't forget to give them a star

- [Discord Phishing Links](https://github.com/nikolaischunk/discord-phishing-links)
- [discord-scam-links](https://github.com/BuildBot42/discord-scam-links)
- [Discord Guardian Action](https://github.com/daltonmenezes/discord-guardian-action)

# License

[MIT © Dalton Menezes](https://github.com/daltonmenezes/discord-malicious-domains/blob/main/LICENSE)
