# ISO Crypt

Create an LUKS2 encrypted ISO from the command line!

Requires:

* libcryptsetup
* Python 3
* udftools (for the mkudffs command)
* losetup (util-linux)

## Install

```bash
sudo pip3 install isocrypt
```

## Example Usage

```bash
sudo python3 -misocrypt --verbose create 20MB --iso test.iso --force
```

add files to the directory (one will be provided if the command is successful)

```bash
sudo python3 -misocrypt --verbose close --dir ./fwqADIxNsBeRjalm/
```

Now, test.iso is encrypted and contains whatever you placed in the ./fwqADIxNsBeRjalm/ directory!
