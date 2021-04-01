# Crypt website

- [Website](https://0xcryptfi.gitbook.io/the-crypt/)
- [Telegram](https://t.me/joinchat/YBoR54Dbu-80MTE9)
- [Discord](https://discord.gg/zrrdQRAj)
- [Twitter](https://twitter.com/0xcryptfi)

# Restoring to REMIX
## FUJI
RIP:
0x9223349Ac8b3bE1e891800836bdA2A767307C0B9

Airdrop: **This will only be the early 116 people that got on board**
0xf07B814D0b95042D9B16faf13DE6D67e7488dBB6

Survey: **This will be for 20 people who complete the survey**

## Development

### Install Dependencies

```bash
yarn
```

### Run

```bash
yarn start
```

## Deployment
We use Nelify for static site hosting
```
npm install netlify-cli -g
netlify login
netlify deploy
```

## Adding a new contract/feature
You'll need to adjust the following files:
- [ ] Load ABI to "./contracts/artifacts"
- [ ] "./src/constants/index.ts" and add the new contract
## Attribution
This code was adapted from this Uniswap repo: [uniswap-interface](https://github.com/Uniswap/uniswap-interface).