# Airbnb Host Profiles

Distributed together with: Self-Disclosure and Perceived Trustworthiness of Airbnb Host Profiles (full citation below).

Licensed under [Creative Commons Attribution Share Alike 4.0](http://choosealicense.com/licenses/cc-by-sa-4.0/).

## Description

We provide annotations of the topics and perceived trustworthiness of ~1,200 Airbnb host profiles, along with results from an experiment we ran in order to understand how perceived trustworthiness affects preferences. The details how we derived this dataset are described in the paper.

## Files

* ``air-hp-sentences.csv``: Annotation of the topics of profiles on the sentence level, 1 denotes the existence of such topic while 0 means the topic was not tagged as mentioned.

* ``air-hp-profile.csv``: Aggregation of the sentence level annotation results on profile level, with columns indicating the number of sentences tagged as mentioning a specific topic. Other host attributes are also included in this file.

* ``air-hp-trustworthiness.csv``: The mean of perceived trustworthiness score of each profile, annotated by five workers.

* ``air-hp-experiment.csv``: The experiment result along with the demographic information of the judges.

## BibTex Entry
@inproceedings{ma2017airbnb, <br>
&nbsp;&nbsp;&nbsp;&nbsp; author={Ma, Xiao and Hancock, Jeffery T and Lim Mingjie, Kenneth and Naaman, Mor}, <br>
&nbsp;&nbsp;&nbsp;&nbsp; title={Self-Disclosure and Perceived Trustworthiness of Airbnb Host Profiles}, <br>
&nbsp;&nbsp;&nbsp;&nbsp; booktitle={Proceedings of the 20th ACM Conference on Computer-Supported Cooperative Work and Social Computing}, <br>
&nbsp;&nbsp;&nbsp;&nbsp; series={CSCW '17}, <br>
&nbsp;&nbsp;&nbsp;&nbsp; year={2017} <br>
}
