# Contributing

## Bug Reports

If you wish to report a bug, search the Issues page to check if the
bug has already been reported. If not, make a new issue using one of the
provided templates.

Keep in mind that your issue, while as thorough as possible, should only contain
information related to the bug you're reporting.

For example, below is how an issue should **NOT** look:

> i have problem. when i clicked 'ok' it closed with no error.

> i put \ and it give bug
> i dont know why

> It was about a half hour past midnight. I was downloading a torrent of
> questionable content when the app suddenly crashed without an error message.
> I was distraught, to say the least. I have tried restarting my computer many a
> time, but to no avail. This is truly a bug like no other, disobeying me. Truly
> a tricky specimen... *(pretend there's like 3 more paragraphs like this here)*

And below are examples of a **good* issue:

> I set the volume to 0% and got an Audio Error stating "Illegal state".
> I am running the app on my Windows PC running Windows 10 Pro 20H2.
> `python --version` output is `Python 3.10.6`.
> Here is the [log][not_rickroll] and [console output][also_not_rickroll].

> i tried to play a song with my speakers unplugged and it said "Segmentation
> Fault (core dumped)". i'm using ubuntu 21.04 on my custom-built gaming pc.

Basically, include any variables that could possibly affect the program's
stability, alike the above examples:

* Your OS and OS version
* Any third-party programs required to run the code (e.g. Python)
* Any log output

Keep in mind **not** to include too much. If someone needs extra information,
they'll just ask for it.

## Fixing Bugs & Adding Things

If you have fixed a bug, make a new PR and make sure to fill out the
provided template according to your exact PR.

**Always** make sure to follow the code style of the repository. Most repos
contain a `.editorconfig` defining it. Also make sure that your PR only contains
the listed changes, and does not affect any code not related to it's specific
fix or feature.

The maintainer(s) of this repository can and will choose which issues will and
will not be solved, as well as which PR will and will not be merged.

[issues]: https://github.com/qeaml/generic-template
[pr]: https://github.com/qeaml/generic-template

[not_rickroll]: https://www.youtube.com/watch?v=dQw4w9WgXcQ
[also_not_rickroll]: https://www.youtube.com/watch?v=aLMU_84BLLM
