Doc4TF pages for [SBLGNT](https://github.com/CenterBLC/SBLGNT/releases/download/v1.0.11/tf-2022.zip) (version 2022)
# Overview features by name (alphabetical)
Overview by [node type](featuresbynodetype.md), [feature type](featuresbytype.md), or [data type](featuresbydatatype.md).

Feature|Feature type|Data type|Available on nodes|Description|Examples
---|---|---|---|---|---
[`book`](book.md#readme)|[`Node`](featuresbytype.md#node)|[`String`](featuresbydatatype.md#string)|[`book`](featuresbynodetype.md#book) [`chapter`](featuresbynodetype.md#chapter) [`verse`](featuresbynodetype.md#verse) |A book name|`1_Corinthians` `1_John` `1_Peter` `1_Thessalonians`
[`book_code`](book_code.md#readme)|[`Node`](featuresbytype.md#node)|[`String`](featuresbydatatype.md#string)|[`book`](featuresbynodetype.md#book) |Short book abbreviation|`1Co` `1Jn` `1Pe` `1Th`
[`case`](case.md#readme)|[`Node`](featuresbytype.md#node)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |case|`` `nominative` `accusative` `genitive`
[`chapter`](chapter.md#readme)|[`Node`](featuresbytype.md#node)|[`Integer`](featuresbydatatype.md#integer)|[`chapter`](featuresbynodetype.md#chapter) [`verse`](featuresbynodetype.md#verse) |A chapter number|`1` `2` `3` `4`
[`clause`](clause.md#readme)|[`Node`](featuresbytype.md#node)|[`Integer`](featuresbydatatype.md#integer)|[`clause`](featuresbynodetype.md#clause) |A clause number|`1` `2` `3` `4`
[`degree`](degree.md#readme)|[`Node`](featuresbytype.md#node)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |degree|``
[`dict_abc_order`](dict_abc_order.md#readme)|[`Node`](featuresbytype.md#node)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |words with their dictionary order|`3455` `2515` `837` `4627`
[`gloss`](gloss.md#readme)|[`Node`](featuresbytype.md#node)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |BibleOL English gloss|`the` `and, even, also, namely` `he, she, it, they, them, same` `you`
[`gn`](gn.md#readme)|[`Node`](featuresbytype.md#node)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |gender|`` `m` `f` `n`
[`lemma`](lemma.md#readme)|[`Node`](featuresbytype.md#node)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |Lemma|`ὁ` `καί` `αὐτός` `σύ`
[`lemma_dictform`](lemma_dictform.md#readme)|[`Node`](featuresbytype.md#node)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |BibleOL Greek dictionary form|`ὁ, ἡ, τό` `καί` `αὐτός, -ή, -ό` `σύ`
[`lemma_freq`](lemma_freq.md#readme)|[`Node`](featuresbytype.md#node)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |word frequency|`19769` `8973` `5546` `2894`
[`mood`](mood.md#readme)|[`Node`](featuresbytype.md#node)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |mood|`` `indicative` `participle` `infinitive`
[`morph`](morph.md#readme)|[`Node`](featuresbytype.md#node)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |Word morphological tag based on Maurice A Robinson's analysis|`C- --------` `P- --------` `D- --------` `N- ----NSM-`
[`morphology`](morphology.md#readme)|[`Node`](featuresbytype.md#node)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |morphology|`C- --------` `P- --------` `D- --------` `N- ----NSM-`
[`normalized_word`](normalized_word.md#readme)|[`Node`](featuresbytype.md#node)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |Normalized word|`καί` `ὁ` `δέ` `ἐν`
[`nu`](nu.md#readme)|[`Node`](featuresbytype.md#node)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |number|`sg` `` `pl`
[`orig_order`](orig_order.md#readme)|[`Node`](featuresbytype.md#node)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |number of word position in NT|`1` `10` `100` `1000`
[`oslots`](oslots.md#readme)|[`Edge`](featuresbytype.md#edge)|[`String`](featuresbydatatype.md#string)||No feature description|No values
[`otype`](otype.md#readme)|[`Node`](featuresbytype.md#node)|[`String`](featuresbydatatype.md#string)||No feature description|No values
[`ps`](ps.md#readme)|[`Node`](featuresbytype.md#node)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |person|`` `p3` `p2` `p1`
[`sentence`](sentence.md#readme)|[`Node`](featuresbytype.md#node)|[`Integer`](featuresbydatatype.md#integer)|[`sentence`](featuresbynodetype.md#sentence) |A sentence number|`1` `2` `3` `4`
[`strongs`](strongs.md#readme)|[`Node`](featuresbytype.md#node)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |Strong's number|`3588` `2532` `846` `4771`
[`tense`](tense.md#readme)|[`Node`](featuresbytype.md#node)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |tense|`` `aorist` `present` `future`
[`text`](text.md#readme)|[`Node`](featuresbytype.md#node)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |Text as it appears in SBLGNT|`καὶ` `ὁ` `ἐν` `τοῦ`
[`translit`](translit.md#readme)|[`Node`](featuresbytype.md#node)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |lemma transliteration|`o` `kai` `autos` `su`
[`verse`](verse.md#readme)|[`Node`](featuresbytype.md#node)|[`Integer`](featuresbydatatype.md#integer)|[`verse`](featuresbynodetype.md#verse) |A verse number|`1` `2` `3` `5`
[`voice`](voice.md#readme)|[`Node`](featuresbytype.md#node)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |voice|`` `active` `middle` `passive`
[`vrsnum`](vrsnum.md#readme)|[`Node`](featuresbytype.md#node)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |N-word in verse|`1` `2` `3` `4`
[`word`](word.md#readme)|[`Node`](featuresbytype.md#node)|[`String`](featuresbydatatype.md#string)|[`word`](featuresbynodetype.md#word) |Word with punctuation stripped|`καὶ` `ὁ` `ἐν` `δὲ`


Created on Nov. 04, 2024 using [Doc4TF version 0.5.2b (July 10, 2024)](https://github.com/tonyjurg/Doc4TF/blob/main/CreateFeatureDoc.ipynb)