### backup_system

A comprehensive backup automation system built on [Restic](https://github.com/restic/restic) with dual-repository redundancy. Backs up configuration files, code, documents, and system state to both a local Raspberry Pi (SFTP) and [Backblaze B2](https://www.backblaze.com/cloud-storage) (cloud). Features include automated retention policies, integrity checking, and single-command execution of all backup jobs.

<!-- CODE_STATISTICS_START -->

### Code Statistics

```
--------------------------------------------------------------------------------
Language                      files          blank        comment           code
--------------------------------------------------------------------------------
Bourne Again Shell               19            158            179            328
Markdown                          1              8              4             39
--------------------------------------------------------------------------------
SUM:                             20            166            183            367
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
    ├── database-backup
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
    ├── ssh-backup
    ├── vault-backup
    ├── wt-backup
    ├── zellij-backup
    └── zshrc-backup

3 directories, 20 files
```
<!-- PROJECT_STRUCTURE_END -->
