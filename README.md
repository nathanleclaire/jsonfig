jsonfig
=======

Look ma, no YAML!

Just `fig up` in the project root.  It works!  But wait, that looks like JSON!?  Turns out that JSON, except for some edge cases, is actually a subset of YAML.  So a lot of valid JSON is also valid YAML.

If you are implementing something like this on your own, know that you could use something like `fig up -f fig.json` to actually name the file with the correct extension.
