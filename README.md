# PokemonGoDecoderForBurp
A simpe decoder to decode requests/responses made by PokemonGo in burp


To Install:
check out this repo and init the submodule. Then compile the .proto files (compile.py -l java) and finaly compile everything using maven.
Then add the generated jar-with-dependencies to burp (via the Extender tab).

Now you can decode some parts of the intercepted Pokemon Go traffic.
Some parts are not jet reverse engenered thus we dont know what those bytes mean :(
