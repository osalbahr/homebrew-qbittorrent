# [qBittorrent](https://github.com/qbittorrent/qBittorrent) Homebrew repository

## How do I install these formulae?

Add this tap by executing 
```
brew tap qbittorrent/qbittorrent https://github.com/qbittorrent/qBittorrent
```

And then install qBittorrent formula:
```
brew install qbittorrent/qbittorrent/qbittorrent
```

Subsequently given lack of notarization it's necessary to get rid of FileVault complaints:
```
sudo xattr -rd com.apple.quarantine /Applications/qBittorrent.app
```

## Brew Documentation
`brew help`, `man brew`, or check [Homebrew's documentation][brew-docs].

[brew]: https://brew.sh
[brew-docs]: https://docs.brew.sh
