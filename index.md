---
layout: default
---

# Call for papers

## Scope of the workshop

Machine learning models for personalized medicine aim at tailoring diagnostic and therapeutic strategies to individual patient characteristics,
which often means that these models have to be trained on data that is not only high-dimensional but also sparse and heterogeneous.
Typical approaches assume the availability of a joint dataset of multiple patients for training a global model, from which patient-specific variants can be built.
In practice, difficulties associated to data collection and governance arise when compiling comprehensive datasets needed for training robust machine learning models.
Moreover, working on historical data is complicated by the fact that this data often exhibits a domain shift in the data distribution, resulting from
the use of different machinery and diagnostic techniques over time.

At the same time, the paradigms of incremental and continual learning in machine learning have garnered significant
attention as a means to develop models that can adapt to new information over time without forgetting previously learned knowledge. 
This capability would perfectly suit the requirements of personalized medicine, assuming a scenario where machine learning models
for healthcare could be trained incrementally on data from few or even a single patient at a time.
Such an approach would not only respect the privacy and data ownership of individuals but would also allow for the continual updating of models for previous
patients as new data becomes available.

The workshop on Personalized Incremental Learning in Medicine (PILM) aims to bridge the gap between
incremental learning research and its application to personalized medicine. The objectives of this workshop are multi-fold:
- To highlight the latest advancements in incremental learning that can be applied to develop personalized medical models.
- To foster discussions on the unique challenges that arise when applying incremental learning to patient-specific data with limited samples.
- To encourage the development of novel methodologies that can incorporate new patient data into existing models without compromising the performance on previous patients' data.
- To explore strategies for overcoming domain shifts within intra-patient data and ensuring robustness across diverse medical equipment.
- To promote the sharing of insights and techniques that can address the issues of data privacy and the inaccessibility of old patient data in the context of continual learning.
- To stimulate collaboration between researchers in machine learning, medical imaging, and clinical practice to develop practical, scalable, and patient-centric solutions.

## Topics

The workshop aims to attract novel and original contributions at the intersection between incremental learning and personalized medicine.
Expected submissions should cover, but are not limited to, the following topics:
- Novel algorithms for incremental and continual learning that are suitable for medical applications.
- Methods to prevent catastrophic forgetting in the context of patient-specific machine learning models.
- Strategies for one-shot or few-shot learning in medical diagnosis and treatment personalization.
- Techniques for handling domain shifts within a patient's data over time or across different medical devices.
- Approaches to integrate incremental learning with transfer learning in medicine.
- Evaluation metrics and methodologies for assessing the performance of incremental learning systems in personalized medicine.
- Ethical considerations and data privacy solutions in the development of incremental learning models for healthcare.
- Case studies and practical applications of incremental learning in medical imaging, patient monitoring, and other areas of personalized medicine.
- Discussions on the limitations of current datasets and proposals for new data collection efforts that support incremental learning research in medicine.
- Interdisciplinary research that combines insights from clinical practice, medical imaging, and machine learning to advance personalized medicine.

<!--## Workshop Proceedings

Workshop proceedings will be published in high-quality venues, indexed by both Scopus and Web of Science.
Final details are being confirmed; further information will be provided as soon as it is available.-->
