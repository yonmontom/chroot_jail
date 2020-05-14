## SM user management
#### Chroot Jail configuration for SM users 
######  - Create chroot jail home 
######  - Create jail sub-directories  dev/ bin/ etc/ lib64/
######  - Create nodes 
######  - Copy Bash commands to $CHROOTHOME/lib64/ directory
######  - Copy Bash command libraries to $CHROOTHOME/lib64/  (os dependent?)
######  - Create group for chroot users 
######  - Create user -s /bin/bash -g $chrootgroup 
######  - Add chroot jail config to ssh config 
######  - Mount log directories in to chroot home 
######  - Restart ssh 
