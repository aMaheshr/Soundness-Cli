# Soundness-Cli

![1500x500](https://github.com/user-attachments/assets/d29f386f-0a5f-4251-a336-63796d6256b3)


## How to Setup Soundness Cli Complete Guide 

---------------------------------------------------------------------
## Basic Steps :

- U need Vps server or Use ur Ubuntu or Gitpod
- [Join Soundness Discord Server](https://discord.gg/2VT2Rxy9)
- [Follow on X](https://x.com/SoundnessLabs)
  
## Lets Start 💻

### Open Terminal & start simply use Below Cmds

## System Update and Upgrade

```console
sudo apt update && sudo apt upgrade -y
```

## Install Rust

```console
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

## Set up Rust Environment

```console
source $HOME/.cargo/env
```

## Check Version

```console
rustc --version
cargo --version
```

## Persist Rust Environment

```console
echo 'source $HOME/.cargo/env' >> ~/.bashrc
```

```console
source ~/.bashrc
```

## Install Soundness Layer Cli with Single line Command

```console
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
```

```console
source ~/.bashrc
```

## Install & Update 

```console
soundnessup install
soundnessup update
```

## Generating a Key Pair

```console
soundness-cli generate-key --name my-key
```

### Set a Password 

- Copy & Save ur Public Key & mnemonic phrase

- Go to Soundness Discord Server & testnet Access Channel
  - simply type !access paste ur public key

-------------------------------------------------------------------------

## Import Key Pair 

```console
soundness-cli import-key --name my-key
```

## Listing Key Pairs

```console
soundness-cli list-keys
```

## Exporting Key Mnemonic

```console
soundness-cli export-key --name my-key
```

Thats it ✔️

![GmalZ0Za8AEhrPA](https://github.com/user-attachments/assets/29e1dde8-1331-487f-87ee-a257dba5683c)

Checkout Official Cli Installation : https://github.com/SoundnessLabs/soundness-layer/tree/main/soundness-cli

### [More Info Follow on X](https://x.com/cryptocrocks)
