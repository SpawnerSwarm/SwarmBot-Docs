**kick**

`kick` removes a member from the Discord server in which the command is invoked. It will also add a flag to a member's database entry indicating that they are barred from invoking further commands. 

If a banned member tries to invoke a command, the message `You are currently banned from using commands. Please contact Mardan to rectify this.` will be sent in response.

Banned members are excluded from the !memberlist count as well.

A message containing the details of the kick: the member kicked, the moderator who initiated the kick, and the reason provided for the kick will be posted to the #recruit_log channel.

Members cannot kick other members of higher or equal rank.

Upon being kicked, a member will receive the message `Hello ${Member.Name}, this is an automated message from the Spawner Swarm to inform you that you have been kicked for '${reason}'.  If you want to re-enter the Swarm, please contact an Officer for a re-invite. You will still be subject to the same rules, however.`

Banned in DMs: Yes

Required rank: General

**Usage:**

`!kick <@Member> [Reason]`

* @Member: A mention of a member on the server. Command will fail if member is not in the database.
* Reason (optional): The reason the kick was initiated. The reason will be included in the post to #recruit_log channel. If left blank, the reason will default to 'None'.

**Examples:**

* `!kick @Mardan`
* `!kick @Mardan Idle`