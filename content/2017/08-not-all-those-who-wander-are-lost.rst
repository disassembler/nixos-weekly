#08 - Not all those who wander are lost
############################################

:date: 2017-05-19
:description: Not all those who wander are lost - J.R.R. Tolkien


Welcome to another edition of NixOS Weekly.


Major announcements include NixCon 2017 and the old wiki migration.
This edition adds a new Tooling section for possibly useful
Nix-related tools in addition to News, Jobs, Reading, and Events.


News
====

- `NixCon 2017`_ October 28-31, Munich.

  Call for participation is open until July 31.


- The `Wiki <https://nixos.org/nixos/wiki.html>`_ is dead. Long live
  the `Wikis <https://github.com/nixos-users/wiki/wiki>`_!


  `This <https://github.com/NixOS/nixos-org-configurations/pull/30>`_
  is the change that disable the wiki.

  The old wiki has been for a while now with `ongoing work
  <https://github.com/NixOS/nixpkgs/milestone/8>`_ on updating and
  migrating the content.

  Current options are the `Community Cookbook
  <https://nix-cookbook.readthedocs.io/en/latest/index.html>`_ and the
  `nixos-users Wiki <https://github.com/nixos-users/wiki/wiki>`_. The
  latter is editable by anyone with a GitHub account.


- Nix has a thankful community.

  Profpatsch did some quick analysis of IRC messages.
  Summary:

  - `1.9% contain the word "thank" <https://twitter.com/Profpatsch/status/862303014601846784>`_
  - `2.4% last year <https://twitter.com/grhmc/status/862304182002479105>`_

.. _`NixCon 2017`: http://nixcon2017.org/


Jobs
====

- `IOHK is hiring <https://iohk.io/careers/#fk06gld>`_

- `CircuitHub is hiring (Haskell+NixOS) <https://circuithub.com/careers/haskellers#block-27f97af4532dee9c4127>`_


Reading
========

- `Intro to Nix Channels and Reproducible NixOS Environment <http://matrix.ai/2017/03/13/intro-to-nix-channels-and-reproducible-nixos-environment/>`_

  See also the `Cookbook
  <http://nix-cookbook.readthedocs.io/en/latest/faq.html#how-to-pin-nixpkgs-to-a-specific-commit-branch>`_.

- `Use NixOS for macOS TimeMachine backups <http://grahamc.com/blog/timemachine-backups-linux-nixos>`_.

- `Building Maven Packages with Nix <https://ww.telent.net/2017/5/10/building_maven_packages_with_nix>`_

  See also the `mvn2nix mailing list discussion <https://mailman.science.uu.nl/pipermail/nix-dev/2017-May/023677.html>`_.

- `My Journey into Nix <https://adelbertc.github.io/posts/2017-04-03-nix-journey.html>`_

  lobste.rs `discussion <https://lobste.rs/s/nw8luo/my_journey_into_nix>`_

- `DistroWatch review of NixOS <https://distrowatch.com/weekly.php?issue=20170515>`_

- `Falling in love with NixOS <https://medium.com/@GauthierPLM/falling-in-love-with-nixos-36db4e50171e>`_


Tooling
=======

- `pnix-shell.sh <https://gist.github.com/aherrmann/51b56283f9ed5853747908fbab907316>`_: creates gc-roots for all dependencies of a shell.nix.

- `nix-package-search <https://gist.github.com/olejorgenb/0c3bafa3c7b63d1a2f83ee13582de7b9/>`_: cached queries for ``nix-env -qa``.

- `nix-zsh-completions <https://github.com/spwhitt/nix-zsh-completions>`_: ZSH completions for Nix and NixOS tools.

- `Auto install/run
  <https://mailman.science.uu.nl/pipermail/nix-dev/2017-May/023569.html>`_
  missing programs.





Events / Meetups
==================

- `NixOps Meetup <https://www.meetup.com/Munich-NixOS-Meetup/events/239835348/>`_ May 26, Munich

  Topics: the NixOps container backend. Possible hackathon afterwards.




Editor's corner
===============

This work would not be possible without the many contributions of the community.

You can help! Create or comment on the `pull request`_ for the next
edition or help with the `issue tracker`_ to add other improvements.

.. _`pull request`: https://github.com/NixOS/nixos-weekly/pulls
.. _`issue tracker`: https://github.com/NixOS/nixos-weekly/issues
