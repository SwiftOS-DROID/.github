![INFO](https://raw.githubusercontent.com/SwiftOS-DROID/.github/main/web/infocard.png)
# SwiftOS

SwiftOS is a ROM that focuses on having unique features without compromising the performance of AOSP

### Quick Sync Source
```bash
#Sync all commits (Useful For contributions)
repo init -u https://github.com/SwiftOS-DROID/sw_manifest -b 13
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags

#Sync by fetching only the most recent commits (can save storage space)
repo init -u https://github.com/SwiftOS-DROID/sw_manifest -b 13 --depth=1
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Our Official Community
- [**Discord**](https://discord.gg/YwFWDbDD2u)
- [**Telegram**](https://t.me/SwiftOS)