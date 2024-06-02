chmod 600 id_ed25519.pub id_ed25519
git config --global user.name "Angelina"
git config --global user.email "142142912+angelinasharma@users.noreply.github.com"
git config --global gpg.format ssh
git config --global commit.gpgsign true
git config --global user.signingkey ~/.ssh/id_ed25519.pub


- get id_ed25519 and id_ed25519 from bitwarden 


- check if it worked using 
    ssh -T git@github.com


- while cloning existing repositories use ssh url  