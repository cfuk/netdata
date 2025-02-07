<!--
title: "timex.plugin"
description: "Monitor the system clock synchronization state."
custom_edit_url: https://github.com/netdata/netdata/edit/master/collectors/timex.plugin/README.md
-->

# timex.plugin

This plugin monitors the system clock synchronization state on Linux nodes.

This plugin creates two charts:

-   System clock synchronization state
-   Computed time offset between local system and reference clock

## Configuration

Edit the `netdata.conf` configuration file using [`edit-config`](/docs/configure/nodes.md#use-edit-config-to-edit-configuration-files) from the [Netdata config directory](/docs/configure/nodes.md#the-netdata-config-directory), which is typically at `/etc/netdata`.

Scroll down to the `[plugin:timex]` section to find the available options:

```
[plugin:timex]
    # update every = 1
    # clock synchronization state = yes
    # time offset = yes
```


