**promote**

`promote` is used to modify a member's rank. If no rank is specified, it will default to the next rank in succession. If no date is specified, it will default to the current date. 

Banned in DMs: Yes

Required rank: Officer (5)

**Usage:**

`!promote <@Member> [--force|--rank|-f|-r Rank] [--date|-d Date]`

* @Member: A mention of a member on the server. Command will fail if member is not in the database.
* Rank (optional): Value is the *name* of the rank to promote the member to. For ranks like 'Member II' where a space is present, the argument provided should be 'MemberII' with no spaces. If no rank is provided, it will default to the member's next rank.
* Date (optional): The date the promotion was performed. If left empty, the date will default to the current date. The date will be used to determine when the member is eligible for their next promotion.

**Examples:**

* `!promote @Mardan`
* `!promote @Mardan --force Recruit`
* `!promote @Mardan -f Recruit -d 11/11/2011`
* `!promote @Mardan --date 11/11/2011`