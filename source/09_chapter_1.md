# The Issue of \newline <br>Sign Language Grammars

Sign languages have been at the center of much debate about iconicity in linguistic encoding. Language researchers went from completely rejecting sign languages as natural, full-fledged languages to finding empirical tests to prove that they follow linguistic rules just as spoken languages do. Although some of the previous research on proving the linguistic status of sign languages had to ignore their iconic component, recent research takes iconicity as an inherent property of human language and central to understanding its intricacies, and pushes the limits of linguistic research in favor of abandoning the old black-or-white understanding of structured tools of interpersonal communication and bringing the threshold of required arbitrariness down as well as shifting its focus to more abstract concepts found in the building blocks of Language. In this dissertation, I study a highly iconic environment, instrumental constructions, in three unrelated sign languages with the aim of finding explanations to why signers make certain linguistic decisions and why their decisions show a great deal of variation. My findings show that there are multiple intertwined factors at play that lie not only internally to the linguistic system but also elsewhere externally, including preference and world knowledge. This dissertation takes a holistic approach to the phenomenon known as Language and seeks flexible answers to the stochastic behaviors of signers while building a model that relies on statistical and computational analyses of naturalistic data. 

## Introduction

<mark>This is the introduction. To include a citation to the text, just add the citation key shown in the references.bib file. The style of the citation is determined by the ref_format.csl file. For example, cite like this [@Cousteau1963].</mark>

Sign languages use *classifier constructions* to encode certain grammatical relations. The term *classifier* was borrowed from studies conducted on spoken language morphology <mark>(XXXX – the classifier types person – Supalla?)</mark> and has since become a popular term to refer to many instances of different types of morphological markings. <mark>[INSERT: What are classifiers in spoken languages? Why are the structures in question called ‘classifier constructions’ in signed languages?]</mark>. Sign languages have a very extensive range of types of classifier use: from marking localizations in space to much more complex forms involving multiple discourse participants (XXXX – check SL classifier literature). The predicate of an instrumental utterance is a classic example of a complex classifier predicate and it is precisely what this dissertation is about.

	[INSERT: Instrumental example and below insert a paragraph talking about how this construction might seem like a series of gestures – try to stick with a simple example such as “cut with scissors”] 

I take the space in this chapter to walk the reader from the general key concepts in sign language research to more specific areas concerning classifier constructions. I will then present some broader literature on instrumentals followed by the related work that has been done on sign language instrumental constructions. To be more precise, I will talk about high level topics that include (i) different levels of linguistic complexity in sign languages, (ii) how the morphologies of sign languages are structured and where they differ from those of spoken languages, (iii) gesture and how it permeates the grammatical fabric of sign languages, (iv) the interfaces of iconicity and arbitrariness in linguistic encoding and how that manifests in the lexicon. I will then dig deeper into more specific matters on (v) classifier predicates in sign languages, (vi) the semantics of instrumentals and (vii) instrumental utterances in sign languages, which will pave the way to the next chapter on the hypotheses and production data. By the end of this chapter, I will have shown to the reader that while sign languages are home to domain-specific structures, they do nonetheless follow the same abstract concepts as spoken languages do such as argument and event structure, theta roles and morphemic representation.


<!-- 
To include a reference, add the citation key shown in the references.bib file.
-->

## Levels of Linguistic Complexity

Sign language linguistics lie in a secluded position within the dominant field of spoken language linguistics while also intersecting with the fields of psychology and gesture research. Despite the misunderstandings concerning sign languages and the limited availability of research on them, throughout many years of research they have proven to provide key concepts in understanding the human linguistic capabilities and cognitive processes which were previously unknown to researchers. Some of these concepts broaden the limits of the levels of linguistic representation and complexity which were once deemed to have reached their limits. Sign languages, despite their standalone positioning far from spoken languages, serve the same communicative purposes and functions that spoken languages do and enrich the ways linguistic complexity can manifest at the interdependent levels of phonological, morphological and syntactic representations.

>> p. 55 in Brentari - Complexity
Complexity is a phenomenon much talked about in linguistics. Some forms are considered to be more complex than others and complexity comes in different flavors (insert Sinnemaki and stuff here – both citations and discussion on complexity). Sign languages are no different than spoken ones with regards to complexity. In the case of classifier use to express instrumental meaning, we can talk about phonological, morphological, semantic and syntactic complexity. Phonological complexity can be perceived at the levels of ease of articulation of the phonological building blocks of a sign. Signs can be decomposed into phonemes, and phonemes are made up of sign features:  handshape, movement and place of articulation (see Brentari, 1998; Sandler, 1989). Each handshape has an internal structure with varying complexity. Fewer features specifications mean less complexity. Less complex forms are more prevalent than complex ones in language production (IS THIS TRUE? CITE IF IT IS – talk about DB’s framework here and say how certain sign languages tend to avoid the use of complex handshapes, then wrap up with how we won’t be looking at phonological complexity in this dissertation).

Morphemes and syllables are different levels of linguistic representation. The extent of a syllable is determined by how much dependent phonological material its nucleus can carry with respect to the specific phonological limitations of a language. For instance, Turkish does not allow onset consonant clusters (*CCV, *CCVC, *CCVCC), while coda consonant clusters are allowed with certain restrictions that obey the sonority hierarchy (CVCC, VCC). In a recent computational study aiming to parse Turkish text into morphemes, I found that the most frequent syllable structure in Turkish is CV (XY%), followed by CVC (XY%), VC(XY%), VCC(XY%), CVCC(XY%) (total number of words: XXX, total number of syllables: YYY). Sign languages, as all natural languages do, respect certain rules in structuring their syllables and distributing their meaning bearing units, i.e. morphemes, across linguistic signals.

Sign languages use the gestural modality as an articulatory system to transmit information and the visual modality to as a perceptual system to receive it. Spoken languages, on the other hand, use different channels to transmit (vocal modality) and to receive (auditory modality) information. These most fundamental differences between the two prevalent modes of human language create a dichotomy of systems that serve the same purpose of communication but with discernible particularities in their subcomponents. The following in Table X.Y. from Meier (2002) summarizes the differences between signed and spoken languages in their articulatory and perceptual systems.

<!-- Force the table onto a newpage -->

<!-- \newpage -->

*Sign* | *Speech*
:-: | :-:
• Light source external to the signer | • Sound source internal to the speaker
• Articulators move in a transparent space, relatively massive and paired | • Articulators largely hidden, relatively small and not paired

Table: Key differences between signed and spoken languages' *articulatory* systems. \label{ref_a_table}

*Sign* | *Speech*
:-: | :-:
• Signer must be in view of addressee | • Speaker need not be in view of addressee]
• High spatial resolution of vision; lower temporal resolution than audition | • High temporal resolution of audition; lower spatial resolution than vision
• Visual stimuli generally not categorically perceived | • Speech is categorically perceived
• Articulatory gestures as the object of perception | • Acoustic events as the object of perception

Table: Key differences between signed and spoken languages' *perceptual* systems. \label{ref_a_table}

These differences in the nature of the two modalities are manifested in how the atomic units of meaning as well as syllables are formed across modalities. Brentari (1998), argues that movement is the locus of sonority in a sign syllable and therefore visually the most salient part of a sign. She proves her point by discussing how an epenthetical movement is inserted when a sign underlyingly lacks a movement (e.g. the ASL sign THINK), pretty much an analog of how spoken languages break up consonant clusters with a semantically vacuous, phonologically unmarked epenthetical vowel that forms the nucleus of an otherwise missing syllable. Since sign languages, contra spoken languages, have multiple articulators with multiple joint sets at different anatomical levels, multiple, simultaneous movements happening at different joints is a possibility. This, however, according to Brentari, does not necessarily mean every single movement in a single time slot constitutes a syllable of its own. She argues that the longer movement in a sign will be the nucleus of the syllable. She shows that path movement is more sonorous than a local, smaller movement because it has more visibility for the interlocutor and is perceived as ‘louder’ than a local movement. Brentari (1998)’s SYLLABLE COUNTING CRITERIA in are as follows:

a.	The number of syllables in a sequence of signs equals the number of sequential movements in that string.
b.	When several shorter (e.g. trilled) movements co-occur with a single (e.g. path) movement of longer duration, the longer movement is the one to which the syllable refers – e.g. ASL DREAM, which is one syllable containing repeated trilled bending movements.
c.	When two or more movements occur at exactly the same time, it counts as one syllable, e.g. ASL INFORM is one syllable containing an aperture change and a path movement.

A different level of complexity, at the level of morphological representation, can be measured in terms of how semantically-loaded a linguistic form is. Sign languages differ from spoken languages in one important aspect: spoken languages tend to stack meanings horizontally while sign languages allow for heavier vertical stacking (CITE). This is known as sequential (horizontal) vs. simultaneous (vertical) morphology and has consequences for both how the morphology is structured and how it interacts with phonology and semantics. In other words, while a single sign is likely to be monosyllabic but polymorphemic, a single spoken morpheme tends to overlap with one or more syllables, oftentimes spanning multiple syllable nuclei. The following schemata in Figure \ref{morph-syll} and the Turkish sentence in (@em) illustrate this distinction.

<!-- 
Figures can be added with the following syntax:
![my_caption \label{my_label}](source/figures/my_image.pdf){ width=50% }

For details on setting attributes like width and height, see:
http://pandoc.org/MANUAL.html#extension-link_attributes
--> 

![Impressionistic distribution of morphemes ($\mu$) across syllables ($\sigma$) in the two modalities \label{morph-syll}](source/figures/fig1_sequentialMorph.png){ width=100% }

(@em) Sequential morphology – horizontal stacking (\textsc{Turkish})

Bakan-ın&emsp;&emsp;&emsp;özel&emsp;istek-ler-i&emsp;yerine^getir-il-me-meli \
minister-GEN&emsp;private&emsp;request-PL-POSS&emsp;grant-PASS-NEG-DEON \
*The minister’s private requests should not be granted.*


Figure \ref{morph-syll}(a) draws an impressionistic illustration of how syllables and morphemes tend to interact in certain spoken languages. One morpheme or less is available per one spoken syllable. In other words, the overall morpheme-to-syllable ratio in spoken languages is likely to be less than 1. The Turkish sentence in (2) has 4 phonological words with morpheme-to-syllable ratios of 0.66, 0.5, 0.75, 0.44. The sentence has 10 morphemes expressed in 18 syllables. The sentence-wide morpheme-to-syllable ratio is 0.55. This pattern of morphological sequentiality of spoken languages is, of course, not without exception. We see varying degrees of limited simultaneity especially in tone languages, Semitic languages\footnote{Templatic morphologies allow for presets of vowel bundles to vertically come between and separate a two or three consonant-long abstract verbal root for derivational and inflectional purposes. For instance, the Arabic root *ktb* ‘read’ vertically merges with the templatic morpheme /CiCaC/ in a cogwheel manner and gives the noun *kitab* ‘book’ or merges with /Ca:CiC/ and gives *ka:tib* ‘clerk’. The same two templatic morphemes can merge with the root *htb* ‘address’ and give *hitab* ‘courtesy’ and *hatip* ‘preacher’ respectively. Notice that, while templatic morphology does work vertically, it operates over multiple syllables, which is different than the kind of simultaneity we find in sign languages.}, which have templatic morphologies, and also in small pockets of the morphologies of other spoken languages where contractions between two morphemes can occur\footnote{Such as the optional English /is/+/not/ > /isn’t/ or;
The mandatory Turkish [i]-deletion in /gir/ *‘enter’* + /di/ PST + /im/ 1PS > gir.dim *‘I entered’*}. However, the general trend points toward a sequential morphology for spoken languages\footnote{Other forms of simultaneity can be found in the oral modality. Speakers may choose to emphasize, for instance, that a movie was *'looong'* by lengthening a vowel. This has an iconic flavor and it does not necessarily add an extra morpheme to the utterance.} as depicted in Figure \ref{morph-syll}(a).



## Maths

Numbered equations are assisted by installing [pandoc-crossref](https://github.com/lierdakil/pandoc-crossref):

$$ \rho c \frac{\partial T}{\partial t} =  \frac{\partial q} {\partial x} $$ {#eq:yourlabel}

Now you can reference your equations (@eq:yourlabel) inline. If using pandoc-crossref, add the following to each relevant section of the makefile. 

```--filter pandoc-crossref``` 

Non numbered equations:
$$ \rho c \frac{\partial T}{\partial t} =  \frac{\partial q} {\partial x} $$

## The middle bit

This is the middle bit. Phasellus quis ex in ipsum pellentesque lobortis tincidunt sed massa. Nullam euismod sem quis dictum condimentum. Suspendisse risus metus, elementum eu congue quis, viverra ac metus. Donec non lectus at lectus euismod laoreet pharetra semper dui. Donec sed eleifend erat, vel ultrices nibh. Nam scelerisque turpis ac nunc mollis, et rutrum nisl luctus.

Cras eleifend velit diam, eu viverra mi volutpat ut. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec finibus leo nec dui imperdiet, tincidunt ornare orci venenatis. Maecenas placerat efficitur est, eu blandit magna hendrerit eu.

### Subsection of the middle bit

This is a subsection of the middle bit. Quisque sit amet tempus arcu, ac suscipit ante. Cras massa elit, pellentesque eget nisl ut, malesuada rutrum risus. Nunc in venenatis mi. Curabitur sit amet suscipit eros, non tincidunt nibh. Phasellus lorem lectus, iaculis non luctus eget, tempus non risus. Suspendisse ut felis mi.

## Summary of chapters

<!-- 
For italic, add one * on either side of the text
For bold, add two * on either side of the text
For bold and italic, add _** on either side of the text
-->

This is a brief outline of what went into each chapter. **Chapter 1** gives a background on duis tempus justo quis arcu consectetur sollicitudin.  **Chapter 2** discusses morbi sollicitudin gravida tellus in maximus.  **Chapter 3** discusses vestibulum eleifend turpis id turpis sollicitudin aliquet.  **Chapter 4** shows how phasellus gravida non ex id aliquet. Proin faucibus nibh sit amet augue blandit varius.


