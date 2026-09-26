# Resilient queue portability fixture

This small repository checks that queue metadata stays portable when a worker
stores an embedded Git worktree for recovery tests. The embedded metadata is
under `bare/`, and its test worktree is under `bare/worktree/`.

The dated project history records the maintenance checks used during releases.
