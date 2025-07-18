# Kali NetHunter Kernel Builder

## Installation

Clone this repository into your kernel source tree, e.g.

```console
$ cd nethunter_a21s
$ git clone https://github.com/BasGame1/nethunter_kernel_a21s.git
```

**cd** into `kali-nethunter-kernel/`, open `config` and make sure that you are happy with all the settings.

Important: Changes should not be made in this file. Copy it across to `local.config` and delete everything except the parameters you would like to change. Change those parameters and save it.

The settings in `local.config` overwrites `config` but will itself not be overwritten by updates.
