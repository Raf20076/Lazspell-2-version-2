# Lazspell-2

Lazspell-2 version 2 by Raf20076, Poland, 2021

Lazspell-2 version 2 is an example of a speller which checks spelling in German, English, Spanish,
French, Italian, Portugues, Polish and Russian and underline in red colour errors.

In this example <b>TRichMemo </b> component was used.

Install TRichMemo in Lazarus IDE.
Download TRichMemo from https://sourceforge.net/p/lazarus-ccr/svn/HEAD/tree/
Click Download Snapshot and uncompress lazarus-ccr-svn-r....zip
Go to folder lazarus-ccr-svn-r... -> components -> richmemo 

All dictionaries are coded in UTF-8 in dict folder from https://github.com/wooorm/dictionaries
You must distribute dict folder with your program.

Lazspell uses hunspell.pas and hunspell.inc from https://github.com/davidbannon/hunspell4pas

Lazspell is under license: 

Unit Main License is https://creativecommons.org/publicdomain/zero/1.0/deed.en 

Unit Functions License is https://creativecommons.org/publicdomain/zero/1.0/deed.en

libhunspell.dll was compiled with Microsoft Visual C++ 2010. from the original source from 
http://sourceforge.net/projects/hunspell/files/Hunspell/1.3.2/hunspell-1.3.2.tar.gz/download

You must distribute this file with your program. 

Lazspell

1. Choose dictionary (Check button will be enabled)
2. Type text in memo box
3. Click Check button
4. If errors found, click an error in Errors box, the error will be highlighted in memo box
5. Click a word in Suggestions box to change highlighted error for suggested word
