```bash
repo init -u ssh://git@github.com/KiwawaXC/manifest -b tiramisu
```
Once you have chosen a source branch, you can proceed with the synchronization using the following command:
```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
