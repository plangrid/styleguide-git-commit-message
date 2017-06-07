PlanGrid for Windows Git Commit Message
==================

All Git Commit Messages **MUST** meet with this Text Format:

```
[Jira Ticket ]:emoji1: [:emoji2: :emoji3: ...] Subject
(Only One NewLine)
Message Body
```

Rules
-----
1. Capitalize the _Subject_.
2. Do not end the _Subject_ line with a period.
3. Message _Subject_ **SHOULD** Begin with _at-least_ One Emoji(see below for [list of Suggested Emojis](#suggested-emojis)).
4. If applicable, subject line **SHOULD** begin with the Jira Ticket.  (i.e. WIN-1234)
5. Total Characters of the _Subject Line_ **MUST** be _Less_ than or _Equal_ to **72** Chars Long.
7. Use Valid [MarkDown](https://daringfireball.net/projects/markdown/basics) format in _Message Body_.
8. Use the **Present Tense** ("Add feature" not "Added feature").
9. Use the **Imperative Mood** ("Move cursor to..." not "Moves cursor to...").
10. Use the _Message body_ to explain **what** and **why** vs. how.

Notes
-----
+ There is a **Space** Character between Multiple Emojis!.
+ There is a **Space** Character between the Jira ticket and the first emoji.
+ Every Raw Emoji Text(`:emoji:`) is Counted as One Char!.
+ See [ToDo Grammar StyleGuide](https://github.com/slashsBin/styleguide-todo-grammar) for more Information on `@XXX` Comment Tags.

---

Suggested Emojis
----------------

| Emoji | Raw Emoji Code | Description |
|:---:|:---:|---|
| :art: | `:art:` | when improving the **format**/structure of the code |
| :cloud: | `:cloud:` | when making changes involving synchronization logic with the backend API |
| :bank: | `:bank:` | when making changes to the sqlite database (Migrations, Scripts, Extensions, ...) |
| :printer: | `:printer:` | when making changes that involve the printer |
| :mag_right: | `:mag_right:` | when making changes to analytics |
| :card_index: | `:card_index:` | changes involving the data model layer |
| :eyes: | `:eyes:` | changes involving searching or filtering |
| 🗞 | 🗞 | when changing how sheets are visualized |
| :pencil: | `:pencil:` | when **performing minor changes/fixing** the code or language |
| :racehorse: | `:racehorse:` | when improving **performance** |
| :books: | `:books:` | when writing **docs** |
| :ambulance: | `:ambulance:` | when fixing a **bug** |
| :white_check_mark: | `:white_check_mark:` | when adding **tests** |
| :octopus: | `:octopus:` | when adding **code coverage** |
| :green_heart: | `:green_heart:` | when fixing the **CI** build |
| :lock: | `:lock:` | when dealing with **security** |
| :shirt: | `:shirt:` | when removing **linter**/strict/deprecation warnings |
| :lipstick: | `:lipstick:` | when improving **UI**/Cosmetic |
| :wheelchair: | `:wheelchair:` | when improving **accessibility** |
| :globe_with_meridians: | `:globe_with_meridians:` | when dealing with **globalization**/internationalization/i18n/g11n |
| :speaker: | `:speaker:` | when Adding **Logging** |
| :mute: | `:mute:` | when Reducing **Logging** |
| :sparkles: | `:sparkles:` | when introducing **New** Features |
| :gear: | `:gear:` | changing **Configuration** |
| :rocket: | `:rocket:` | Anything related to Deployments/**DevOps** |
| :arrow_up: | `:arrow_up:` | when upgrading **dependencies** |
| :arrow_down: | `:arrow_down:` | when downgrading **dependencies** |
| :fast_forward: | `:fast_forward:` | when **forward-porting features** from an older version/branch |
| :rewind: | `:rewind:` | when **backporting features** from a newer version/branch |

Ask to Be [Creative](https://emoji.codes/)!

Tools
-----
There is Also a [nifty CLI tool](https://github.com/jakeasmith/commit) to aid in standardizing commit messages based on this document, thanks to [@jakeasmith](https://github.com/jakeasmith).
