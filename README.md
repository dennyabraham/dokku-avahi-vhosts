# dokku-avahi-vhosts-plugin
A Dokku/Dokku-alt plugin that adds vhosts to mDNS/Zeroconf/Bonjour/Avahi, useful when you're deploying to a staging server on a LAN (or a local VM).

Assumes you're using the <appname>.hostname.local format, and adds/removes hosts upon container creation.

Sadly, Windows and Mac clients don't seem to recognize these aliases.
