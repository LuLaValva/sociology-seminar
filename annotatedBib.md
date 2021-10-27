---
title: Algorithmic Spread of Misinformation
subtitle: Annotated Bibliography
author: Lucas LaValva
date: November 30, 2021
output: pdf_document
geometry: "margin=1in"
header-includes:
    - \usepackage{setspace}
    - \doublespacing
    - \usepackage{hanging}
bibliography: [references.bib]
---

# Machine Learning Biases

## [@Gianfrancesco_2018_PotentialBiasesInMLHealth]

As machine learning and computational intelligence have been integrated more into fields that had previously relied on human intelligence, it has become increasingly apparent that reliance on computer models without understanding often results in negative effects. @Gianfrancesco_2018_PotentialBiasesInMLHealth discuss the potential ramifications of this knowledge gap in the field of healthcare. One important consideration is that the term "machine learning" refers to a large body of algorithms that have a variety of strengths and weaknesses. For example, methods such as decision tree and market basket analysis provide associations between variables and significant correlations. Even though the statistical analysis is abstracted away from the people who use these methods, it is left to professionals to interpret the useful output and that which is obvious or not important. Because of the way these models are constructed they are unable to differentiate between correlation and causation, so it is up to the user to differentiate. On the other hand, many of the most sophisticated machine learning models like deep learning act as black boxes that simply take in a body of information and respond with a conclusion. Currently, these models are used in healthcare to predict in-hospital mortality and expected length of stay. There are other instances in which machine learning is used to identify anomalies in medical scans.

Most use cases for machine learning have benefited the healthcare system without significant negative effects, but @Gianfrancesco_2018_PotentialBiasesInMLHealth have highlighted the inequalities and biases that may arise if the algorithms are not properly understood. There is an argument to be made that excessive use of machine learning is likely to perpetuate or worsen existing inequalities. One reason for this is because larger amounts of data are usually correlated with higher accuracy in algorithms. It is known that hospitals have significantly larger volumes of information for people who have a higher social status, and fewer for marginalized groups. Most machine learning algorithms are excellent at identifying meaningful information without context but are unable to distinguish data that matters within the context of the field for which they are applied. For example, one algorithm found that the highest predictor of death during a hospital stay is the number of visits from friends and family; any hospital worker knows that this is simply a correlation and death is not caused by hospital visits.

The solution that is provided by @Gianfrancesco_2018_PotentialBiasesInMLHealth is excessive documentation for each type of machine learning algorithm that is designed to be read by laypeople. Without an understanding of how these algorithms work, people who are using a machine learning-based system are at risk of feeding the algorithms with biased data or of misinterpreting the results that they are given. It is also recommended that hospitals only apply machine learning to places where it is demonstrated that results will be clinically important. Overreliance on algorithms in areas where they do not provide meaningful results may degrade those areas of the health field, and this should not happen in excessive amounts.

# Identification of Misinformation
## [@Wu_2019_MisinformationInSocialMedia]

A study by @Wu_2019_MisinformationInSocialMedia examines misinformation in social media and discusses the potential for detecting it with machine learning algorithms. The issue they feel is most important is that the definition of misinformation varies wildly across current literature. It always describes the information that is fake or inaccurate, but this definition is far too broad to be studied extensively. As such, they define eleven categories and subcategories of misinformation that can each be studied individually. Some important variables are brought up continuously, most frequently the intention of deceit and the verification of information.

After defining categories of misinformation, the researchers determine that they intend to focus on false information which is intentionally and maliciously spread in social networks. The two main types of attacks in social media are **manipulation of networks**, in which fake accounts will attach themselves to preexisting social networks or form their own, and **manipulation of content**, in which they copy large portions of information from real accounts and then introduce illegitimate information. They go on to discuss each of these types of attacks in detail and describe ways in which spam accounts can be automatically detected. Four methods of detection are proposed; an illegitimate post can be identified based on the contents of the post, the context in which it was posted, the patterns with which the post propagated throughout the platform, or before it becomes viral using a combination of these techniques. Misinformation in social media posts is often contextualized with very little supporting data or labels.

## [@Kata_2021_PostmodernAntiVax]

# Establishment of Consensus
## [@Plaza_2019_ConsensusAlgorithmsMedicalMisinformation]

@Plaza_2019_ConsensusAlgorithmsMedicalMisinformation performed a set of case studies to identify the origins of medical misinformation. In doing so, they discovered that many movements encouraging a deviation from scientific consensus begin with either a misunderstanding of scientific literature or with the publication of a paper that is not properly peer-reviewed. For example, a 2017 study concluded that its research methods were not rigorous enough to determine whether or not the presence of fluoride in tap water caused toxicity. Less than a year later, a cascade of sources citing this study claimed that fluoride was a neurotoxic chemical that had no place in the water supply. Twenty years earlier, in 1998, _The Lancet_ published a paper by Andrew Wakefield which found that specific vaccines caused autism in children. After this paper's publication, many independent scientists discovered critical errors in Wakefield's research methods and determined that the findings were not accurate. However, before _The Lancet_ retracted the paper, its findings had been viewed and accepted by a significant portion of the public. As a result, a large movement claiming that autism was caused by vaccinations had formed. The authors of this study concluded that one way to prevent situations like this from happening again is by establishing a metric of scientific consensus that could be assigned to each claim for the public to refer to.

An ideal metric to determine scientific consensus, according to @Plaza_2019_ConsensusAlgorithmsMedicalMisinformation, would allow for each claim to undergo review and scrutiny from a large set of unbiased experts. To solve this problem, they recommend the development of a distributed mechanism for the determination of medical scientific consensus. One mechanism that may be used to consistently verify consensus is the implementation of blockchain technology (BCT). According to the authors, BCT would prevent this verification from being oppressive in terms of scientific freedom while it reduced the likelihood of invalid claims making their way outside of the community. If implemented correctly, BCT would associate each claim with a set of reviews which ultimately provided a numerical "validity score" displayed as a percentage. In simple terms, if a claim is said to have a validity of over 50% then it can be said that it has scientific consensus. A higher validity score represents a claim that is more likely to be referred to as scientific fact, but it is impossible for a claim to ever reach this point through this system.

No matter how close a claim is to achieving complete scientific consensus, it is important to refrain from considering it as fact. Paradigm shifts happen in science, and ideas that were heavily regarded as the truth are now known to be false. One example in which scientific consensus was incorrect in the field of medical information was the 1955 understanding of peptic ulcers. When researchers published a paper claiming that an infection called _Helicobacter pylori_ was the root cause of peptic ulcers, they were met with scrutiny and denial from the vast majority of the scientific community. However, after 30 years of consistent research in the field that showed the validity of the claim, scientific consensus slowly shifted in favor of the researchers. Because these claims circulated for multiple decades before scientific consensus was updated, it can be argued that many lives were lost unnecessarily. @Plaza_2019_ConsensusAlgorithmsMedicalMisinformation assert that BCT would prevent situations like this from taking as long as they did in the twentieth century by increasing the efficiency with which scientific consensus is updated.

## [@Resnick_2021_InformedCrowdsIdentifyMisinformation]

Before organizing their study, @Resnick_2021_InformedCrowdsIdentifyMisinformation optimistically argued that, while individuals are not always reliable at identifying misinformation, it may be possible for groups of people to collectively and democratically determine whether an article or news source is misleading. Past research has shown that political biases do not significantly affect the average rater's ability to distinguish sources of mainstream news from those of hyperpartisan and fake news, but until this study, there was no similar analysis for individual articles. Thus, a study was organized in which the objective was to determine the correlation between the identification of misinformation by liberal voters, conservative voters, and journalists who have been trained in objectivity.

To perform this experiment, @Resnick_2021_InformedCrowdsIdentifyMisinformation began by hiring a group of untrained and ideologically balanced lay raters via Amazon's Mechanical Turk and 4 professional journalists who had completed certifications via a fellowship for mid-career journalists. The lay raters were each separated into one of nine groups; first, an initial screening identified each as either liberal, conservative, or moderate. Then each ideological group was given a set of articles and a condition under which to rate them based on believability. Based on these conditions, raters either judged articles after no additional research, after research that was self-guided or after that which was based on a given set of other ideologically balanced articles. Because the researchers were not qualified to label articles based on believability, they performed an analysis based on the correlation between the labels given by lay raters and those given by journalists.

Many of the results found by this study were aligned with those of previous research. Regardless of the amount of research, it was found that liberal and conservative voters were highly correlated in decisions about believability. However, conservative voters were less likely on average to agree with the decisions made by journalists. One statistical analysis found that 3.54 self-researching liberal voters were equivalent to a single journalist, while the equivalent number of conservative voters was 5.45. The limitations of the experiment did not allow for an "equivalency rating" with journalists that was higher than 18, and the conservative crowd exceeded this limit far more often than liberal voters did. Regardless of political affiliation, it was found that lay raters who did research themselves were more likely to agree with journalists than those who were given a politically balanced set of articles to read beforehand. The most evident result found by @Resnick_2021_InformedCrowdsIdentifyMisinformation was that raters who have performed research on the subject before rating the believability of an article are far less likely to disagree with journalists and more likely to agree with the opposing political affiliation.

## [@Roitero_2020_CrowdIdentifyMisinformationObjectively]

## [@Pennycook_2021_CrowdsourcedJudgements]

# Detecting Misinformation with Machine Learning

## [@Yu_2017_convolutionalMisinformationIdentification]

## [@Du_2021_DetectVaccineMisinfoWithML]

# Attention vs. Accuracy

## [@Pennycook_2021_AttentionToAccuracy]




# References

```{=latex}
\begin{hangparas}{2em}{1}
```

<div id="refs"></div>

```{=latex}
\end{hangparas}
```