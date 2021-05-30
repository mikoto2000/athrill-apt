# Athrill apt repository

## How to install athrill

### OS requirements

- Ubuntu bionic 18.04(LTS)
- Ubuntu focal 20.04(LTS)
- Debian buster

### Install required packages

```sh
sudo apt-get update
sudo apt-get install curl gnupg2 software-properties-common
```

### Add Athrill repository GPG key

```sh
curl -fsSL https://mikoto2000.github.io/athrill-apt/athrill.gpg.key | sudo apt-key add -
```

### Add Athrill repository

#### bionic

```sh
sudo add-apt-repository "deb https://mikoto2000.github.io/athrill-apt/ubuntu bionic main"
```

#### focal

```sh
sudo add-apt-repository "deb https://mikoto2000.github.io/athrill-apt/ubuntu focal main"
```

#### buster

```sh
sudo add-apt-repository "deb https://mikoto2000.github.io/athrill-apt/debian buster main"
```

### Install Athrill

```sh
sudo apt-get update
sudo apt-get install athrill-rh850f1x
```

