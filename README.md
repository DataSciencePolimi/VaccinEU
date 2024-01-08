# VaccinEU

We curated a list of vaccine-related keywords as complete as possible with the help of native speakers, using a snowball sampling approach, and collected over 70 million tweets in three different languages, from November 1st 2020 to November 15th 2021, using a combination of streaming and historical search Twitter APIs. 

We provide public access to this data in agreement with Twitter terms of service by releasing ids of tweets which can be used to retrieve full objects via APIs. These can be "hydrated" using [Hydrator](https://github.com/DocNow/hydrator).

For each language, we further collected a list of hashtags which strongly state a stance in favor or against vaccination, and we manually annotated a random sample of 1,000 tweets with four labels (Pro, Anti, Neutral, Out-of-context). We provide full access to this metadata, which can be used to better understand the polarized debate around vaccinations and train machine learning classifiers to automatically detect anti-vaccination messages.

More details in our [paper]([http://arxiv.org/abs/2201.06293](https://ojs.aaai.org/index.php/ICWSM/article/view/19374)).

If you use this data please cite the following paper: <br>
<b> Di Giovanni M, Pierri F, Torres-Lugo C, Brambilla M. VaccinEU: COVID-19 vaccine conversations on Twitter in French, German and Italian. InProceedings of the International AAAI Conference on Web and Social Media 2022 May 31 (Vol. 16, pp. 1236-1244). https://ojs.aaai.org/index.php/ICWSM/article/view/19374
</b>
 <br>

# Team
Francesco Pierri, Marco Di Giovanni, Marco Brambilla <br>
Dipartimento di Elettronica, Informatica e Bioingegneria, Politecnico di Milano, Milano, Italy

For any inquiries please contact: francesco.pierri at polimi.it

# Acknowledgments
This work is partially supported by the EU H2020 research and innovation programme, COVID-19 call, under grant agreement No. 101016233 “PERISCOPE” (https://periscopeproject.eu/), and by the PRIN grant HOPE (FP6, Italian Ministry of Education).
