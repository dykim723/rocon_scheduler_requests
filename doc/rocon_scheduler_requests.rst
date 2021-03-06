rocon_scheduler_requests
------------------------

.. module:: rocon_scheduler_requests

This is the top-level namespace of the rocon_scheduler_requests_ ROS
package.  

It exports the primary interfaces for requester or scheduler node
implementations.  These classes provide relatively simple programming
interfaces, not requiring detailed knowledge of scheduler request
messages or state transitions.  Their documentation includes usage
examples:

 * :py:class:`.Requester`
 * :py:class:`.Scheduler`

The package-specific exceptions are also defined here:

 * :py:exc:`.TransitionError`
 * :py:exc:`.WrongRequestError`

The following pages describe lower-level interfaces:

.. toctree::
   :maxdepth: 1

   common
   exceptions
   requester
   scheduler
   transitions

.. _rocon_scheduler_requests: http://wiki.ros.org/rocon_scheduler_requests
