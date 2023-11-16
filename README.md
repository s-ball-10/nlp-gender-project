# nlp-gender-project
This repository contains the code and write-up for a student project conducted at the Universtiy of Oxford in spring 2022. 

It’s title is: \\
**Language differences and accommodation in Amazon book reviews --
An analysis of gendered online environments and their impact on linguistic
differences between the sexes**

## Abstract 

This work uses NLP methods to study linguistic differences and language accomodation between the sexes. While prior studies suggest distinct linguistic patterns between men and women, this research adopts a more nuanced perspective, acknowledging gender as a fluid construct influenced by various societal factors. Leveraging a corpus of 767,860 reviews from the Amazon book reviews dataset for the genres classics, romance, and science fiction, the results of the study indicate that men and women write differently about the same book genre. Furthermore, gendered book genres are associated with higher levels of language accommodation, which seems to be driven more by men than women. Employing ML techniques to analyse language differences is based on the idea that a classifier tends to reach higher performance levels the more distinguishable the language between men and women is. However, this methodology has the drawback that the results can be biased by architecture and hyperparameter choices and the quality of the data, which is why the findings of the study are preliminary. 

## Background
At the heart of many gender attribution attempts in machine learning is the assumption that gender is a fixed concept with two expressions: female and male (Nguyen et al., 2014). These gender attributions draw on studies suggesting that men and women use different language. Lakoff (1973) was among the first to observe that men and women differ in their general pattern of word usage. Statistical analyses seem to support this finding: Garimella & Mihalcea (2016), for instance, show that broad semantic classes related to sensorial concepts or family are specific to language used by women, whereas classes like sports or job are more related to men’s language. While gender attribution studies point to a static understanding of gender, disciplines like sociolinguistics and the social sciences rather consider gender to be "fluid". This means that gender identification and expression are influenced by a variety of variables including the societal context, the culture of a conversation partner, or social roles (Eckert, 2008, 2012). Acknowledging the complexity of gender identification and expression, this paper takes up Ngyuyen et al.’s (2014) call to analyse factors that potentially influence the degree to which a person uses gender-indexical language. Specifically, this paper aims to explore whether the context of gendered book genres influences language con- or divergence between male and female Amazon reviewers. The following three questions are guiding this study:

**RQ1**: Do men and women use different language when reviewing the same book genre?

**RQ2**: Does a potential difference in language depend on how "gender-stereotyped" a genre is? 

**RQ3**: Is linguistic adaption, if it exists, equally driven by both genders?

Please read the [analysis text file](text_nlp_gender.pdf) which includes the derivation of hypotheses, explanations for the methods, the results and limitations of this work, and the references.

The code is accessible [here](complete_code_nlp_gender.ipynb) or as a [google colab](https://drive.google.com/file/d/1MuZFWWQ-UEt5csh0KBXM18u94VuywYjl/view?usp=sharing)


### References mentioned in README.md

Eckert, P. (2008). Variation and the indexical field 1. Journal of sociolinguistics, 12(4), 453– 476.

Eckert, P. (2012). Three waves of variation study: The emergence of meaning in the study of sociolinguistic variation. Annual review of Anthropology, 41, 87–100.

Garimella, A., & Mihalcea, R. (2016). Zooming in on gender differences in social media. In
Proceedings of the Workshop on Computational Modeling of People’s Opinions, Personality, and Emotions in Social Media (PEOPLES), (pp. 1–10).

Lakoff, R. (1973). Language and woman’s place. Language in society, 2(1), 45–79.

Nguyen, D., Trieschnigg, D., Doğruöz, A. S., Gravel, R., Theune, M., Meder, T., & de Jong, F. (2014). Why gender and age prediction from tweets is hard: Lessons from a crowdsourcing experiment. In 25th International Conference on Computational Linguistics (COLING 2014), (pp. 1950–1961). Dublin City University and Association for Computational Linguistics.

