# DevOps Git Practice Repo

This repository demonstrates essential Git workflows for DevOps engineers.

## Operations Practiced

### 1. Merge with Conflict Resolution
- Created feature/add-logging branch
- Created feature/add-monitoring branch
- Both modified deploy.sh differently
- Resolved conflict by combining both changes
- Successfully merged to main

### 2. Stash Workflow
- Created feature/add-alerts branch
- Made untracked changes (alerts.sh)
- Stashed work using: git stash --include-untracked
- Switched branches without losing work
- Restored work using: git stash pop
- Committed stashed changes

### 3. Rebase Operations
- Created feature/add-config branch
- Made changes on main branch
- Rebased feature/add-config onto updated main
- Merged rebased feature back to main

## Scripts in This Repo

- **deploy.sh**: Deployment automation with logging and monitoring
- **health-check.sh**: System health monitoring
- **backup.sh**: Backup automation
- **alerts.sh**: Alert system for monitoring
- **config.sh**: Configuration utility

## How to Use

```bash
./deploy.sh
./health-check.sh
./backup.sh
./alerts.sh
./config.sh
```

## Author
Iniya - DevOps Engineer
