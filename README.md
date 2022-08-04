# gitlearn
how to setup git, visual code, python

install python

install visual code 

install git

setup ssh keys

from terminal: ssh-keygen -t ed25519 -C "your_email@example.com"

ssh-keygen -t ed25519 -C "your_email@example.com"

When you're prompted to "Enter a file in which to save the key," press Enter

> Enter passphrase (empty for no passphrase): [Type a passphrase]
> Enter same passphrase again: [Type passphrase again]

# start the ssh-agent in the background
$ eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519

**adding a new SSH key to your account on GitHub.com**

from terminal: clip < ~/.ssh/id_ed25519.pub
In the upper-right corner of any page, click your profile photo, then click Settings.
In the "Access" section of the sidebar, click SSH and GPG keys.
Click New SSH key or Add SSH key. 
In the "Title" field, add a descriptive label for the new key. For example, if you're using a personal Mac, you might call this key "Personal MacBook Air".
Paste your key into the "Key" field.
Click Add SSH key. 
done