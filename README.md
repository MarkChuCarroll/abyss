# Abyss

A different take on a text editor. 

A lot of the ideas of this came from looking at the Acme editor from Plan9. Acme is,
in a lot of ways, an ideal tool for a software developer. It's fast and simple,
and it's programmable using external tools - in a lot of ways, it feels like it's
taken some of the basic ideas of pipes in the unix shell, and adapted them to
working inside of a programming environment.

The problem is, it's just unusable. 

You can't do anything without the mouse. Even simple cursor movement, you
have to take you hand off your keyboard, and go mousing. To me, that's completely
unacceptable.

It's also written in an idiosyncratic gui toolkit. So it looks ugly, and
every control works in odd, non-standard ways. Even something as simple as
a scrollbar doesn't work the way you expect it to.

So for years, I've wanted to try to build something that has the parts
of Acme that I like, but which also fits into a modern GUI framework,
allows me to do basic editing without touching a mouse, allows me to
do things like program keybindings, etc. And I'd like to take advantage
of some modern tools that have become available - particularly things
like language servers that have become ubiquitous and standardized thanks
to vscode!

I've made a lot of false starts on this, because that's just the way I am.
But I think I've finally done enough exploration and experimentation,
and this time, I'm going to try to actually build something that works.


