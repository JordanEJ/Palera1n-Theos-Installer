> ## WARNING: This is a work in progress. It does not work at the moment.

# Palera1n-Theos-Installer
The theos installer script slight rewritten to work with palera1n.

### Explanation:
When trying to install theos on iOS I kept on getting errors because the Palera1n strap repo is apparently unsigned. you could normally fix this by removing that repo but Palera1n strap is required and therefore unremovable. I have rewritten it so that it allows you to install even with unsigned repos.

### Usage:
Just follow the installation instructions from the <a href="https://theos.dev/docs/installation-ios">official theos docs</a> but use:
```
bash -c "$(curl -fsSL https://raw.githubusercontent.com/JordanEJ/Palera1n-Theos-Installer/main/install-theos)"
```
Instead of:
```
bash -c "$(curl -fsSL https://raw.githubusercontent.com/theos/theos/master/bin/install-theos)"
```
