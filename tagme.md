**tagme**

`tagme` adds a specified Discord tag, or role, to a user. `untagme` removes a specified tag from a user.

Valid tags will not be listed in this document, to prevent inconsistencies, but they can be found by performing the `!tagme` or `!untagme` commands with no arguments.

Banned in DMs: Yes

Required rank: none

**Usage:**

`!(un)tag(me) <Tag> [@Member]`

* Tag: A tag to apply to the user of the message. The only especially notable tag is the `rank` tag. If the Tag `rank` is provided, the member will be given the tag corresponding to their current rank and all preceding ranks as well as removing any tags they should not have. The `rank` argument will not be valid for `untagme`.

* Member: The member to whom to apply the tag. If left blank, for instance in `!tagme warframe`, the sender will be the assumed target. The behavior is exactly the same regardless of whether the argument is specified or not, with one notable exception. The `!tagme rank` command will assign the *target user's own ranks*; in other words, you can't tag someone else with your ranks.

**Examples:**

* `!tagme rank`
* `!tag warframe`
* `!tag leave @Mardan`
* `!untagme bot`