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


Other future features include:
 * _lan_ command - tunnel only lan traffic to host, not all traffic
   * For when you have a slow WAN connection on the remote host, so you don't want to send non-important traffic over that link
 * _tnlbut_ command - same as tunnel, but excluding some subnet
   * For when you want to tunnel all your traffic to a remote host, but still need to access local resources on your local LAN
