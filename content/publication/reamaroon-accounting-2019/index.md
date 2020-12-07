---
title: "Accounting for Label Uncertainty in Machine Learning for Detection of Acute Respiratory Distress Syndrome"
date: 2019-01-01
publishDate: 2020-07-13T03:35:36.550248Z
authors: ["Narathip Reamaroon", "Michael W. Sjoding", "Kaiwen Lin", "Theodore J. Iwashyna", "Kayvan Najarian"]
publication_types: ["2"]
abstract: "When training a machine learning algorithm for a supervised-learning task in some clinical applications, uncertainty in the correct labels of some patients may adversely affect the performance of the algorithm. For example, even clinical experts may have less conﬁdence when assigning a medical diagnosis to some patients because of ambiguity in the patient’s case or imperfect reliability of the diagnostic criteria. As a result, some cases used in algorithm training may be mislabeled, adversely affecting the algorithm’s performance. However, experts may also be able to quantify their diagnostic uncertainty in these cases. We present a robust method implemented with support vector machines (SVM) to account for such clinical diagnostic uncertainty when training an algorithm to detect patients who develop the acute respiratory distress syndrome (ARDS). ARDS is a syndrome of the critically ill that is diagnosed using clinical criteria known to be imperfect. We represent uncertainty in the diagnosis of ARDS as a graded weight of conﬁdence associated with each training label. We also performed a novel time-series sampling method to address the problem of intercorrelation among the longitudinal clinical data from each patient used in model training to limit overﬁtting. Preliminary results show that we can achieve meaningful improvement in the performance of algorithm to detect patients with ARDS on a hold-out sample, when we compare our method that accounts for the uncertainty of training labels with a conventional SVM algorithm."
featured: false
summary: "*IEEE Journal of Biomedical and Health Informatics*"
publication: "*IEEE Journal of Biomedical and Health Informatics*"
url_pdf: "https://ieeexplore.ieee.org/document/8304750/"
doi: "10.1109/JBHI.2018.2810820"
url_code: "https://github.com/kayvanlabs/ARDS/tree/master/Label%20Uncertainty"
url_project: 'https://nickreamaroon.com/project/uncertainty/'
tags: ["Publication"]
---

