Shows
==============================

A show represents a series of episodes and many resources that are used to produce the episodes.

Every resourec in animan belongs to ONE show and may be used for multiple episodes. Resoures can be referenced each other.

The hierachy of the resource management structure is described below:

::

    shows
    ├── resource categories
    │   └── resources(&shots)
    │       └── files
    └── episodes
        └── shots
            ├── fla/xstage
            ├── audio
            └── animatic


.. toctree::
    :maxdepth: 1

    addNewShow
    rendering
    episodes/index
    resources/index


