# Kubevela asdf Plugin

This is the plugin repo for [asdf-vm/asdf](https://github.com/asdf-vm/asdf.git)
to manage [oam-dev/kubevela](https://github.com/oam-dev/kubevela.git).

## Install

After installing [asdf](https://github.com/asdf-vm/asdf),
you can add this plugin like this:

```bash
asdf plugin-add kubevela https://github.com/josephlim75/asdf-kubevela.git
asdf list-all kubevela
asdf install kubevela v1.2.1
asdf global kubvela v1.2.1
vela version
kubectl vela version
`````