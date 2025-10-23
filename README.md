# ns8-pulse

[Pulse](https://github.com/rcourtman/Pulse) is a real-time monitoring for Proxmox VE, Proxmox Mail Gateway, PBS, and Docker infrastructure with alerts and webhooks.

## Install

The app is installable via Software Center after adding the [mrmarkuz repo](https://repo.mrmarkuz.com/).

## Configure

Configure the FQDN and browse to it. Then you can setup credentials and start discovering your Proxmox environment.

## Uninstall

It's possible via Software Center or CLI:

    remove-module --no-preserve pulse1
