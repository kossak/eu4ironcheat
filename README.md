# eu4ironcheat
Scripts for creating backups and restoring them for Europa Universalis 4 for Unix systems

Path for saved games is stored in env `EU4_SAVED_GAMES_PATH`, which default value `${HOME}/Documents/Paradox Interactive/Europa Universalis IV/save games` 
## Usage:
Add to your `~/.bash_profile`
    
    source $PATH_TO_SCRPITS/eu4ironcheatrc
    
#### Backup: 
   
    eu4backup SOURCE_NAME [TARGET_NAME]
By default target backup file name is build as `SOURCE_NAME-backup-UNIX_TIMESTAMP` 
    
#### Restore:
    
    eu4restore BACKUP_FILE TARGET_SAVE


### TODO:
- Daemon for auto-backup of running game
