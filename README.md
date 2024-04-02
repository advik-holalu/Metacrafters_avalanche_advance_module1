# Metacrafters-Avalance-Advanced1

I have created my own local subnet with ChainID 9999 and Token Symbol ARH. I have used the template provided by Metacrafters and this contract has been deployed to that subnet.

## Installation

### Compatibility

The tool has been tested on Linux and Mac. Windows is currently not supported.

### Instructions

To download a binary for the latest release, run:

```sh
curl -sSfL https://raw.githubusercontent.com/ava-labs/avalanche-cli/main/scripts/install.sh | sh -s
```

The binary will be installed inside the `~/bin` directory.

To add the binary to your path, run

```sh
export PATH=~/bin:$PATH
```

To add it to your path permanently, add an export command to your shell initialization script (ex: .bashrc).


## Quickstart

After installing, launch your own custom subnet:

```bash
avalanche subnet create <subnetName>
avalanche subnet deploy <subnetName>
```

Shut down your local deployment with:

```bash
avalanche network stop
```
we will get RPCURL, ChainID, Token Symbol and private key in our terminal after deploying the subnet.

Hence, we will use this information to add a network in Metamask and import test tokens using the private key

## Authors

* Advik Holalu- advikholalu@gmail.com

## License

This project is licensed under the MIT License
