# GPG Sync Configuration

## About GPG Sync

[GPG Sync](https://github.com/firstlookmedia/gpgsync) is a program for Linux and MacOS that frees you from manually managing the PGP keys of everyone in your organization.

## Install Client

See https://github.com/firstlookmedia/gpgsync#getting-gpg-sync

### MacOS

Download and install the client from: https://github.com/firstlookmedia/gpgsync/releases

### Linux (Debian/Ubuntu/Mint)

    sudo apt install -y python3-pyqt5 python3-nose python3-stdeb python3-requests python3-socks python3-packaging python3-dateutil gnupg2
    git clone https://github.com/firstlookmedia/gpgsync.git
    cd gpgsync
    ./install/build_deb.sh
    sudo dpkg -i deb_dist/gpgsync_*.deb

## Configure Client

A screenshot can be found here: https://github.com/firstlookmedia/gpgsync/wiki/Configuring-GPG-Sync-on-everyone's-computers and you only have to enter the information from the table below.

| Field            | Value                                                                            |
| ---------------- | -------------------------------------------------------------------------------- |
| GPG Fingerprint  | EEC8A807595873988AC5E6E1E3F2A04C7C9671C7                                         |
| Fingerprints URL | https://raw.githubusercontent.com/ubirch/ubirch-gpg-sync/master/fingerprints.txt |

## Download Signing Key

If necessary you can either import the signing key from this directory or [download it from a keyserver](https://sks-keyservers.net/pks/lookup?op=get&search=0xE3F2A04C7C9671C7).

