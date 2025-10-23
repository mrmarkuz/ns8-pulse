# ns8-pulse

[Pulse](https://github.com/rcourtman/Pulse) is a real-time monitoring for Proxmox VE, Proxmox Mail Gateway, PBS, and Docker infrastructure with alerts and webhooks.

## Install

Instantiate the module with:

    add-module ghcr.io/mrmarkuz/pulse:latest 1

The output of the command will return the instance name.
Output example:

    {"module_id": "pulse1", "image_name": "pulse", "image_url": "ghcr.io/nethserver/pulse:latest"}

## Configure

Configure the FQDN and browse to it.

## Uninstall

To uninstall the instance:

    remove-module --no-preserve pulse1
