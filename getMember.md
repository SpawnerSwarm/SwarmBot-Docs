**getMember**

`getMember` produces the names, rank, and last rankup history for a given member. It also displays whether they are banned and if they are eligible for a rankup.

Banned in DMs: Yes

Required rank: none

**Usage:**

`!getMember <@Member> [--verbose|-v]`

* @Member: A mention of a member on the server. Command will fail if member is not in the database.
* verbose: No value. The presence of this argument will produce additional information, such as the aliases of a member.

**Examples:**

* `!getMember @Mardan`
* `!getMember @Mardan --verbose`