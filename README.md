# scripts
TONS of utility scripts I've written over the years.

### Notable scripts I use all the time:

#### Git Related
- [b](https://github.com/ZackMFleischman/scripts/blob/master/git/b): Short for "branches". Dump the last 10 git branches I used with a number next to it. Run it again with that number to switch to that branch.
- [cr](https://github.com/ZackMFleischman/scripts/blob/master/git/cr): Short "Checkout Remote". This will fetch all remote branches, then checkout a new branch against the remote branch that already exists.

#### Utility Scripts
- [ff](https://github.com/ZackMFleischman/scripts/blob/master/util/ff): Short for "Find File". This will take a search term and recursively search from the current directory for any files containing the search term in the name. It will list them with a number next to it. Running the script again with that number will open that file in vim.
- [internet](https://github.com/ZackMFleischman/scripts/blob/master/util/internet): I run this when the internet is down. It will wait until the internet is back up, then send me an email, a text, and pop a notification on my desktop that the internet is back up. (See also [pingup](https://github.com/ZackMFleischman/scripts/blob/master/util/pingup), which does the same thing for an arbitrary website or server.)
- [email](https://github.com/ZackMFleischman/scripts/blob/master/util/email): This will send an email through my gmail account. It takes CLI args for to, cc, bcc, subject, and body. It will also read the body in from standard in so you can pipe program output into an email.
- [text](https://github.com/ZackMFleischman/scripts/blob/master/util/text): Sends me a text message with whatever string is passed.
- [dump](https://github.com/ZackMFleischman/scripts/blob/master/util/dump): Dumps the content of the script passed as a parameter. This will work anywhere for any script as long as the script is on the PATH.
- [change](https://github.com/ZackMFleischman/scripts/blob/master/util/change): Opens a script up in vim regardless of where your current working directory is as long as the script is on the PATH.
- [ip](https://github.com/ZackMFleischman/scripts/blob/master/util/ip): Dumps your public facing IP address to the console.
