# grub live boot menu entry #

Allows booting the system in live mode. Meaning, no persistent modifications
will be written to the disk. All changes stay in RAM.

Adds a grub live boot menu entry.

Existing grub boot entries stay unmodified.

No claims are made with regard to anti forensics.
## How to install `grub-live` using apt-get ##

1\. Add [Whonix's Signing Key](https://www.whonix.org/wiki/Whonix_Signing_Key).

```
sudo apt-key --keyring /etc/apt/trusted.gpg.d/whonix.gpg adv --keyserver hkp://ipv4.pool.sks-keyservers.net:80 --recv-keys 916B8D99C38EAF5E8ADC7A2A8D66066A2EEACCDA
```

3\. Add Whonix's APT repository.

```
echo "deb http://deb.whonix.org stretch main" | sudo tee /etc/apt/sources.list.d/whonix.list
```

4\. Update your package lists.

```
sudo apt-get update
```

5\. Install `grub-live`.

```
sudo apt-get install grub-live
```

## How to Build deb Package ##

Replace `apparmor-profile-torbrowser` with the actual name of this package with `grub-live` and see [instructions](https://www.whonix.org/wiki/Dev/Build_Documentation/apparmor-profile-torbrowser).

## Contact ##

* [Free Forum Support](https://forums.whonix.org)
* [Professional Support](https://www.whonix.org/wiki/Professional_Support)

## Payments ##

`grub-live` requires [payments](https://www.whonix.org/wiki/Payments) to stay alive!
