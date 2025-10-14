# ansible-practice 

- Logon to GitHub
- Make a new Repository
- Go to:
	Profile
	Settings
	SSH and GPG Keys
	New SSH Key
- Copy the first SSH key I used on Ubuntu Workstation
	SSH into server
	Copy the key from Authorized_Keys
- Past that key into GitHub and Add new Key
- Go back to repository 
	Code
	Clone with SSH and Copy
- Now I have access to that folder on the workstation

#Tell GitHub who I am on terminal

- git config --global user.name "Klark Knight"
- git config --global user-mail "klarkus@hotmail.com"
- cat ~/.gitconfig (shows whats been added)
- Edit README

#Update on website

- git status (shows in red what has been changed
- git diff (shows the difference)
- git add README.md (updates it)
- git commit -m "Updated readme file, initial commit"
- git push origin master
