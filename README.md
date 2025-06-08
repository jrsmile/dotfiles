!#/bin/sh
mkdir -p ~/.dotflies/bin
curl -fLo ~/.dotfiles/bin/yadm https://github.com/yadm-dev/yadm/raw/master/yadm && chmod a+x ~/.dotfiles/bin/yadm
yadm clone https://github.com/jrsmile/dotfiles.git
yadm decrypt
