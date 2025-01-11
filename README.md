# pwnagotchi Date and Time

Display the date and time on your pwnagotchi waveshare v4 dashboard.

Requires an RTC module!


### with memtemp enabled<br>
  - ![image](https://github.com/BigPawTate/pwnagotchi-datetime/assets/116862308/5227b2c8-3c9d-4a35-9184-5292abfeab92)

### no memtemp<br>
  - ![image](https://github.com/BigPawTate/pwnagotchi-datetime/assets/116862308/2c290cdb-0abd-47ee-bcab-9ab632f4e2fa)

### Observe the time your pwnagotchi went offline
  - e-ink display will show the time when pwnagotchi lost power


## Installation

To install, first set the directory for custom plugins in your config file.  

Update `config.toml` to the correct custom-plugins directory:  

```
main.custom_plugins = "/etc/pwnagotchi/custom-plugins/"
```

The default custom-plugins directory for jayofelony v2.8.9 is `/etc/pwnagotchi/custom-plugins/` 

After that, add the `clock.py` file to the custom-plugins directory.

Finally, enable it in your `config.toml` by adding the following line:

```toml
main.plugins.clock.enabled = true
```

Restart the pwnagotchi service to refresh the dashbaord with the date and time enabled:  

```
sudo systemctl restart pwnagotchi
```

