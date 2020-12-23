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

All data credits belong to the wonderful work done by **Rekhta foundation**.
Link: https://www.rekhta.org/

Data has been parsed into Urdu, Hindi and English translieration thanks to their excellent webpage.
Consider supporting them for their great work in pushing the urdu language.


Credits to these authors for their wonderful original creations:

*'mirza-ghalib','allama-iqbal','faiz-ahmad-faiz','sahir-ludhianvi','meer-taqi-meer',
'dagh-dehlvi','kaifi-azmi','gulzar','bahadur-shah-zafar','parveen-shakir',
'jaan-nisar-akhtar','javed-akhtar','jigar-moradabadi','jaun-eliya',
 'ahmad-faraz','meer-anees','mohsin-naqvi','firaq-gorakhpuri','fahmida-riaz','wali-mohammad-wali',
 'waseem-barelvi','akbar-allahabadi','altaf-hussain-hali','ameer-khusrau','naji-shakir','naseer-turabi',
 'nazm-tabatabai','nida-fazli','noon-meem-rashid', 'habib-jalib'*


If you would want to extend the size of this dataset, do a fork of this repository. 
There is scope of improvement because currently this simple parsing only looks at a hand curated list of authors.
There can be better ways of automating the task.
