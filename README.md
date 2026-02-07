### backup_system

A comprehensive backup automation system built on [Restic](https://github.com/restic/restic) with dual-repository redundancy. Backs up configuration files, code, documents, and system state to both a local Raspberry Pi (SFTP) and [Backblaze B2](https://www.backblaze.com/cloud-storage) (cloud). Features include automated retention policies, integrity checking, and single-command execution of all backup jobs.

<!-- CODE_STATISTICS_START -->

### Code Statistics

```
--------------------------------------------------------------------------------
Language                      files          blank        comment           code
--------------------------------------------------------------------------------
Bourne Again Shell               17            140            159            297
Markdown                          1              8              4             37
--------------------------------------------------------------------------------
SUM:                             18            148            163            334
--------------------------------------------------------------------------------
```
<!-- CODE_STATISTICS_END -->

<!-- PROJECT_STRUCTURE_START -->

### Project Structure

```
backup_system
├── logs
├── README.md
└── scripts
    ├── backup-all
    ├── backup-check
    ├── bash-backup
    ├── direnv-backup
    ├── helix-backup
    ├── icon-backup
    ├── ipython-backup
    ├── nvim-backup
    ├── package-backup
    ├── powershell-backup
    ├── python-backup
    ├── sql-backup
    ├── sqliterc-backup
    ├── vault-backup
    ├── wt-backup
    ├── zellij-backup
    └── zshrc-backup

3 directories, 18 files
```
<!-- PROJECT_STRUCTURE_END -->
