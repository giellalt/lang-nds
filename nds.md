Nouns
No nouns so far


Numerals
No numerals so far


Verbs
So far only a couple of verbs








Strong verbs 

Class I


Class II 



Class III







Class IV



Class V




Prefixes
No prefixes so far



Adjectives
No adjectives so far




Pronouns
No pronouns so far.


================================================== !
The Low German morphophonological/twolc rules file !
================================================== !




strong verb class 1 1st part
strong verb class 1 2nd part
strong verb class 2a 1st part
strong verb class 2a 2nd part
strong verb class 2b 1st part
strong verb class 2b 2nd part
strong verb class 3a 
strong verb class 3bc
strong verb class 4a 1st part
strong verb class 4ab 2nd part
strong verb class 4b 1st part
strong verb class 4c 1st part
strong verb class 4c 2nd part 
strong verb class 5a 1st part 
strong verb class 5ab 2nd part
strong verb class 5b 1st part


TRIGGERS
 * %^CC2C:0  for Deleting second consonant in orthographic geminate
 * %^VV2V:0  for Orthographic vowel deletion in open syllable
 * %^IUML:0  for i-umlaut
 * %^UUML:0  for u-umlaut
 * %^ABL1NL:0  for non-lengthened ablaut grade 1 in class 4 and 5 in some southern dialects, ABL1 = ablaut grade 1, NL = non-lengthened
 * %^ABL1S:0  for shortened ablaut grade 1 in 2nd and 3rd sg. of present tense, S = shortened
 * %^ABL2:0  for ablaut grade 2 in preterite, ABL2 = ablaut grade 2
 * %^ABL2W:0  for specific preterite forms in Westphalian dialects, W = Westphalian
 * %^ABL2U:0  for irregular umlaut of ablaut grade 2 in class 4a,b and 5, U = (irregular) umlaut
 * %^ABL3:0  for long ablaut grade 3 in perfect participle
 * %^ABL3NL:0  for short ablaut grade 3 in some southern dialects, NL = non-lengthened 






**Deleting s before suffix -st**

* *leas%>st*
* *lea0%>st*

* ★*leas%>st* (is not standard language)
* ★*leas%>st* (is not standard language)



**Deleting t before suffix -t**

* *acht%>t*
* *ach0%>t*

* ★*acht%>t* (is not standard language)
* ★*acht%>t* (is not standard language)


**Orthographic vowel deletion in open syllable**

maken+V+Ind+Prs+Sg1
* *maak%^VV2V%>e*
* *ma0k0%>e*

* ★*maak%^VV2V%>e* (is not standard language)
* ★*maak0%>e* (is not standard language)

**Orthographic consonant deletion in closed syllable**

tellen+V+PrfPrc 
* *tell%^CC2C>d*
* *tel00%>d*

* ★*tell%^CC2C>d* (is not standard language)
* ★*tell0%>d* (is not standard language)


**I-umlaut for short vowels in closed syllable or long vowels in open syllable** 

holt+N+Pl+Nom: **muorra/puu/wood**
* *holt%^IUML%>er*
* *hölt0%>er*

* ★*holt%^IUML%>er* (is not standard language)
* ★*holt0%>er* (is not standard language)

broder+N+Pl+Nom: **viellja/veli/brother**
* *broder%^IUML%>s*
* *bröder0%>s*

* ★*broder%^IUML%>s* (is not standard language)
* ★*broder0%>s* (is not standard language)

woord+N+Pl+Nom: **sátni/sana/word**
* *woord%^IUML%>e*
* *wöörd0%>e*

* ★*woord%^IUML%>e* (is not standard language)
* ★*woord0%>e* (is not standard language)

vuust+N+Pl+Nom: **čorbma/nyrkki/fist**
* *vuust%^IUML%>e*
* *vüüst0%>e*

* ★*vuust%^IUML%>e* (is not standard language)
* ★*vuust0%>e* (is not standard language)


**I-umlaut for å ** 


**Double marking of i-umlaut for å** 

råd+N+Pl+Nom: **ráđđi/neuvo/council**
* *r%{åöä%}%{0äö%}d%^IUML%>e*
* *röäd0%>e*

* ★*r%{åöä%}%{0äö%}d%^IUML%>e* (is not standard language)
* ★*rö%{0äö%}d0%>e* (is not standard language)

* ★*r%{åöä%}%{0äö%}d%^IUML%>e* (is not standard language)
* ★*r%{åöä%}%{0äö%}d0%>e* (is not standard language)


daal+N+Pl+Nom: **leahki/laakso/valley**
* *daal%^VV2V%^IUML%>er*
* *dä0l00%>er*

* ★*daal%^VV2V%^IUML%>er* (is not standard language)
* ★*da0l00%>er* (is not standard language)

book+N+Pl+Nom: **girji/kirja/book**
* *book%^VV2V%^IUML%>er*
* *bö0k00%>er*

* ★*book%^VV2V%^IUML%>er* (is not standard language)
* ★*bo0k00%>er* (is not standard language)

huus+N+Pl+Nom: **viessu/talo/house**
* *huus%^VV2V%^IUML%>e*
* *hü0s00%>e*

* ★*huus%^VV2V%^IUML%>e* (is not standard language)
* ★*hu0s00%>e* (is not standard language)

**Double marking of umlaut for graphemes consisting of two different letters, ending in a:ä**

sak+N+Pl+Nom: **seahkka/pussi/bag**
* *sakk%^IUML%>e*
* *säkk0%>e*

* ★*sakk%^IUML%>e* (is not standard language)
* ★*sakk0%>e* (is not standard language)

slag+N+Pl+NOM: **časkin/lyönti/hit**
* *slag%^IUML%>e*
* *släg0%>e*

* ★*slag%^IUML%>e* (is not standard language)
* ★*slag0%>e* (is not standard language)

maagd+N+Pl+Nom: **biigá/piika/maid**
* *maagd%^IUML%>e*
* *määgd0%>e*

* ★*maagd%^IUML%>e* (is not standard language)
* ★*maagd0%>e* (is not standard language)

* ★*maagd%^IUML%>e* (is not standard language)
* ★*mäagd0%>e* (is not standard language)

broak+N+Pl+Nom: **doadjin/katkaisu/break**
* *broak%^IUML%>e*
* *bröäk0%>e*

* ★*broak%^IUML%>e* (is not standard language)
* ★*broak0%>e* (is not standard language)

* ★*broak%^IUML%>e* (is not standard language)
* ★*bröak0%>e* (is not standard language)



**Double marking of umlaut for graphemes consisting of two different letters, ending in u:y**

**Double marking of umlaut for graphemes consisting of two different letters, ending in u:ü**
busk+N+Pl+Nom: **miestta/pensas/bush**
* *busk%^IUML%>e*
* *büsk0%>e*

* ★*busk%^IUML%>e* (is not standard language)
* ★*busk0%>e* (is not standard language)



**Short ablaut grade 1 in class 1  %{eiØ%}:i**

**Second part of short ablaut grade 1 in class 1** 

ryden+V+Ind+Prs+Sg3: **riidet/ratsastaa/ride**
* *r%{eiØ%}%{yaØ%}d%^ABL1S%>t*
* *r0id0%>t*

* ★*r%{eiØ%}%{yaØ%}d%^ABL1S%>t* (is not standard language)
* ★*ri{yaØ%}d0%>t* (is not standard language)

* ★*r%{eiØ%}%{yaØ%}d%^ABL1S%>t* (is not standard language)
* ★*r%{eiØ%}%{yaØ%}d0%>t* (is not standard language)

**Short ablaut grade 1 in class 2a %{eouü%}:ü**

**Second part of short ablaut grade 1 in class 2a** 

beden+V+Ind+Prs+Sg3: **bivdit/pyytää/ask**
* *b%{eouü%}%{Øeua%}d%^ABL1S%>t*
* *bü0d0%>t*

**Short ablaut grade 1 in class 2b  %{uüo%}:ü**

**Second part of short ablaut grade 1 in class 2b**

krupen+V+Ind+Prs+Sg3: **čákŋat/ryömiä/creep**
* *kr%{uüo%}%{uaØ%}p%^ABL1S%>t*
* *krü0p0%>t*

**Short ablaut grade 1 in class 4a %{iaeo%}:i**

**Second part of short ablaut grade 1 in class 4a+b and 5a+b**

niamen+V+Ind+Prs+Sg3: **váldit/ottaa/take**
* *n%{iaeo%}%{aeØ%}m%^ABL1S%>t*
* *ni0mØ%>t*

**Short ablaut grade 1 in class 4b %{eiao%}:i **

dreapen+V+Ind+Prs+Sg3: **deaivvadit/tavata/meet**
* *dr%{eiao%}%{aeØ%}p%^ABL1S%>t*
* *dri0pØ%>t*

**Short ablaut grade 1 in class 4c %{eio%}:i**

**Second part of short ablaut grade 1 in class 4c**

spreaken+V+Ind+Prs+Sg3: **hupmat/puhua/speak**
* *spr%{eio%}%{aØo%}k%^ABL1S%>t*
* *spri0k0%>t*

**Short ablaut grade 1 in class 5a %{iae%}:i**


giaven+V+Ind+Prs+Sg3: **addit/antaa/give**
* *g%{iae%}%{aeØ%}v%^ABL1S%>t*
* *gi0v0%>t*

**Short ablaut grade 1 in class 5b**

steaken+V+Ind+Prs+Sg3: **čugget/pistää/stab**
* *st%{eia%}%{aeØ%}k%^ABL1S%>t*
* *sti0k0%>t*

**Ablaut grade 2 and 3 in class 1 %{eiØ%}:e**

**Second part of ablaut grade 2 in class 1**

ryden+V+Ind+Prt+Sg3: **riidet/ratsastaa/ride**
* *r%{eiØ%}%{yaØ%}d%^ABL2*
* *reyd0*

* ★*r%{eiØ%}%{yaØ%}d%^ABL2* (is not standard language)
* ★*r%{eiØ%}%{yaØ%}d0* (is not standard language)

* ★*r%{eiØ%}%{yaØ%}d%^ABL2* (is not standard language)
* ★*re%{yaØ%}d0* (is not standard language)

**Ablaut grade 2 and 3 in class 2a **

**Second part of ablaut grade 2 in class 2a **

beden+V+Ind+Prt+Sg3: **bivdit/pyytää/ask**
* *b%{eouü%}%{Øeua%}d%^ABL2*
* *boud0*

* ★*b%{eouü%}%{Øeua%}d%^ABL2* (is not standard language)
* ★*b%{eouü%}%{Øeua%}d0* (is not standard language)

* ★*b%{eouü%}%{Øeua%}d%^ABL2* (is not standard language)
* ★*bo%{Øeua%}d0* (is not standard language)

**Ablaut grade 2 and 3 in class 2b**

**Second part of ablaut grade 2 in class 2b**

krupen+V+Ind+Prt+Sg3: **čákŋat/ryömiä/creep**
* *kr%{uüo%}%{uaØ%}p%^ABL2*
* *kroup0*

* ★*kr%{uüo%}%{uaØ%}p%^ABL2* (is not standard language)
* ★*kr%{uüo%}%{uaØ%}p0* (is not standard language)

* ★*kr%{uüo%}%{uaØ%}p%^ABL2* (is not standard language)
* ★*kro%{uaØ%}p0* (is not standard language)

**Ablaut grade 2 and 3 in class 3a**

drinken+V+Ind+Prt+Sg3: **juhkat/juoda/drink**
* *dr%{iua%}nk%^ABL2*
* *drunk0*

* ★*dr%{iua%}nk%^ABL2* (is not standard language)
* ★*dr%{iua%}nk0* (is not standard language)

drinken+V+PrfPrt: **juhkat/juoda/drink**
* *dr%{iua%}nk%^ABL3%>en*
* *drunk0%>en*

* ★*dr%{iua%}nk%^ABL3%>en* (is not standard language)
* ★*dr%{iua%}nk0%>en* (is not standard language)

**Ablaut grade 2 and 3 in class 3b and 3c**

helpen+V+Ind+Prt+Sg3: **veahkehit/auttaa/help**
* *h%{eoa%}lp%^ABL2*
* *holp0*

* ★*h%{eoa%}lp%^ABL2* (is not standard language)
* ★*h%{eoa%}lp0* (is not standard language)

helpen+V+PrfPrt: **veahkehit/auttaa/help**
* *h%{eoa%}lp%^ABL3%>en*
* *holp0%>en*

* ★*h%{eoa%}lp%^ABL3%>en* (is not standard language)
* ★*h%{eoa%}lp0%>en* (is not standard language)

**Ablaut grade 2 in class 4a (with generalised old conjunctive for northern and northeastern dialects)**
**Second part of ablaut grade 2 in class 4a+b+c and 5a+b (with generalised old conjunctive for northern and northeastern dialects)**

niamen+V+Ind+Prt+Sg3: **váldit/ottaa/take**
* *n%{iaeo%}%{aeØ%}m%^ABL2U*
* *naem0*

* ★*n%{iaeo%}%{aeØ%}m%^ABL2U* (is not standard language)
* ★*n%{iaeo%}%{aeØ%}m0* (is not standard language)

* ★*n%{iaeo%}%{aeØ%}m%^ABL2U* (is not standard language)
* ★*na%{aeØ%}m0* (is not standard language)

**Ablaut grade 2 in class 4b (with generalised old conjunctive for northern and northeastern dialects)**

dreapen+V+Ind+Prt+Sg3: **deaivvadit/tavata/meet**
* *dr%{eiao%}%{aeØ%}p%^ABL2U*
* *draep0*


**Ablaut grade 2 and 3 in class 4c**
**Second part of ablaut grade 2 in class 4c**

spreaken+V+Ind+Prt+Sg3: **hupmat/puhua/speak**
* *spr%{eio%}%{aØo%}k%^ABL2*
* *sprook0*

**Ablaut grade 2 in class 5a (with generalised old conjunctive for northern and northeastern dialects)**

giaven+V+Ind+Prt+Sg3: **addit/antaa/give**
* *g%{iae%}%{aeØ%}v%^ABL2U*
* *gaev0%>t*

**Ablaut grade 2 in class 5b (with generalised old conjunctive for northern and northeastern dialects)**

steaken+V+Ind+Prt+Sg3: **čugget/pistää/stab**
* *st%{eia%}%{aeØ%}k%^ABL2U*
* *staek0*

**Second part of ablaut grade 3 in class 1**

ryden+V+PrfPrc: **riidet/ratsastaa/ride**
* *r%{eiØ%}%{yaØ%}d%^ABL3%>en*
* *read0%>en*

* ★*r%{eiØ%}%{yaØ%}d%^ABL3%>en* (is not standard language)
* ★*r%{eiØ%}%{yaØ%}d0%>en* (is not standard language)

* ★*r%{eiØ%}%{yaØ%}d%^ABL3%>en* (is not standard language)
* ★*re%{yaØ%}d0%>en* (is not standard language)

**Second part of ablaut grade 3 in class 2a **

beden+V+Ind+Prt+Sg3: **bivdit/pyytää/ask**
* *b%{eouü%}%{Øeua%}d%^ABL3%>en*
* *boad0%>en*

* ★*b%{eouü%}%{Øeua%}d%^ABL3%>en* (is not standard language)
* ★*b%{eouü%}%{Øeua%}d0%>en* (is not standard language)

* ★*b%{eouü%}%{Øeua%}d%^ABL3%>en* (is not standard language)
* ★*bo%{Øeua%}d0%>en* (is not standard language)

**Second part of ablaut grade 3 in class 2b**

krupen+V+PrfPrc: **čákŋat/ryömiä/creep**
* *kr%{uüo%}%{uaØ%}p%^ABL3%>en*
* *kroap0%>en*

* ★*kr%{uüo%}%{uaØ%}p%^ABL3%>en* (is not standard language)
* ★*kr%{uüo%}%{uaØ%}p0%>en* (is not standard language)

* ★*kr%{uüo%}%{uaØ%}p%^ABL3%>en* (is not standard language)
* ★*kro%{uaØ%}p0%>en* (is not standard language)

* ★*kr%{uüo%}%{uaØ%}p%^ABL2* (is not standard language)
* ★*kro%{uaØ%}p0* (is not standard language)


**Ablaut grade 3 in class 4a+b**

**Second part of ablaut grade 3 in class 4a**

niamen+V+PrfPrt: **váldit/ottaa/take**
* *n%{iaeo%}%{aeØ%}m%^ABL3%>en*
* *noam0%>en*

* ★*n%{iaeo%}%{aeØ%}m%^ABL3%>en* (is not standard language)
* ★*n%{iaeo%}%{aeØ%}m0%>en* (is not standard language)

* ★*n%{iaeo%}%{aeØ%}m%^ABL3%>en* (is not standard language)
* ★*na%{aeØ%}m0%>en* (is not standard language)

**Ablaut grade 3 in class 4b**

dreapen+V+PrfPrt: **deaivvadit/tavata/meet**
* *dr%{eiao%}%{aeØ%}p%^ABL3%>en*
* *droap0%>en*

* ★*dr%{eiao%}%{aeØ%}p%^ABL3%>en* (is not standard language)
* ★*dr%{eiao%}%{aeØ%}p0%>en* (is not standard language)

* ★*dr%{eiao%}%{aeØ%}p%^ABL3%>en* (is not standard language)
* ★*dro%{aeØ%}p0%>en* (is not standard language)

**Second part of ablaut grade 3 in class 4c**

spreaken+V+PrfPrt: **hupmat/puhua/speak**
* *spr%{eio%}%{aØo%}k%^ABL3%>en*
* *sproak0%>en*

* ★*spr%{eio%}%{aØo%}k%^ABL3%>en* (is not standard language)
* ★*spr%{eio%}%{aØo%}k0%>en* (is not standard language)

* ★*spr%{eio%}%{aØo%}k%^ABL3%>en* (is not standard language)
* ★*spro%{aØo%}k0%>en* (is not standard language)

# Symbol affixes





Noun inflection
The Low German language nouns inflect in cases.





Proper noun inflection
The Low German language proper nouns inflect in the same cases as regular
nouns, but with a colon (':') as separator.



Verb inflection
The LOW SAXON language verbs inflect in persons. So far only for northwestern dialects.

tellen:tell
 Orthographic variation in consonant length




maken:maak
Orthographic variation in marking of long vowels, perfect participle '-ed'






völen:vööl
Orthographic variation in marking of long vowels, perfect participle '-d'






koaken:koak
No orthographic variation in marking of long vowels or consonants, perfect participle '-ed'






waien:wai
No orthographic variation in marking of long vowels or consonants, perfect participle '-d'






sakken:sakk
 Orthographic variation in consonant length, perfect participle '-ed'






ryden:r%{ei0%}%{ya0%}d
Strong verb class 1, 4c






beden:b%{eouü%}%{0eua%}d
Strong verb class 2






drinken:dr%{iua%}nk
Strong verb class 3





winnen:w%{iua%}nn
Strong verb class 3, stem ending with two identical consonants






niamen:n%{iaeo%}%{ae0%}m
Strong verb class 4a,b






steaken:st%{eia%}%{ae0%}k
Strong verb class 5










Adjective inflection
The Low German language adjectives compare.






INTRODUCTION TO MORPHOLOGICAL ANALYSER OF Low German LANGUAGE.


 # Definitions for Multichar_Symbols
 * %{åöä%}
 * %{Øäö%}
 * %{aö%}
 * %{Øä%}

strong verb class 1 1st part
strong verb class 1 2nd part
strong verb class 2a 1st part
strong verb class 2a 2nd part
strong verb class 2b 1st part
strong verb class 2b 2nd part
strong verb class 3a 
strong verb class 3bc
strong verb class 4a 1st part
strong verb class 4ab 2nd part
strong verb class 4b 1st part
strong verb class 4c 1st part
strong verb class 4c 2nd part 
strong verb class 5a 1st part 
strong verb class 5ab 2nd part
strong verb class 5b 1st part


TRIGGERS

 * %^CC2C  for Deleting second consonant in orthographic geminate
 * %^VV2V  for Orthographic vowel deletion in open syllable
 * %^IUML  for i-umlaut
 * %^UUML  for u-umlaut
 * %^ABL1NL  for non-lengthened ablaut grade 1 in class 4 and 5 in some southern dialects, ABL1 = ablaut grade 1, NL = non-lengthened
 * %^ABL1S  for shortened ablaut grade 1 in 2nd and 3rd sg. of present tense, S = shortened
 * %^ABL2  for ablaut grade 2 in preterite, ABL2 = ablaut grade 2
 * %^ABL2W  for specific preterite forms in Westphalian dialects, W = Westphalian
 * %^ABL2U  for irregular umlaut of ablaut grade 2 in class 4a,b and 5, U = (irregular) umlaut
 * %^ABL3  for long ablaut grade 3 in perfect participle
 * %^ABL3NL  for short ablaut grade 3 in some southern dialects, NL = non-lengthened 


## Analysis symbols
The morphological analyses of wordforms for the Low German
language are presented in this system in terms of the following symbols.
(It is highly suggested to follow existing standards when adding new tags).

The parts-of-speech are:

The parts of speech are further split up into:

The Usage extents are marked using following tags:

The nominals are inflected in the following Case and Number

The possession is marked as such:
The comparative forms are:
Numerals are classified under:
Verb moods are:
Verb personal forms are:
Other verb forms are

 * +Symbol = independent symbols in the text stream, like £, €, ©
Special symbols are classified with:
The verbs are syntactically split according to transitivity:
Special multiword units are analysed with:
Non-dictionary words can be recognised with:

Question and Focus particles:


Semantics are classified with


Derivations are classified under the morphophonetic form of the suffix, the
source and target part-of-speech.


Morphophonology
To represent phonologic variations in word forms we use the following
symbols in the lexicon files:

And following triggers to control variation

## Flag diacritics
We have manually optimised the structure of our lexicon using following
flag diacritics to restrict morhpological combinatorics - only allow compounds
with verbs if the verb is further derived into a noun again:
 |  @P.NeedNoun.ON@ | (Dis)allow compounds with verbs unless nominalised
 |  @D.NeedNoun.ON@ | (Dis)allow compounds with verbs unless nominalised
 |  @C.NeedNoun@ | (Dis)allow compounds with verbs unless nominalised

For languages that allow compounding, the following flag diacritics are needed
to control position-based compounding restrictions for nominals. Their use is
handled automatically if combined with +CmpN/xxx tags. If not used, they will
do no harm.
 |  @P.CmpFrst.FALSE@ | Require that words tagged as such only appear first
 |  @D.CmpPref.TRUE@ | Block such words from entering ENDLEX
 |  @P.CmpPref.FALSE@ | Block these words from making further compounds
 |  @D.CmpLast.TRUE@ | Block such words from entering R
 |  @D.CmpNone.TRUE@ | Combines with the next tag to prohibit compounding
 |  @U.CmpNone.FALSE@ | Combines with the prev tag to prohibit compounding
 |  @P.CmpOnly.TRUE@ | Sets a flag to indicate that the word has passed R
 |  @D.CmpOnly.FALSE@ | Disallow words coming directly from root.

Use the following flag diacritics to control downcasing of derived proper
nouns (e.g. Finnish Pariisi -> pariisilainen). See e.g. North Sámi for how to use
these flags. There exists a ready-made regex that will do the actual down-casing
given the proper use of these flags.
 |  @U.Cap.Obl@ | Allowing downcasing of derived names: deatnulasj.
 |  @U.Cap.Opt@ | Allowing downcasing of derived names: deatnulasj.

The word forms in Low German language start from the lexeme roots of basic
word classes, or optionally from prefixes:










We describe here how abbreviations are in Low German are read out, e.g.
for text-to-speech systems.

For example:

 * s.:syntynyt # ;  
 * os.:omaa% sukua # ;  
 * v.:vuosi # ;  
 * v.:vuonna # ;  
 * esim.:esimerkki # ; 
 * esim.:esimerkiksi # ; 


















































% komma% :,      Root ;
% tjuohkkis% :%. Root ;
% kolon% :%:     Root ;
% sárggis% :%-   Root ; 
% násti% :%*     Root ; 

