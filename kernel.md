#### Swappiness and cache pressure

Edit `/etc/sysctl.conf` and change the values for `swappiness` and `vfs_cache_pressure`.
    
    vm.swappiness=10
    vm.vfs_cache_pressure=50
