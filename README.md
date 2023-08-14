**Dataset** is arranged as authors-> [en , ur, hi] -> ghazals/poems

[en, ur , hi] signify english translieration and urdu , hindi text

**Why is this interesting ?**
Urdu is a low resource language in NLP. Compared to English, which could have hundreds of thousands of articles floating around on the internet,
there is not much content for Urdu, to train ML language models .

*Ghazal* is a form of poetry popular in South Asia. 

*In terms of NLP*, it provides interesting possiblities for future testing of language models.

Source: https://en.wikipedia.org/wiki/Ghazal

- The ghazal is a short poem consisting of rhyming couplets, called Sher or Bayt. 
- Most ghazals have between seven and twelve shers. For a poem to be considered a true ghazal, it must have no fewer than five couplets. 
- Almost all ghazals confine themselves to less than fifteen couplets (poems that exceed this length are more accurately considered as qasidas). Ghazal couplets end with the same rhyming pattern and are expected to have the same meter. 
- The ghazal's uniqueness arises from its rhyme and refrain rules, referred to as the 'qaafiyaa' and 'radif' respectively. 
- Each sher is self-contained and independent from the others, containing the complete expression of an idea.



I want to highlight an important point at this momement.
22Mb of text data is nothing compared to what transformer based models actually need. 

[common crawl dataset](https://commoncrawl.org/) is a giant repository of free text data in more than 40 languages.
If you actually want to train a transformer model from scratch, you would need data in order of millions of text files. And for that it would be best to start with one of these big data tools.

===============================================

All data credits belong to the wonderful work done by **Rekhta foundation**.
Link: https://www.rekhta.org/

Data has been parsed into Urdu, Hindi and English translieration thanks to their excellent webpage.
Consider supporting them for their great work in pushing the urdu language.


Credits to authors for their wonderful original creations


===============================================

If you would want to extend the size of this dataset, do a fork of this repository. 

