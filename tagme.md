**tagme**

`tagme` adds a specified Discord tag, or role, to the sender of the message. `untagme` removes a specified tag from the sender.

Valid tags will not be listed in this document, to prevent inconsistencies, but they can be found by performing the `!tagme` or `!untagme` commands with no arguments.

Banned in DMs: Yes

Required rank: none

**Usage:**

`!(un)tagme <Tag>`

* Tag: A tag to apply to the sender of the message. The only especially notable tag is the `rank` tag. If the Tag `rank` is provided, the member will be given the tag corresponding to their current rank and all preceding ranks as well as removing any tags they should not have. The `rank` argument will not be valid for `untagme`.

**Examples:**

* `!tagme rank`
* `!untagme bot`