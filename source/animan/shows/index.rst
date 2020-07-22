Shows
==============================

A show represents a series of episodes, broken into seasons, and the many resources that are used to produce the episodes.

Every resource in animan belongs to ONE show and may be used for multiple seasons and episodes. Resoures reference each other.

The hierachy of the resource structure is described below:

::

    shows
    ├── resource categories
    │   └── resources(&shots)
    │       └── files
    └── seasons
    │   └── episodes
    │       └── shots
    │           ├── fla/xstage
    │           ├── audio
    │           └── animatic


.. toctree::
    :maxdepth: 1

    addNewShow
    rendering
    episodes/index
    resources/index
