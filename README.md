# Jeroen De Gussem, "Larger than Life? A Stylometric Analysis of the Multi-Authored *Vita* of Hildegard of Bingen," *Interfaces*, forthcoming.

This repository comprises the code, corpora and figures for the article "Larger than Life? A Stylometric Analysis of the Multi-Authored *Vita* of Hildegard of Bingen," forthcoming in *Interfaces*.

# Abstract

In recent decades, the surfacing evidence that the secretaries of the twelfth-century visionary Hildegard of Bingen (1098–1179) left their mark not only on the ultimate form of her texts but also on her image for posterity has increasingly been gaining traction. This article explores by aid of stylometric methods the collaborative authorship of the *Vita Hildegardis*, Hildegard’s (auto-?)biography that was posthumously appended to her *opera omnia* assembled in the Wiesbaden Riesencodex. The *Vita* was possibly designed to pursue her canonisation. Both Hildegard and her biographers gradually contributed to the text, first in the course of the last years of her life and later posthumously completed in the mid-1180s by end redactor Theoderic of Echternach. In between these *termini a quo* and *ante quem* the work was allegedly taken up but left unfinished by secretaries Godfrey of Disibodenberg and Guibert of Gembloux. In light of the fact that the *Vita* is an indispensable source in gaining historical knowledge on Hildegard’s life, the question has often been raised whether the *Life of Hildegard* is —by dint of contributions by multiple stakeholders— a larger-than-life depiction of the visionary’s life course. Specifically the ‘autobiographical’ passages included in the *Vita*, in which Hildegard is allegedly cited directly and is taken to recount biographical information in the first-person singular, have been approached with suspicion. 

The stylometric results in this article indicate, however, that there is no reason to presume on a statistical basis that Hildegard’s language was tampered with by her biographers in all too extensive a fashion, and that the autobiographical passages appear genuine. It may even be the case, as a stylistic analysis of two short letters appended to the *Vita*’s third and final book seems to suggest, that Hildegard either passively or actively contributed to parts of the *Vita* which are not traditionally ascribed to her. Since these letters recount Hildegard’s miraculous deeds and her veneration after death, this must remain a speculative case to show how thin the line is between what is to be considered ‘Hildegard’ and what is to be considered ‘Hildegardian.’ The article concludes with a number of reflections on Guibert of Gembloux’s potential influence in passages traditionally ascribed to Theoderic of Echternach.

# Corpus Details

Both the Python code and the texts discussed in this article are made available in open access here, with a limited number of exceptions when it comes to copright-protected textual data. The original texts found in the data folder of this online repository were camouflaged in order to respect copyright-protected texts. Only function words —which are highly successful for distinguishing writing styles— were retained in their original position and form. All the remaining, content-loaded tokens were substituted by asterisks, rendering the text illegible. This means that some experiments in the current article which relied on content words in addition to function words will not be replicable by relying solely on the text data as available on GitHub. To replicate these experiments as well, one may request access to the electronic versions of the editions referred to by contacting the publishers in charge.

Prior to analysis the Latin texts were transformed to adopt the same formatting norms so as to allow a reliable basis for comparison. Irrelevant material is removed and the divergent orthographical forms due to various manuscript witnesses or editorial practices are normalized, such as such as \<j\>’s to \<i\>’s, \<v\>’s to \<u\>’s, \<ae\>’s to \<e\>’s, etc. For the *Vita Hildegardis* specifically, it should be noted that the *Capitula* after each prologue were removed.

# Code and Visualizations

The code above is written in [Python 3](https://www.python.org/downloads/release/python-360/), and requires a number of packages collected under the [Anaconda](https://www.continuum.io/downloads) distribution. 

Clone this repository locally (i.e. download it in a convenient location). The texts under scrutiny are already in the data folder. In the terminal, change your current directory to the theoderic-of-fleury folder, and run the Python script simply by typing the following command:

```python code/main.py```

# Acknowledgements

This article is a revision of a chapter that was originally part of [my doctoral thesis](https://biblio.ugent.be/publication/8634997/file/8634998) (<- open access) titled “Collaborative Authorship in Twelfth-Century Latin Literature: A Stylometric Approach to Gender, Synergy and Authority” (defended at Ghent University in November 2019). The project was funded by the [Ghent University Special Research Fund](https://www.ugent.be/en/research/funding/bof) (BOF). Its execution rested on a close collaboration between the [Henri Pirenne Institute for Medieval Studies (HPIMS)](https://www.ugent.be/pirenne/en) at Ghent University, the [CLiPS Computational Linguistics Group](https://www.uantwerpen.be/en/research-groups/clips/) at the University of Antwerp, and the [Centre Traditio Litterarum Occidentalium](https://www.corpuschristianorum.org/) division for computer-assisted research into Latin language and literature housed in the Corpus Christianorum Library and Knowledge Centre of Brepols Publishers in Turnhout (Belgium). Firstly, I would like to thank the two anonymous peer reviewers for their invaluable feedback on this article. Secondly, my gratitude and indebtedness goes out to the guidance of prof. dr. Jeroen Deploige, prof. dr. Wim Verbaal and prof. dr. Mike Kestemont, the founders and intellectual inspirers of the aforementioned project which I had the honour of bringing to completion. Finally, I owe a great deal to the stimulating research presented at the conference [The Medieval Literary Canon in the Digital Age](https://www.mcda.ugent.be/) (17–18 September 2018), which has found its way —to my great delight, haplessly— to the pages of *Interfaces*.

# Further Reference

* Kestemont, Mike, Sara Moens, and Jeroen Deploige. ‘Collaborative Authorship in the Twelfth Century: A Stylometric Study of Hildegard of Bingen and Guibert of Gembloux'. *Digital Scholarship in the Humanities* 30, no. 2 (2013): 199–224.
* De Gussem, Jeroen. 'Bernard of Clairvaux and Nicholas of Montiéramey: Tracing the Secretarial Trail with Computational Stylistics'. *Speculum* 92, no. S1 (2017): S190–S225.
* Kestemont, Mike, and Jeroen De Gussem. 'Integrated Sequence Tagging for Medieval Latin Using Deep Representation Learning'. Edited by Marco Büchler and Laurence Mellerin. *Journal of Data Mining and Digital Humanities*, Special Issue on Computer-Aided Processing of Intertextuality in Ancient Languages, 2017, 1–17. [https://arxiv.org/abs/1603.01597](https://arxiv.org/abs/1603.01597).
* De Gussem, Jeroen, and Dinah Wouters. ‘Language and Thought in Hildegard of Bingen's Visionary Trilogy: Close and Distant Readings of a Thinker's Development'. *Parergon*, 2019, 31–60.