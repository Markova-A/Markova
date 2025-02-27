## how to kreate ssh key

1. Download git.
2. Open git shell in the definite folder
3. Enter: ssh-keygen -t ed25519 -C "your_email@example.com"
4. Tener key file name if you need it. Do not use password
5. Run ssh agent. Enter: eval "$(ssh-agent -s)"
6. Add ssh. Enter: ssh-add ~/.ssh/id_ed25519

## how to add ssh key to the website

1. In settings of your profile find ssh and gpg keys
2. Click new ssh key or add ssh key
3. In title add description
4. In key add text from file in the folder .ssh
5. Click add ssh

## how to clone repository

1. In repository click code - ssh and copy the text
2. In terminal use comand git clone with this copied text