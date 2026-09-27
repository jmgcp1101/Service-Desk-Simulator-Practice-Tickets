Ticket Summary

The user was unable to print to the department's network printer. The printer was powered on and had paper, but print jobs were not going through. The issue was traced to an incorrect printer IP address configured on the user's PC.

What I Did

I first checked the print server through the server room panel to make sure it was online and not reporting any errors. After confirming that the server appeared to be functioning normally, I remotely connected to the user's PC and checked its network connection to the printer. I found that the printer was configured with the wrong IP address, so I removed the existing printer connection and added it again using the correct IP. Printing then worked normally.

What I Got Stuck On / What I Learned

I spent some time checking the print server first, even though the symptoms pointed more directly toward the user's connection to the printer. This helped me realize that I should start troubleshooting from the affected endpoint and work my way through the connection path before checking broader infrastructure. It was a good reminder to follow the simplest and most relevant troubleshooting path first.