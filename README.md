How to set up 2 or more GitHub accounts

<!-- 1 Free Code Camp - mar2018 -->
https://www.freecodecamp.org/news/manage-multiple-github-accounts-the-ssh-way-2dadc30ccaca/

<!-- 2 Medium - jan2018 -->
https://medium.com/@pinglinh/how-to-have-2-github-accounts-on-one-machine-windows-69b5b4c5b14e 

<!-- 3 Medium - jun2020 -->
https://betterprogramming.pub/how-to-use-multiple-github-accounts-with-one-computer-c9ba3f851b75

<!-- 4 dev.to - jul2020 -->
https://jogendra.dev/how-to-use-multiple-github-accounts-on-single-machine

<!-- 5 BEST: dev.to - sep2020 -->
https://dev.to/sammm/setting-up-multiple-github-accounts-on-the-same-computer-without-having-to-change-the-repo-url-1007


<!-- Setting up SSH config -->
From terminal, run cd ~/.ssh .
Check if a config file exists by running - ls config . If you see ls: config: No such file or directory , create a new config file by running touch config .

<!-- Setting your user.name and user.email -->
#Check if you have an existing .gitconfig in your root by running ls ~/.gitconfig . 
#If you don't have one, create one by running touch ~/.gitconfig 
