Reinout's ansible setup for local vagrant VMs
=============================================

I have a mac laptop and I use vagrant + vmware fusion for most of my
development work. You can look at `my VM setup on github
<https://github.com/reinout/vm>`_.

The VMs are provisioned with ansible. I use some common ansible roles from
work for that. What's missing after those is some local setup and
customization. That's what the ansible role here does!

- Adding my public ssh key so that I can log in normally.

- Installing some extra packages such as emacs.

- Installing dotfiles (from my custom private Dotfiles collection).

- Installing some python tools and shell scripts (from
  https://github.com/reinout/tools).


License: BSD. Created by `Reinout van Rees <http://reinout.vanrees.org>`_.
