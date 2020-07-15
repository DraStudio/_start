# Terminal Commands

## Sass Preferred Output
sass --watch style.scss:_site/css/style.min.css --style compressed




## Start 11ty server
eleventy --serve




## Git - Recheck Working Tree
git rm . -r --cached
git add .
git commit -m "fixed untracked files"




## Misc
ping yahoo.com
curl -O http://



## macOS
### Show hidden files (though Mojave added Command + Shift + . shortcut)
defaults write com.apple.finder AppleShowAllFiles YES

### Add Dock Spacer
defaults write com.apple.dock persistent-apps -array-add '{tile-data={}; tile-type="spacer-tile";}'

killall Dock

### Change to Suck Minimize
defaults write com.apple.dock mineffect -string suck