# Marko Substitution Poltergeist

Minimal project that reproduces strange issue with subsitution of `and` words to `&&` symbols

# Play

    $ git clone git@github.com:schetnikovich/marko-substitution-poltergeist.git
    $ npm install
    $ node server.js
    
# Reasons

I don't know actual reason of this problem, but for the end user this is because of `'` symbol, that
makes all subsequent `and` words be replaced by `&&` symbol.

If you'll "close" single quotes, i.e. `We'are' young` - everything will be correct.
