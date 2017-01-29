# SSHuttle Control Scripts

Control scripts which allow you to easily run sshuttle in the background. Allows easy start, stop, and viewing of open connections.

This is still in development, most features are not implemented yet.

Here's an example of a currently working command - this will tunnel (tnl) all your traffic through the SSH host.
``` bash
# To start:
sshuttle-ctrl tnl start SSHHOST

# To stop:
sshuttle-ctrl tnl stop SSHHOST

# To list connections:
sshuttle-ctrl tnl list

```
