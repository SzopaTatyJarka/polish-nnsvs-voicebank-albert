- - - USAGE - - -

(To clarify, a "[ ]" is representing note in UTAU.)

1. Make sure the UST is in phoneme input format: 
O --> [o]
Nic --> [N i c]
Wczas --> [f cz a s]
Kleszcz --> [k l e sz cz]
Na wczasy --> [n a f] [cz a] [s y]*

2a. UTAU: use the ENUNU plugin to render the singing voice, wait until the rendering is finished, it should start playing back. (The rendered files can be found in the same folder the UST is)
2b. OpenUTAU: wait for the singing voice to render

* When dividing words into syllables, there's a specific way to divide consonant clusters:

CC	[C] [C]
ciebie	[C e b] [j e]

CCC	[C] [C C]
akcja	[a k] [c j a]

CCCC	[C C] [C C]
jest kto	[j e s t] [k t o]

CCCCC	[C C] [C C C]
akt z wczoraj [a k t] [s f cz o] [r a j]

CCCCCC	[C C C] [C C C]
park w trzcinach	[p a r k f] [t sz C i] [n a h]

* Notice that this library can pronounce glottal stops, to enable them, place a [cl] symbol in a short following note. [t E] [cl] [i]

* Notice that this library is also able to pronounce rolled r's, to enable them, place several [r] phonemes in surrounding notes. [b a r r] [r dz o]

* This library contains a Japanese hiragana configuration and can sing in Japanese, but with a hard accent.

* This library misses "H" and "J" labels. Those cases are handled contextually until the next model update.

* For various information regarding the singing voice, look into the "STATISTICS.ods"

** UTAU Specific:

* This library does not work with canon's timing plugin.

* If the UST has multiple rest [R] symbols after each other, please merge them using a dedicated plugin. This will prevent generating too many breath sounds.

- - - RESOURCES - - -

ENUNU usage tutorial (Japanese): https://youtu.be/IkWvu0H1aIk

PL NNSVS repo: https://github.com/SzopaTatyJarka/nnsvs-polish-support

Albert's GitHub page: https://github.com/SzopaTatyJarka/polish-nnsvs-voicebank-albert

- - - NOTES - - -

Special thanks to Casuticism and Haru0l for countless test training, troubleshooting and the whole NNSVS community for the generous support over the whole development process. Thank you guys so much!

Icon design artwork created by @wik_wav on Twitter