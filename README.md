# CSS-Inliner-workflow

Inline all CSS in order to use in email.

Writing HTML page for email is really hard, you have to inline all your CSS. However, doing this when developing will mess up your code and allow bugs to appear.

After searching, I found [Zurb Inliner](http://foundation.zurb.com/emails/inliner.html) which can finish this task. I extract the url and param format, then write a workflow to call it automatically.

So, now you can write your CSS in a `<style></style>` tag, and then trigger hotkey to inline it.

Usage:

1. write all your CSS in a `<style></style>` tag,
2. select all HTML text,
3. press `Ctrl + Shift + 0`,
4. wait for a short time(if your internet is slow),
5. press `⌘ + V`,
6. BOOM! You get the final inlined HTML.

Hopes this can make email writing easier.

# License

[WTFPL](https://en.wikipedia.org/wiki/WTFPL).