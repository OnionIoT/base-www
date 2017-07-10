# base-www
Files for website hosting on the Omega to ensure compatibility between Onion utilities

## Operation

Displays either the Setup Wizard or the Onion Console in an iFrame. Defaults to showing the Console if both are present.

Operations:

1. Check if Onion Console html files are present
1. If so, set the iFrame `src` address to the Console
1. If not, set the iFrame `src` address to the Setup Wizard


