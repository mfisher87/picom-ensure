Ensure picom is running.

# Motivation

I'm not sure why yet, but I often notice `picom` has mysteriously stopped
running and screen tearing is occurring. This script is a quick and easy way to
get it running again.


# Configuring

The script is not generalized, but it is trivial. Modify the `$CONFIG` variable
to point to your config, or otherwise modify the `picom` command to suit your
system.


# Installing

```
ln -s $PWD/picom-ensure /usr/local/bin/picom-ensure
```
