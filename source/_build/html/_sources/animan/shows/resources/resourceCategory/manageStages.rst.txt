.. _manageStages:

Manage Resource Category Stages
=================================

Privilege required:
 - admin
 - or EDIT CATEGORY privilege


Each :ref:`Resource Category<resourceCategory>` has a list of stages that each of resource belongs to this category needs to go through.



.. topic:: :icon:`info` **Finish Stage**

    A "Finish" stage must in place and its type must be set to "admin" so no one should work on it when it's on Finish stage.


.. topic:: :icon:`info` **Animation Stage**

    An "Animation" stage must in place for the system created :ref:`shot` stage.
    This stage is a key element that animan calculate members' work quota.


Stage Types
++++++++++++++

Every Stage has a type of either admin/work/review type.

#. admin
 The stage of admin type is a no-one-work-on-it stage.
 This is useful when the resource is still in discussion stage before anyone work on it, or a finish stage.
#. work
 This stage determine a worker who is assigned to the stage should start to work on it.
#. review
 The review stage is usually placed after a work stage.
 When a resource is on this stage, a reviewer that is assigned to this stage should donwload the file, review it, and either approve and move to next stage, or reject to move back to previous work stage.

Assign Members
+++++++++++++++++

The editor of Resource Category is responsible to assign member to the stages.

For "work" stage:

- assign "Assigner"
 The assigner of the work stage is able to assign a worker from the worker list to a resource.

- assign "Worker"
 The member in this list is listed when assigner is assigning a worker to a work stage.

For "review" stage:

- assign "reviewer"

 All reviewers in this list can review, approve or reject the work.