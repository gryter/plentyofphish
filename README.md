@Plentyofphish is the Hive account that holds the list of hacked (phished) accounts or accounts spawned by hackers.

It operates in conjunction with @hivewatchers, @spaminator, @guard and @theycallmedan accounts. 

This repository is maintained by @guiltyparties from the @hivewatchers team. 

# Procedures for Addition/Removal

1. Steem accounts deemed as being under hacker control are added to the Phishing.txt list.
2. Steem accounts confirmed as recovered by their legitimate owners are removed from the Phishing.txt list.
3. The Phishing.txt list is automatically synced with the "Mute" function of the @plentyofphish account on a regular basis.
4. The @plentyofphish "Mute" list is regularly synced with the Phishing Masterlist managed by the @steemcleaners team.
5. Suggested additions/removals from Phishing.txt will be reviewed on a regular basis. 

# Policy

The Steemcleaners team will manually downvote ("Flag") Steem accounts to zero reputation, with @hivewatchers and/or @spaminator, under the following circumstances:
1. The account is actively posting phishing messages; 
2. The account will likely be used to post phishing messages in the near future; and
3. The account was created solely for the purposes of phishing.

The Steemcleaners team will automatically downvote ("Flag") Steem posts and/or comments with @guard, irrespective of which account posts them, under the following circumstances: 
1. The post/comment contains a short-link that, once unfurled, directs users to a phishing website;
2. The post/comment contains a direct clickable URL to a phishing website; or
3. The post/comment contains a masked, non-clickable URL to a phishing website.

The Steemcleaners team will automatically downvote ("Flag") Steem posts and/or comments with @mack-bot where accounts are deemed under hacker control.

The Steemcleaners team will remove downvotes made by the @steemcleaners and/or @spaminator, where possible, under the following circumstances:
1. The account owner has restored full control of the account and has removed the malicious URLs; or
2. The account owner has restored full control of the account and the existing instances of malicious links are either defunct or individually flagged.

The Steemcleaners team will not remove downvotes made by @hivewatchers and/or @spaminator under the following circumstances:
1. The downvoted post/comment is <12 hours to payout (6+ days old), making removal impossible;
2. The downvoted post/comment has been deleted, making removal impossible;
3. We have reason to suspect the account is still compromised; or
4. The account was created solely for the purposes of phishing.

The Steemcleaners team will not remove downvotes made by @guard or @mack-bot by default unless: 
1. Downvote removal is necessary to reverse severe* reputational damage to the account; and
2. The account owner has restored full control of the account and has removed the malicious URLs. 
*Reputation lowered to zero or thereabouts. 

The Steemcleaners team and designated community members will review all reports of compromised and restored accounts on an individual and objective basis. 

The nature of the account or it's prior contact history with Cheetah or Hivewatchers will not bear any effect on its treatment by the Team under the anti-phishing initiative. 

# @Plentyofphish (Steem) Keyholder List
The following account holders may use the "Mute" and "Unmute" feature of the @plentyofphish account, which allows for syncing with the phishing.txt list: 
@guiltyparties


# FAQ
**Q:** My account was recovered but it is still on the list. How do I get it removed?

**A:** Open an Issue here or let us know on the Hivewatchers Discord https://discord.gg/W2ykxCY 

**Q:** My reputation is zero because I was flagged by @hivewatchers or @spaminator. What can I do?

**A:** Please make sure you edited out malicious links that hackers posted in the posts/comments they made using your account.

**Q:** Can you take @guard or @mack-bot flags off my comments?

**A:** No. @guard or @spaminator flags are small enough to not cause undue reputational damage to an account. They are not removed unless severe reputational damage has occurred regardless.

**Q:** How do I remove posting authority from a 3rd party Steem service or app?

**A:** https://v2.steemconnect.com/apps/authorized

**Q:** How do I check if I'm delegating my SP to a hacker?

**A:** http://www.steemreports.com/delegation-info/

**Q:** How do I undelegate the SP?

**A:** Undelegating is just re-delegating but with zero 'vests' (SP). You can undelegate with Steem Connect by changing parts of this URL: https://v2.steemconnect.com/sign/delegateVestingShares?delegator=youraccountnamehere&delegatee=thehackeraccountnamehere&vesting_shares=000000.000000%20VESTS

**Q:** How do I avoid becoming a victim to phishing?

**A:** Do not click on random links or trust websites that ask you for your keys/password unless you're 100% they're legitimate.

**Q:** Can my account become compromised from Steem-related mobile apps?

**A:** There are many phishing mobile apps out there. Do not install them unless you verified them. Never log in with your password.

**Q:** How do I keep my money safe?

**A:** Use your private posting key and do not trust any website or app that asks for your password.

**Q:** What do I do if hackers use my account to spam but I can still log in?

**A:** Change your password and revoke all app permissions using https://v2.steemconnect.com/apps/authorized if you start seeing strange comments.

**Q:** What do I do if my money was moved to someone but I did not move it myself?

**A:** Change your password immediately.

**Q:** How do I speed up my account restoration?

**A:** Use the email address you signed up with when you do the account restoration.

**Q:** Should I wait to fill out the Stolen Account Recovery form on Steemit?

**A:** No. Restore your account immediately after being locked out -- it can take well over 24 hours.

**Q:** Should I delete all the comments the hackers posted?

**A:** Do not delete flagged comments -- just edit them to change the text.

**Q:** I deleted the comments, can you take the flags off?

**A:** Deleted comments cannot be unflagged.

**Q:** How do I get back the SBD/STEEM the hackers stole?

**A:** Stolen money can't be returned.
