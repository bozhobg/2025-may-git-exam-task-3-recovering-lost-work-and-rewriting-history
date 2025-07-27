## Recovering Lost Work and Rewriting Git History
1. Initial state local remote with file changes on branch
2. Resetting HEAD~2 and force pushing into remote
![1-initial-state-force-push-of-old-version.png](./readme-files/1-initial-state-force-push-of-old-version.png)
3. Restoring lost commits and squashing locally using interactive rebase
![2-restoring-local-history-1.png](./readme-files/2-restoring-local-history-1.png)
![2-restoring-local-history-2.png](./readme-files/2-restoring-local-history-2.png)
![2-restoring-local-history-3.png](./readme-files/2-restoring-local-history-3.png)
![2-restoring-local-history-4.png](./readme-files/2-restoring-local-history-4.png)
4. Restoring lost commits and editing "sensitive data" (using git reflog again)
![3-restoring-local-history-with-edit-1.png](./readme-files/3-restoring-local-history-with-edit-1.png)
![3-restoring-local-history-with-edit-2.png](./readme-files/3-restoring-local-history-with-edit-2.png)
![3-restoring-local-history-with-edit-3.png](./readme-files/3-restoring-local-history-with-edit-3.png)
![3-restoring-local-history-with-edit-4.png](./readme-files/3-restoring-local-history-with-edit-4.png)
5. Restoring timeline to remote repo push with lease
![4-restoring-remote-timeline.png](./readme-files/4-restoring-remote-timeline.png)
6. git log and git reflog
![05-git-log-git-reflog.png](./readme-files/05-git-log-git-reflog.png)