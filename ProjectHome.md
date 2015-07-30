# Context #
This project aims at studying the context of two words in French : "Ton" and "Voix" ("voice" and "tone/pitch"). The question is : what are the most plausible adjectives with those names ? To answer this question I made statistics evaluating which kind of adjectives were associated to those words. I had 100Mo of novels extracted from gutenberg project.

# How #

For extracting the adjectives associated to "voix" and "ton" I used a parser : the xerox parser online :

http://open.xerox.com/Services/XIPParser/Pages/Using%20XIP.

I made a script that send the corpora and collect the information needed :


_Name Adjective1 Occurences Adjective2 Occurences_

**Example :**

_Voix : aigüe 33 grave 42 ..._

# Why did-I use Xerox parser ? #

For knowing which adjective is associated to a name, we need a deep parsing. Xerox is able to do that, I tried some sentences and noticed that most of the mistakes were mistakes of recall, not of precision which is tolerable for the research made. This online parser is quite quick and above all doesn't limit the volume of text analyzed.

# The result #

On the downloads page you can find "analyseVoixTon.pdf". This file is in  French. It explains my results how I processed and why this research is relevant.