# [<img src="https://ipinfo.io/static/ipinfo-small.svg" alt="IPinfo" width="24"/>](https://ipinfo.io/) IPinfo CLI

This is the official CLI for the [IPinfo.io](https://ipinfo.io) IP address API,
allowing you to:

- Look up IP details in bulk or one-by-one.
- Look up ASN details.
- Summarize the details of up to 1000 IPs at a time.
- Open a map of IP locations for any set of IPs.
- Filter IPv4 & IPv6 addresses from any input.
- Print out IP lists for any CIDR or IP range.
- And more!

## Installation

The `ipinfo` CLI is available for download via multiple mechanisms.

### macOS

```bash
brew install ipinfo-cli
```

OR to install the latest `amd64` version without automatic updates:

```bash
curl -Ls https://github.com/ipinfo/cli/releases/download/ipinfo-3.3.1/macos.sh | sh
```

### Ubuntu PPA

_Note_: this installs our full suite of binaries and keeps them up-to-date.

```bash
echo "deb [trusted=yes] https://ppa.ipinfo.net/ /" | sudo tee  "/etc/apt/sources.list.d/ipinfo.ppa.list"
sudo apt update
sudo apt install ipinfo
```

### Debian / Ubuntu

_Note_: this is a one-time installation; updates are not automatic. Use the PPA
for automatic updates.

```bash
curl -Ls https://github.com/ipinfo/cli/releases/download/ipinfo-3.3.1/deb.sh | sh
```

where `{arch}` can be 386, amd64, arm, or 
### Arch linux

```bash
git clone https://aur.archlinux.org/ipinfo-cli.git
makepkg -si
```

### Windows Powershell

_Note_: run powershell as administrator before executing this command.


### Scoop

```bash
scoop install ipinfo-cli
```

### Docker

```bash
docker run --rm -it ipinfo/ipinfo:3.3.1
```

To save the CLI's config, add `-v "/path_to_config:/root/.config/ipinfo"`. For
example, the following command saves the config to the `ipinfo` directory 

### Using `go install`

Make sure that `$GOPATH/bin` is in your `$PATH`, because that's where this gets
installed:


### Using `curl`/`wget`


The following OS & arch combinations are supported
```bash
# for Windows, use ".zip" instead of ".tar.gz"



### Using `
Replace `<path>` with the required location.

## Additional CLIs



Currently these subcommands are separately shipped:

| CLI        | Version                                                               |
| ---------- | --------------------------------------------------------------------- |
| grepip     | [1.2.3](https://github.com/ipinfo/cli/releases/tag/grepip-1.2.3)      |
| grepdomain | [1.0.0](https://github.com/ipinfo/cli/releases/tag/grepdomain-1.0.0)  |
| matchip    | [1.0.0](https://github.com/ipinfo/cli/releases/tag/matchip-1.0.0)     |
| prips      | [1.0.0](https://github.com/ipinfo/cli/releases/tag/prips-1.0.0)       |
| cidr2range | [1.2.0](https://github.com/ipinfo/cli/releases/tag/cidr2range-1.2.0)  |
| cidr2ip    | [1.0.0](https://github.com/ipinfo/cli/releases/tag/cidr2ip-1.0.0)     |
| range2cidr | [1.3.0](https://github.com/ipinfo/cli/releases/tag/range2cidr-1.3.0)  |
| range2ip   | [1.0.0](https://github.com/ipinfo/cli/releases/tag/range2ip-1.0.0)    |
| randip     | [1.1.0](https://github.com/ipinfo/cli/releases/tag/randip-1.1.0)      |
| splitcidr  | [1.0.0](https://github.com/ipinfo/cli/releases/tag/splitcidr-1.0.0)   |
| mmdb       | [1.4.2](https://github.com/ipinfo/mmdbctl/releases/tag/mmdbctl-1.4.2) |



### Disabling Color Output

### Color on Windows