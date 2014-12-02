Changelog for Reinout's ansible setup for vagrant VMs
=====================================================

0.1 (unreleased)
----------------

- Started based on old fabfile script.

- Installing my dotfiles automatically.

- In the tools dir, we use the latest dotfiles, which allows treating
  ``~/.ssh`` as a package. So only the files in ``~/Dotfiles/ssh`` are copied,
  which allows us to keep the vagrant ssh pubkey in
  ``~/.ssh/authorized_keys``. The main task ensures it is (still) there. And
  it now also copies our own ssh key.
