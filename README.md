# Athrill apt repository

## How to install athrill

### OS requirements

- Ubuntu bionic 18.04(LTS)

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

```sh
sudo add-apt-repository "deb https://mikoto2000.github.io/athrill-apt bionic main"
```

### Install Athrill

```sh
apt-get update
apt-get install athrill-rh850f1x
```

