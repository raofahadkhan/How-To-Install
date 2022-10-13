# How To Install Github Desktop, Yarn, Surge on Ubuntu::

In this repo i have put all the command that are needed to install the softwares, utilities and packages that are needed in our daily life.
__________________________________________________________________________________________________________________
## How To Install GitHub Desktop on Ubuntu:

**It is a two step process:**

### 1.To set up the package repository, run these commands:

```
wget -qO - https://packagecloud.io/shiftkey/desktop/gpgkey | sudo apt-key add -

sudo sh -c 'echo "deb [arch=amd64] https://packagecloud.io/shiftkey/desktop/any/ any main" > /etc/apt/sources.list.d/packagecloud-shiftky-desktop.list'

sudo apt-get update
```

### 2.Then install GitHub Desktop:

`sudo apt install github-desktop`
__________________________________________________________________________________________________________________

## How To Install Yarn: 
```
curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -

echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
```

__________________________________________________________________________________________________________________

## How To Install NodeJS LTS Version:

```
curl -sL https://deb.nodesource.com/setup_lts.x | sudo -E bash -

sudo apt-get install -y nodejs
```
__________________________________________________________________________________________________________________

## How To Install Surge:

```
sudo npm install surge -g

surge login

surge list
```
__________________________________________________________________________________________________________________

## SNAP Essential Commands:

```
how to see the changes that are going on or being made by snap:
===> snap changes

how to abort an ongoing change:
===> sudo snap abort snap-Id

how to install a package from snap-store:
===> sudo snap install package-name

```
__________________________________________________________________________________________________________________

### That's it and if you find that repo useful give it a STAR.
