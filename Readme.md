# pibuild

Vagrant File to setup a build environment for Raspberry Pi images with Docker enabled.

```bash
vagrant up
vagrant ssh
sudo su -
cd /home/vagrant/pi-gen
./build.sh
```

The image will be in the directory `/home/vagrant/pi-gen/work/<DATE>-Raspbian/export-image`

Edit the `git clone https://github.com/alastairhm/pi-gen.git` line in the Vagrant file to point it back to the upstream repo or your desired repo.
