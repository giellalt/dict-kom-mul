##
2012-02-21
Paula is checking the Finnish translations and correcting them.

##
When the Finnish has been check and empty elements for Finnish meaning have been filled, we will continue on to the next step. The next step involves utilizing the structure of the Komi-Russian dictionary.

##Removed from VNEG before merging 2012-12-18:
   <!--
<entry> <lg><l>CiprianAndTrond</l><stg> <st Contlex="#">FixThis</st></stg></lg><pos>N</pos><e> <mg><m><head></head></m> <tg lang="eng">We need an attr saying _do not make lexc_</tg> </mg> </e></entry> -->
   <!-- comment: The problem here is the share of burden between xml and lexc. The VERBNEGATIVE lexicon looks like this: LEXICON VERBNEGATIVE оз+V+Neg+Ind+Prs+Sg1:ог K ; оз+V+Neg+Ind+Prs+Sg2:он K ; оз+V+Neg+Ind+Prs+Sg3:оз K ; ... The problem with the things below is that"l" and"st" are mixed."l" is used in two ways: a. as ditionary lookup term (expected is the wordform) b. as fst reference term (expected is оз) For the time being we should have a special contlex entry saying <contlex>NOCONTLEXGENERATION</contlex> with a corresponding if-statement in the xslt file generating the kt/tmp/out/ files. Conclusion reached (?) on Jan 1st ( :-) a new year's promise): We do the pronouns in the same way. Preliminary, we comment them out from the dict, awaiting an implementation of the NOCONTLEX contlex value. o In this way we can use sts from the individual personal pronouns once each ме тэ -->


##
2014-04-26
src>g '<t/>' *|c
   13148
 ==> there are 13148 empty t-elements in the src files

