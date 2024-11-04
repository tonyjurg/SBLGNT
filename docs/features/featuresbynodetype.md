Doc4TF pages for [SBLGNT](https://github.com/CenterBLC/SBLGNT/releases/download/v1.0.11/tf-2022.zip) (version 2022)
# Overview features by node type
Overview by [name](featuresbyname.md), [data type](featuresbydatatype.md), or [feature type](featuresbytype.md).
## book

Feature|Feature type|Data type|Description|Examples
---|---|---|---|---
[`book`](book.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|A book name|`1_Corinthians` `1_John` `1_Peter` `1_Thessalonians`
[`book_code`](book_code.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|Short book abbreviation|`1Co` `1Jn` `1Pe` `1Th`
## chapter

Feature|Feature type|Data type|Description|Examples
---|---|---|---|---
[`book`](book.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|A book name|`1_Corinthians` `1_John` `1_Peter` `1_Thessalonians`
[`chapter`](chapter.md#readme)|[`Node`](featuresbytype.md#Node)|[`Integer`](featuresbydatatype.md#Integer)|A chapter number|`1` `2` `3` `4`
## sentence

Feature|Feature type|Data type|Description|Examples
---|---|---|---|---
[`sentence`](sentence.md#readme)|[`Node`](featuresbytype.md#Node)|[`Integer`](featuresbydatatype.md#Integer)|A sentence number|`1` `2` `3` `4`
## verse

Feature|Feature type|Data type|Description|Examples
---|---|---|---|---
[`book`](book.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|A book name|`1_Corinthians` `1_John` `1_Peter` `1_Thessalonians`
[`chapter`](chapter.md#readme)|[`Node`](featuresbytype.md#Node)|[`Integer`](featuresbydatatype.md#Integer)|A chapter number|`1` `2` `3` `4`
[`verse`](verse.md#readme)|[`Node`](featuresbytype.md#Node)|[`Integer`](featuresbydatatype.md#Integer)|A verse number|`1` `2` `3` `5`
## clause

Feature|Feature type|Data type|Description|Examples
---|---|---|---|---
[`clause`](clause.md#readme)|[`Node`](featuresbytype.md#Node)|[`Integer`](featuresbydatatype.md#Integer)|A clause number|`1` `2` `3` `4`
## word

Feature|Feature type|Data type|Description|Examples
---|---|---|---|---
[`case`](case.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|case|`` `nominative` `accusative` `genitive`
[`degree`](degree.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|degree|``
[`dict_abc_order`](dict_abc_order.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|words with their dictionary order|`3455` `2515` `837` `4627`
[`gloss`](gloss.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|BibleOL English gloss|`the` `and, even, also, namely` `he, she, it, they, them, same` `you`
[`gn`](gn.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|gender|`` `m` `f` `n`
[`lemma`](lemma.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|Lemma|`ὁ` `καί` `αὐτός` `σύ`
[`lemma_dictform`](lemma_dictform.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|BibleOL Greek dictionary form|`ὁ, ἡ, τό` `καί` `αὐτός, -ή, -ό` `σύ`
[`lemma_freq`](lemma_freq.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|word frequency|`19769` `8973` `5546` `2894`
[`mood`](mood.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|mood|`` `indicative` `participle` `infinitive`
[`morph`](morph.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|Word morphological tag based on Maurice A Robinson's analysis|`C- --------` `P- --------` `D- --------` `N- ----NSM-`
[`morphology`](morphology.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|morphology|`C- --------` `P- --------` `D- --------` `N- ----NSM-`
[`normalized_word`](normalized_word.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|Normalized word|`καί` `ὁ` `δέ` `ἐν`
[`nu`](nu.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|number|`sg` `` `pl`
[`orig_order`](orig_order.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|number of word position in NT|`1` `10` `100` `1000`
[`ps`](ps.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|person|`` `p3` `p2` `p1`
[`strongs`](strongs.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|Strong's number|`3588` `2532` `846` `4771`
[`tense`](tense.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|tense|`` `aorist` `present` `future`
[`text`](text.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|Text as it appears in SBLGNT|`καὶ` `ὁ` `ἐν` `τοῦ`
[`translit`](translit.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|lemma transliteration|`o` `kai` `autos` `su`
[`voice`](voice.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|voice|`` `active` `middle` `passive`
[`vrsnum`](vrsnum.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|N-word in verse|`1` `2` `3` `4`
[`word`](word.md#readme)|[`Node`](featuresbytype.md#Node)|[`String`](featuresbydatatype.md#String)|Word with punctuation stripped|`καὶ` `ὁ` `ἐν` `δὲ`


Created on Nov. 04, 2024 using [Doc4TF version 0.5.2b (July 10, 2024)](https://github.com/tonyjurg/Doc4TF/blob/main/CreateFeatureDoc.ipynb)