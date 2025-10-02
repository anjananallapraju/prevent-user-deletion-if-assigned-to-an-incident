# prevent-user-deletion-if-assigned-to-an-incident
prevent user deletion if assigned to an incident

In an IT Service Management environment, users are frequently assigned to incidents for issue resolution and tracking. However, the current system lacks a validation mechanism to prevent the deletion of a user who is still actively assigned to incidents. This can lead to broken data references, loss of accountability, and disruption in workflow continuity.
There is a need to implement a safeguard that prevents such deletions unless all assigned incidents are closed or reassigned.
