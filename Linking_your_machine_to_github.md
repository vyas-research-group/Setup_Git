# Generating_an_ssh_keypair

In your local machine's command line or terminal type the following command:

```shell
ssh-keygen -t ed25519 -C "your_email@example.com"
```

You will be asked what directory to put the key. Press enter for the default. **But take note of where it is stored**
You will also be asked for a passphrase, you may enter one if you like or leave it blank and press enter.

Then you will go to the directory where the keys were generated and open the ssh key that ends in the .pub extension. Copy the text inside this file.

Next in your github click your profile picture to get this dropdown menu:
![[Profile_Dropdown_Menu.png]]
Then select settings.

On the left side there is an option for SSH and GPG Keys:
![[SSH_Key_Page.png]]
click the bright green "New SSH key" button in the upper right hand corner.
![[Add_SSH_Key_Page.png]]
Give the ssh key a title that will remind you what it goes to paste in the public key you generated. You have now linked your local computer with your github. You will be able to push and pull repositories to github from your git repositories.