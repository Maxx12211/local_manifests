# local_manifests
Clone the repository to the right path

```bash
git clone https://github.com/Maxx12211/local_manifests -b rova2 .repo/local_manifests
```


# After removing them do a repo sync

```bash
  repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
