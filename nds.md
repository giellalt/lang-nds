


















* Sets for POS sub-categories





* Sets for Semantic tags





* Sets for Morphosyntactic properties






































































































































































* Sets for verbs


- V is all readings with a V tag in them, REAL-V should
be the ones without an N tag following the V.  
The REAL-V set thus awaits a fix to the preprocess V ... N bug.



* The set COPULAS is for predicative constructions







* NP sets defined according to their morphosyntactic features







* The PRE-NP-HEAD family of sets

These sets model noun phrases (NPs). The idea is to first define whatever can
occur in front of the head of the NP, and thereafter negate that with the
expression **WORD - premodifiers**.












The set **NOT-NPMOD** is used to find barriers between NPs.
Typical usage: ... (*1 N BARRIER NPT-NPMOD) ...
meaning: Scan to the first noun, ignoring anything that can be
part of the noun phrase of that noun (i.e., "scan to the next NP head")






* Miscellaneous sets





















* Border sets and their complements













* Syntactic sets




These were the set types.



## HABITIVE MAPPING


* **hab1** 


* **hab2** 

* **hab3** (<hab> @ADVL>) for hab-actor and hab-case; if leat to the right, and Nom to the right of leat. Lots of restrictions.



* **habNomLeft** 


* **hab4** 	



* **hab6** 

* **hab7** 

* **hab8** This is not HAB
* **hab5**  This is not HAB



* **habDain** (<hab> @ADVL>) for (Pron Dem Pl Loc) if leat followed by Nom to the right




* **habGen** (<hab> @<ADVL) hab for Gen; if Gen is located in the end of the sentence and Nom is sentence initial










































































* **spred<obj** (@SPRED<OBJ) for Acc; the object of an SPRPED. Not to be mistaken with OPRED. If SPRED is to the left, and copulas is to the left of it. Nom or Hab are found sentence initially.


* **Hab<spred** (@<SPRED) for Nom; if copulas, goallut or jápmit is FMAINV and habitive or human Loc is found to the left. OR: if Ill or @Pron< followed by HAB are found to the left.

* **Hab>Advlcase<spred** (<ext> @<SUBJ) for Nom; it allows adverbials with Ill/Loc/Com/Ess to be found inbetween HAB and <ext>.

* **Nom>Advlcase<spred** (<ext> @<SUBJ) for Nom; it allows adverbials with Ill/Loc/Com/Ess to be found inbetween Nom and <ext> @<SUBJ.

* **<spred** (<ext> @<SUBJ) for Nom; if copulas to the left, and some kind of adverb, N Loc, time related word or Po to the left of it. OR: if Ill or @Pron< to the left, followed by copulas and the before mentioned to the left of copulas. 

* **<spred** (<ext> @<SUBJ) for Nom, but not for Pers. To the left boahtit or heaŋgát as MAINV, and futher to the left is some kind of place related word, or time related word


* **<spredQst1** (<ext> @<SUBJ) for Nom in a typically question sentence; if A) Hab, some kind of place word, Po or Nom to the left, and Qst followed by copulas to the left. B) same as a, only the Qst-pcle is attached to copulas. C) Qst to the left, with copulas to its left, but not if two Nom:s are found somewhere to the right. D) copulas to the left, and BOS to the left. E) Loc or Ill to the left, and Loc or Hab to the left of this, Qst and copulas to the left. F) Num @>N to the left, Hab, some kind of place word, Po or Nom to the left, and Qst followed by copulas to the left. NOTE) for all these rules; human, Loc or Sem/Plc not allowed to the right.

* **<spredQst2** (@<SPRED) for Nom; in a typically question sentence; differs from <spredQst1 by not beeing as restricted to the right. Though you are not allowed to be Pers or human.

* **Nom<spredQst** (@<SPRED) for Nom; in a typically question sentence. Differs from <spredQst2 by letting Nom be found between SPRED and copulas



* **<spred** (@<SPRED) for A Nom or N Nom if; the subject Nom is on the same side of copulas as you: on the right side of copulas

* **<spredVeara** (@<SPRED) for veara + Nom; if genitive immediately to the right, and intransitive mainverb to the right of genitive

* **leftCop<spred** (@<SPRED) for Nom; if copulas is the main verb to the left, and there is no Ess found to the left of cop (note that Loc is allowed between target and cop). OR: if you are Coll or Sem/Group with copulas to your left. 

* **<spredLocEXPERIMENT** (@<SPRED) for material Loc; if you are to the right of copulas, and the Nom to the left of copulas is not a hab-actor


* **NumTime** (@<SPRED) for A Nom

* **<spredSg** (@<SPRED) for Sg Nom	

* **<spredPg** (@<SPRED) for Pl Nom	

* **<spred** (@<SPRED) for Nom; if copulas to the left, and Nom or sentence boundary to the left of copulas. First one to the right is EOS.

* **<spred** (@<SPRED) for N Ess

* **spredEss>** (@SPRED>) for N Ess; if copulas to the right of you, and if an NP with nom-case first one to your left.

* **HABSpredSg>** (@SPRED>) for Nom; if habitive first one to the left, followed by copulas.

* **GalleSpred>** (@SPRED>) for Num Nom; if sentence initial

* **spredSgMII>** (@SPRED>)

* **r492>** (@SPRED>) for Interr Gen; consisting only of negations. You are not allowed to be MII. You are not allowed to have an adjective or noun to yor right. You are not allowed to have a verb to your right; the exception beeing an aux.



* **AdjSpredSg>** (@SPRED>) for A Sg Nom; if copulas to the right, but not if A or @<SPRED are found to the right of copulas

* **SpredSg>Hab** (@SPRED>) for Nom; if you are sentence initial, copulas is located to the right, and there is a habitive to the right of copulas



* **Spred>SubjInf** (@SPRED>) for Nom; if copulas to the right, and the subject of copulas is an Inf to the right

* **spredCoord** (@<SPRED) coordination for Nom; only if there already is a SPRED to the left of CNP. Not if there is some kind of comparison involved.






* **subj>Sgnr1** (@SUBJ>) for Nom Sg, including Indef Nom if; VFIN + Sg3 or Pl3 to the right (VFIN not allowed to the left) 

* **subj>Du** (@SUBJ>) for dual nominatives, including Coll Nom. VFIN + Du3 to the right. 
* **subj>Pl** (@SUBJ>) for plural nominatives, including Coll and Sem/Group. VFIN + Pl3 to the right.

* **subj>Pl** (@SUBJ>) for plural nominatives


* **subj>Sgnr2** (@SUBJ>) for Nom Sg; if VFIN + Sg3 to the right.

* **<subjSg** (@<SUBJ) for Nom Sg; if VFIN Sg3 or Du2 to the left (no HAB allowed to the left).




















* **f<advl** (@-F<ADVL) for infinite adverbials

* **f<advl** (@-F<ADVL) for infinite adverbials



* **s-boundary=advl>** (@ADVL>) for ADVL that resemble s-booundaries. Mainverb to the right.




* **-fobj>** (@-FOBJ>) for Acc 

* **-fobj>** (@-FOBJ>) for Acc




* **advl>mainV** (@ADVL>) if; finite mainverb not found to the left, but the finite mainverb is found to the right.


* **<advl** (@<ADVL) if; finite mainverb found to the left. Not if a comma is found immediately to the left and a finite mainverb is located somewhere to the right of this comma.




* **<advlPoPr** (@<ADVL) if mainverb to the left.
* **advlPoPr>** (@<ADVL) if mainverb to the right.



* **advlEss>** (@<ADVL) for weather and time Ess, if FMAINV to the left.






* **advl>inbetween** (@ADVL>) for Adv; if inbetween two sentenceboundaries where no mainverb is present.

* **comma<advlEOS** (@<ADVL) if; comma found to the left and the finite mainverb to the left of comma. To the right is the end of the sentence.



* **advlBOS>** (@ADVL>) if; you are N Ill and found sentnece initially. First one to your right is a clause.


* **<advlPoEOS** (@<ADVL) for Po; if you are found at the very end of a sentence. A mainverb is needed to the right though.



* **cleanupILL<advl** (@<ADVL) for N Ill if; there are no boundarysymbols to your left, if you arent already @N< OR @APP-N<, and no mainverb is to yor left.











* **<opredAAcc** (@<OPRED) for A Acc; if an other accusative to the left, and a transtive verb to the left of it. OR: if a transitive verb to the left, and an accusative to the left of it.


### sma object









* **<advlEss** (@<ADVL) for ESS-ADVL if; FMAINV to the left
* **<spredEss** (@<SPRED) for N Ess if; FMAINV to the left is intransitive or bargat





## SUBJ MAPPING - leftovers

## OBJ MAPPING - leftovers


## HNOUN MAPPING
















* * *
<small>This (part of) documentation was generated from [../src/cg3/functions.cg3](http://github.com/giellalt/lang-nds/blob/main/../src/cg3/functions.cg3)</small>================================================== !
The Low German morphophonological/twolc rules file 
================================================== !

This file documents the [phonology.twolc file](http://github.com/giellalt/lang-nds/blob/main/src/fst/phonology.twolc) 




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
* * *
<small>This (part of) documentation was generated from [../src/fst/phonology.twolc](http://github.com/giellalt/lang-nds/blob/main/../src/fst/phonology.twolc)</small>Nouns
No nouns so far


* * *
<small>This (part of) documentation was generated from [../src/fst/stems/nouns.lexc](http://github.com/giellalt/lang-nds/blob/main/../src/fst/stems/nouns.lexc)</small>Numerals
No numerals so far


* * *
<small>This (part of) documentation was generated from [../src/fst/stems/numerals.lexc](http://github.com/giellalt/lang-nds/blob/main/../src/fst/stems/numerals.lexc)</small>Adjectives
No adjectives so far




* * *
<small>This (part of) documentation was generated from [../src/fst/stems/adjectives.lexc](http://github.com/giellalt/lang-nds/blob/main/../src/fst/stems/adjectives.lexc)</small>Prefixes
No prefixes so far



* * *
<small>This (part of) documentation was generated from [../src/fst/stems/prefixes.lexc](http://github.com/giellalt/lang-nds/blob/main/../src/fst/stems/prefixes.lexc)</small>Pronouns
No pronouns so far.


* * *
<small>This (part of) documentation was generated from [../src/fst/stems/pronouns.lexc](http://github.com/giellalt/lang-nds/blob/main/../src/fst/stems/pronouns.lexc)</small>Verbs
So far only a couple of verbs








Strong verbs 

Class I


Class II 



Class III







Class IV



Class V




* * *
<small>This (part of) documentation was generated from [../src/fst/stems/verbs.lexc](http://github.com/giellalt/lang-nds/blob/main/../src/fst/stems/verbs.lexc)</small>
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







* * *
<small>This (part of) documentation was generated from [../src/fst/root.lexc](http://github.com/giellalt/lang-nds/blob/main/../src/fst/root.lexc)</small>
# Symbol affixes





* * *
<small>This (part of) documentation was generated from [../src/fst/affixes/symbols.lexc](http://github.com/giellalt/lang-nds/blob/main/../src/fst/affixes/symbols.lexc)</small>Noun inflection
The Low German language nouns inflect in cases.





* * *
<small>This (part of) documentation was generated from [../src/fst/affixes/nouns.lexc](http://github.com/giellalt/lang-nds/blob/main/../src/fst/affixes/nouns.lexc)</small>Adjective inflection
The Low German language adjectives compare.





* * *
<small>This (part of) documentation was generated from [../src/fst/affixes/adjectives.lexc](http://github.com/giellalt/lang-nds/blob/main/../src/fst/affixes/adjectives.lexc)</small>Verb inflection
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










* * *
<small>This (part of) documentation was generated from [../src/fst/affixes/verbs.lexc](http://github.com/giellalt/lang-nds/blob/main/../src/fst/affixes/verbs.lexc)</small>Proper noun inflection
The Low German language proper nouns inflect in the same cases as regular
nouns, but with a colon (':') as separator.



* * *
<small>This (part of) documentation was generated from [../src/fst/affixes/propernouns.lexc](http://github.com/giellalt/lang-nds/blob/main/../src/fst/affixes/propernouns.lexc)</small>


We describe here how abbreviations are in Low German are read out, e.g.
for text-to-speech systems.

For example:

 * s.:syntynyt # ;  
 * os.:omaa% sukua # ;  
 * v.:vuosi # ;  
 * v.:vuonna # ;  
 * esim.:esimerkki # ; 
 * esim.:esimerkiksi # ; 


* * *
<small>This (part of) documentation was generated from [../src/transcriptions/transcriptor-abbrevs2text.lexc](http://github.com/giellalt/lang-nds/blob/main/../src/transcriptions/transcriptor-abbrevs2text.lexc)</small>















































% komma% :,      Root ;
% tjuohkkis% :%. Root ;
% kolon% :%:     Root ;
% sárggis% :%-   Root ; 
% násti% :%*     Root ; 

* * *
<small>This (part of) documentation was generated from [../src/transcriptions/transcriptor-numbers-digit2text.lexc](http://github.com/giellalt/lang-nds/blob/main/../src/transcriptions/transcriptor-numbers-digit2text.lexc)</small>
[ L A N G U A G E ]  G R A M M A R   C H E C K E R









# DELIMITERS


# TAGS AND SETS



## Tags


This section lists all the tags inherited from the fst, and used as tags
in the syntactic analysis. The next section, **Sets**, contains sets defined
on the basis of the tags listed here, those set names are not visible in the output.




### Beginning and end of sentence
BOS
EOS



### Parts of speech tags

N
A
Adv
V
Pron
CS
CC
CC-CS
Po
Pr
Pcle
Num
Interj
ABBR
ACR
CLB
LEFT
RIGHT
WEB
QMARK
PPUNCT
PUNCT

COMMA
¶



### Tags for POS sub-categories

Pers
Dem
Interr
Indef
Recipr
Refl
Rel
Coll
NomAg
Prop
Allegro
Arab
Romertall


### Tags for morphosyntactic properties

Nom
Acc
Gen
Ill
Loc
Com
Ess
Ess
Sg
Du
Pl
Cmp/SplitR
Cmp/SgNom Cmp/SgGen
Cmp/SgGen
PxSg1
PxSg2
PxSg3
PxDu1
PxDu2
PxDu3
PxPl1
PxPl2
PxPl3
Px

Comp
Superl
Attr
Ord
Qst
IV
TV
Prt
Prs
Ind
Pot
Cond
Imprt
ImprtII
Sg1
Sg2
Sg3
Du1
Du2
Du3
Pl1
Pl2
Pl3
Inf
ConNeg
Neg
PrfPrc
VGen
PrsPrc
Ger
Sup
Actio
VAbess



Err/Orth



### Semantic tags

Sem/Act
Sem/Ani
Sem/Atr
Sem/Body
Sem/Clth
Sem/Domain
Sem/Feat-phys
Sem/Fem
Sem/Group
Sem/Lang
Sem/Mal
Sem/Measr
Sem/Money
Sem/Obj
Sem/Obj-el
Sem/Org
Sem/Perc-emo
Sem/Plc
Sem/Sign
Sem/State-sick
Sem/Sur
Sem/Time
Sem/Txt

HUMAN

HAB-ACTOR
HAB-ACTOR-NOT-HUMAN


PROP-ATTR
PROP-SUR



TIME-N-SET


###  Syntactic tags

@+FAUXV
@+FMAINV
@-FAUXV
@-FMAINV
@-FSUBJ>
@-F<OBJ
@-FOBJ>
@-FSPRED<OBJ
@-F<ADVL
@-FADVL>
@-F<SPRED
@-F<OPRED
@-FSPRED>
@-FOPRED>
@>ADVL
@ADVL<
@<ADVL
@ADVL>
@ADVL
@HAB>
@<HAB
@>N
@Interj
@N<
@>A
@P<
@>P
@HNOUN
@INTERJ
@>Num
@Pron<
@>Pron
@Num<
@OBJ
@<OBJ
@OBJ>
@OPRED
@<OPRED
@OPRED>
@PCLE
@COMP-CS<
@SPRED
@<SPRED
@SPRED>
@SUBJ
@<SUBJ
@SUBJ>
SUBJ
SPRED
OPRED
@PPRED
@APP
@APP-N<
@APP-Pron<
@APP>Pron
@APP-Num<
@APP-ADVL<
@VOC
@CVP
@CNP
OBJ
<OBJ
OBJ>
<OBJ-OTHERS
OBJ>-OTHERS
SYN-V
@X





## Sets containing sets of lists and tags

This part of the file lists a large number of sets based partly upon the tags defined above, and
partly upon lexemes drawn from the lexicon.
See the sourcefile itself to inspect the sets, what follows here is an overview of the set types.



### Sets for Single-word sets

INITIAL


### Sets for word or not

WORD
REAL-WORD
REAL-WORD-NOT-ABBR
NOT-COMMA


### Case sets

ADLVCASE

CASE-AGREEMENT
CASE

NOT-NOM
NOT-GEN
NOT-ACC

### Verb sets


NOT-V

### Sets for finiteness and mood

REAL-NEG

MOOD-V

NOT-PRFPRC


### Sets for person

SG1-V
SG2-V
SG3-V
DU1-V
DU2-V
DU3-V
PL1-V
PL2-V
PL3-V





### Pronoun sets

















### Adjectival sets and their complements




### Adverbial sets and their complements




### Sets of elements with common syntactic behaviour


### NP sets defined according to their morphosyntactic features








### The PRE-NP-HEAD family of sets

These sets model noun phrases (NPs). The idea is to first define whatever can
occur in front of the head of the NP, and thereafter negate that with the
expression **WORD - premodifiers**.





















### Border sets and their complements











### Grammarchecker sets








* * *
<small>This (part of) documentation was generated from [../tools/grammarcheckers/grammarchecker.cg3](http://github.com/giellalt/lang-nds/blob/main/../tools/grammarcheckers/grammarchecker.cg3)</small>