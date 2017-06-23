# trellectron

An [Electron](https://electron.atom.io/) wrapper for [Trello](https://trello.com/).

Download the [latest release](https://github.com/conortm/trellectron/releases/latest).

## Local dev

```bash
git clone git@github.com:conortm/trellectron.git
cd trellectron
yarn
yarn run start
```

## Build and release

1. On `master` branch, run the following:

   ```bash
   yarn version
   # Enter new version on prompt
   yarn run build
   # Assuming all goes well, run:
   git push --follow-tags
   ```

1. Create [release](https://github.com/conortm/trellectron/releases) from tag and upload `build/Trello-darwin-x64.zip`.

## License

[MIT](./LICENSE) © [Conor McNamara](http://conortm.io/)
