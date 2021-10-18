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

# Identification of Misinformation
## [@Wu_2019_MisinformationInSocialMedia]

In their work, @Wu_2019_MisinformationInSocialMedia examine misinformation in social media and discuss the potential for detecting it with machine learning algorithms. The issue they feel is most important is that the definition of misinformation varies wildly across current literature. It always describes the information that is fake or inaccurate, but this definition is far too broad to be studied extensively. As such, they define eleven categories and subcategories of misinformation that can each be studied individually. Some important variables are brought up continuously, most frequently the intention of deceit and the verification of information.

After defining categories of misinformation, the researchers determine that they intend to focus on false information which is intentionally and maliciously spread in social networks. The two main types of attacks in social media are **manipulation of networks**, in which fake accounts will attach themselves to preexisting social networks or form their own, and **manipulation of content**, in which they copy large portions of information from real accounts and then introduce illegitimate information. They go on to discuss each of these types of attacks in detail and describe ways in which spam accounts can be automatically detected. Four methods of detection are proposed; an illegitimate post can be identified based on the contents of the post, the context in which it was posted, the patterns with which the post propagated throughout the platform, or before it becomes viral using a combination of these techniques. Misinformation in social media posts is often contextualized with very little supporting data or labels.

## [@Kata_2021_PostmodernAntiVax]

# Establishment of Consensus
## [@Plaza_2019_ConsensusAlgorithmsMedicalMisinformation]

@Plaza_2019_ConsensusAlgorithmsMedicalMisinformation performed a set of case studies to identify the origins of medical misinformation. In doing so, they discovered that many movements encouraging a deviation from scientific consensus begin with either a misunderstanding of scientific literature or with the publication of a paper that is not properly peer-reviewed. For example, a 2017 study concluded that its research methods were not rigorous enough to determine whether or not the presence of fluoride in tap water caused toxicity. Less than a year later, a cascade of sources citing this study claimed that fluoride was a neurotoxic chemical that had no place in the water supply. Twenty years earlier, in 1998, _The Lancet_ published a paper by Andrew Wakefield which found that specific vaccines caused autism in children. After this paper's publication, many independent scientists discovered critical errors in Wakefield's research methods and determined that the findings were not accurate. However, before _The Lancet_ retracted the paper, its findings had been viewed and accepted by a significant portion of the public. As a result, a large movement claiming that autism was caused by vaccinations had formed. The authors of this study concluded that one way to prevent situations like this from happening again is by establishing a metric of scientific consensus that could be assigned to each claim for the public to refer to.

An ideal metric to determine scientific consensus, according to @Plaza_2019_ConsensusAlgorithmsMedicalMisinformation, would allow for each claim to undergo review and scrutiny from a large set of unbiased experts. To solve this problem, they recommend the development of a distributed mechanism for the determination of medical scientific consensus. One mechanism that may be used to consistently verify consensus is the implementation of blockchain technology (BCT). According to the authors, BCT would prevent this verification from being oppressive in terms of scientific freedom while it reduced the likelihood of invalid claims making their way outside of the community. If implemented correctly, BCT would associate each claim with a set of reviews which ultimately provided a numerical "validity score" displayed as a percentage. In simple terms, if a claim is said to have a validity of over 50% then it can be said that it has scientific consensus. A higher validity score represents a claim that is more likely to be referred to as scientific fact, but it is impossible for a claim to ever reach this point through this system.

No matter how close a claim is to achieving complete scientific consensus, it is important to refrain from considering it as fact. Paradigm shifts happen in science, and ideas that were heavily regarded as the truth are now known to be false. One example in which scientific consensus was incorrect in the field of medical information was the 1955 understanding of peptic ulcers. When researchers published a paper claiming that an infection called _Helicobacter pylori_ was the root cause of peptic ulcers, they were met with scrutiny and denial from the vast majority of the scientific community. However, after 30 years of consistent research in the field that showed the validity of the claim, scientific consensus slowly shifted in favor of the researchers. Because these claims circulated for multiple decades before scientific consensus was updated, it can be argued that many lives were lost unnecessarily. @Plaza_2019_ConsensusAlgorithmsMedicalMisinformation assert that BCT would prevent situations like this from taking as long as they did in the twentieth century by increasing the efficiency with which scientific consensus is updated.

## [@Resnick_2021_InformedCrowdsIdentifyMisinformation]

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