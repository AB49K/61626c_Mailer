61626c mail list manager


This was built in response to being unable to find a super simple mailing list software that doesn't want aliases with postfix or any number of unessesary system integrations.

FAQ:
1. This program doesn't automatically monitor the inbox?
	
	No - It's not meant to run constantly, set it up on a 30 second cron job or loop a bash script.

2. I found a bug?
	
	You can email me at andrew@ab49k.net or join the technology@61626c.net mailing list and ask for
	help there.

3. What license? 

	Beerware. but if you do any improvements, I would appreciate a diff.

4. I how many emails can I send at once? 

	Depends on your email provider. for example gmail top out at 500 recipients per email. if you've got more than 500 people on a single list, might be time to upgrade
	to some better software.


TODO:

1. database system to keep user information. - DONE

2. confirmation of subscription. - DONE

3. email filtering to make sure only subscribed members can email the list - DONE

4. finding the most efficient way to mass mail (how many bcc address can I add to an email? - DONE

