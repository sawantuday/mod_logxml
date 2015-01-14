mod_logxml
==========

mod_logxml for ejabberd 13.12 - log all packets to xml file.


Sample configuration in yml syntax 
```
mod_logxml:
    stanza: [message, other]
    direction: [external]
    orientation: [send, recv]
    logdir: "/var/jabber/logs/"
    timezone: universal
    rotate_days: 1
    rotate_megs: 100
    rotate_kpackets: no
    check_rotate_kpackets: 1
```
