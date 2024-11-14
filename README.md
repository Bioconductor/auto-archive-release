# Bioconductor Auto Archive Release

This repository contains automation scripts for archiving Bioconductor releases.

## Required GitHub Secrets

- `BIOC_VM_IP`: IP address of the VM where the sync will run
- `VM_SSH_KEY`: SSH private key for accessing the VM
- `RSYNC_PRIVATE_KEY`: Private key for rsync authentication
- `RCLONE_CONF_CONTENTS`: Complete rclone configuration file contents


## Usage

1. Go to Actions tab
2. Select "Sync Bioconductor Release" workflow
3. Click "Run workflow"
4. Enter the Bioconductor version to sync
5. Click "Run workflow"

