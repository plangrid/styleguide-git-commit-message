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
| :cloud: | `:cloud:` | when making chnages involving synchronization logic with the backend API |
| :bank: | `:bank:` | **Generic Database** specific (Migrations, Scripts, Extensions, ...) |
| :pencil: | `:pencil:` | when **performing minor changes/fixing** the code or language |
| :racehorse: | `:racehorse:` | when improving **performance** |
| :books: | `:books:` | when writing **docs** |
| :ambulance: | `:ambulance:` | when fixing a **bug** |
| :umbrella: | `:umbrella:` | when adding **tests** |
| :microscope: | `:microscope:` | when adding **code coverage** |
| :green_heart: | `:green_heart:` | when fixing the **CI** build |
| :lock: | `:lock:` | when dealing with **security** |
| :arrow_up: | `:arrow_up:` | when upgrading **dependencies** |
| :arrow_down: | `:arrow_down:` | when downgrading **dependencies** |
| :fast_forward: | `:fast_forward:` | when **forward-porting features** from an older version/branch |
| :rewind: | `:rewind:` | when **backporting features** from a newer version/branch |
| :shirt: | `:shirt:` | when removing **linter**/strict/deprecation warnings |
| :lipstick: | `:lipstick:` | when improving **UI**/Cosmetic |
| :wheelchair: | `:wheelchair:` | when improving **accessibility** |
| :globe_with_meridians: | `:globe_with_meridians:` | when dealing with **globalization**/internationalization/i18n/g11n |
| :speaker: | `:speaker:` | when Adding **Logging** |
| :mute: | `:mute:` | when Reducing **Logging** |
| :sparkles: | `:sparkles:` | when introducing **New** Features |
| :zap: | `:zap:` | when introducing **Backward-InCompatible** Features, _maybe_ with `@CHANGED` Comment Tag |
| :snowflake: | `:snowflake:` | changing **Configuration**, Usually together with :penguin: or :ribbon: or :rocket: |
| :ribbon: | `:ribbon:` | Customer requested application **Customization**, with `@HACK` Comment Tag |
| :rocket: | `:rocket:` | Anything related to Deployments/**DevOps** |
| :handshake: | `:handshake:` | when **Merge files** |

Ask to Be [Creative](https://emoji.codes/)!

Tools
-----
There is Also a [nifty CLI tool](https://github.com/jakeasmith/commit) to aid in standardizing commit messages based on this document, thanks to [@jakeasmith](https://github.com/jakeasmith).
