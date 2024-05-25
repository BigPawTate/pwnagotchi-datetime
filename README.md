# pwnagotchi Date and Time
Display the date and time on your pwnagotchi waveshare v4 dashboard. <br>
Requires an RTC module!

### with memtemp enabled<br>
  - ![image](https://github.com/BigPawTate/pwnagotchi-datetime/assets/116862308/5227b2c8-3c9d-4a35-9184-5292abfeab92)

### no memtemp<br>
  - ![image](https://github.com/BigPawTate/pwnagotchi-datetime/assets/116862308/2c290cdb-0abd-47ee-bcab-9ab632f4e2fa)




## Installation

To install, first set your directory for custom plugins in your config file.  
The default directory for jayofelony v2.8.9 is `/etc/pwnagotchi/custom-plugins/` <br>
Find or add `main.custom_plugins = "/etc/pwnagotchi/custom-plugins/"` Initially, it may be empty.

After that, add `clock.py` to that folder.
Finally, enable it in your config.toml by adding the following line:

```toml
main.plugins.clock.enabled = true
```

