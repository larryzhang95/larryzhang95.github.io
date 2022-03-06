---
title: Predictive Modeling in Semantic Memory Search

summary: Semantic Memory Search describes the cognitive psychological process of exploring internal representations to retrieve semantic knowledge, facts, and experience from memory. I am developing predictive models of memory search via Optimal Foraging theory. This work contributes to both theoretical findings in understanding human semantic memory and clinical informatics approaches for understanding pathological alterations to memory, as the result of neuropsychiatric disorders

tags:
- Semantic Memory
- Cognitive Science
- Prediction
- Clinical Research
- Neuropsychiatry
- Natural Language Processing

date: "2022-03-06T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point:

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://https://sociophysio.org/current-projects/
# url_code: ""
# url_pdf: ""
# url_slides: ""
# url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:
---
Semantic Memory Search describes the cognitive psychological process of exploring internal representations to retrieve semantic knowledge, facts, and experience from memory. Memory retrieval as a computational problem strongly aligns itself with information retrieval areas including [search engines and digital media retrieval](https://proceedings.neurips.cc/paper/2012/file/14d9e8007c9b41f57891c48e07c23f57-Paper.pdf).Two primary theories currently dominate the research landscape on semantic memory search: Semantic Foraging and Random Walk models.

The Semantic Foraging model suggests semantic memory search is performed on a spatial representation of concepts, resembling optimal foraging behavior seen in animals searching for food. Optimal foraging theory is often dependent on the marginal value theorem, which describes an optimality model of when leaving a “patch of resources” in search of a new patch is most favorable. Under the scope of semantic foraging, the “patch of resources” corresponds to a spatial cluster of semantic concepts in memory. 

The Random Walk model suggests semantic memory search is performed on a network-wise representation of concepts, where nodes correspond to individual conceptual items, and edges encode semantic links between nodes. Edges can be either unweighted or weighted, and such weighting is often derived from observed experimental data directly via tasks such as the word associative task (e.g. : words associated with cue “hospital”).

Models of Semantic Memory Search are typically evaluated on the semantic fluency task, a common neuropsychological test performed in both clinical and experimental settings. The most common version of the semantic fluency task is: “Name as many animals as you can in XX minutes”. Early studies on semantic fluency suggested a two part retrieval process involving clustering and switching. This phenomena directly corresponds to the ideas proposed in optimal foraging theory, where the marginal value theorem demarcates an area of possible psychological process models by which clustering and switching is done (e.g. switching from patch to patch). However, proponents of the random walk model suggest the same mechanism can be explained naturally via random walks on semantic network representations. This is evidenced by the optimistic results of the random walk model in estimating the likelihood of semantic fluency list production in comparison to the semantic foraging model, and it’s ability to also explain clustering and switching, despite a simpler one-part process model. However, one of the criticisms of this model is that it is based on directly observed experimental data, rather than the more global spatial model of Semantic Foraging, biasing the performance of the model. Such a result is resemblant of the “data leakage” problem seen in machine learning and data science.

My research in this area, with Prof. Michael N Jones at IU, focuses on the Semantic Foraging model. Currently, the Semantic Foraging model utilizes a similarity drop model for characterizing cluster and switching behavior. This corresponds to a retroactive model, which determines clustering via the detection of similarity drop between the pairwise similarity of the previous fluency list item and current item, and pairwise similarity of the current item and the next. We are proposing alternative process model(s) that are predictive in nature, which do not depend on the fluency list itself, that explain clustering and switching behavior. We aim to demonstrate that such predictive models, generally based on research such as Shephard’s Law of Universality, can better characterize cluster and switching behavior than the random walk model, all things made equal (e.g. analogous network and spatial representations and parameter dependencies). 

Once the supremacy of the predictive model in comparison to the random walk model, we seek to show that when embedded within the semantic foraging model, the combined model can better explain fluency data than the random walk model on general and clinical populations. The proposed predictive model of clustering and switching may also be independently valuable for evaluating clinical issues such as cognitive decline. 

In conjunction with the wider IU Computational Cognition Lab led by Prof. Michael N Jones, we are also planning to open source all our proposed models and methods for researchers to utilize. In doing so, we seek to accelerate research on semantic memory search, especially in non-normative populations. We hope this allows us to better understand and assess the capacity of these leading models of semantic memory search.
