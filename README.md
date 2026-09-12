# vibepage CLI

Install:

```bash
curl -fsSL https://github.com/vibepage/cli/releases/latest/download/install.sh | bash
```

Releases and binaries are published here. The hosting control plane stays in a private repository.

## Manual download

Grab the binary for your OS/arch from [Releases](https://github.com/vibepage/cli/releases), then:

```bash
chmod +x vibepage-*
mv vibepage-* ~/.local/bin/vibepage
```

## After install

```bash
vibepage login you@email.com
vibepage init --name my-app
vibepage deploy
```
