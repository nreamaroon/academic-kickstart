---
title: "Signal quality measure for pulsatile physiological signals using morphological features: Applications in reliability measure for pulse oximetry"
date: 2019-01-01
publishDate: 2020-07-13T03:35:36.551520Z
authors: ["Elyas Sabeti", "Narathip Reamaroon", "Michael Mathis", "Jonathan Gryak", "Michael W. Sjoding", "Kayvan Najarian"]
publication_types: ["2"]
abstract: "Pulse oximetry is a noninvasive and low-cost physiological monitor that measures blood oxygen levels. While the noninvasive nature of pulse oximetry is advantageous, the estimates of oxygen saturation generated by these devices are prone to motion artifacts and ambient noise, reducing the reliability of such estimations. Clinicians combat this by assessing the quality of oxygen saturation estimation by visual inspection of the photo­ plethysmograph (PPG), which represents changes in pulsatile blood volume and is also generated by the pulse oximeter. In this paper, we propose six morphological features that can be used to determine the quality of the PPG signal and generate a signal quality index. Unlike many similar studies, this approach uses machine learning and does not require a separate signal, such as ECG, for reference. Multiple algorithms were tested against 46 30min PPG segments of patients with cardiovascular and respiratory conditions, including atrial fibrillation, hypoxia, acute heart failure, pneumonia, ARDS, and pulmonary embolism. These signals were independently annotated for signal quality by two clinicians, with the union of their annotations used as the ground-truth. Similar to any physiological signal recorded in a clinical setting, the utilized dataset is also unbalanced in favor of good quality segments. The experiments showed that a cost-sensitive Support Vector Machine (SVM) outperformed other tested methods and was robust to the unbalanced nature of the data. Though the proposed algorithm was tested on PPG signals, the methodology remains agnostic to the dataset used, and may be applied to any type of pulsatile physiological signal."
featured: false
publication: "*Informatics in Medicine Unlocked*"
summary: "*Informatics in Medicine Unlocked*"
url_pdf: "https://linkinghub.elsevier.com/retrieve/pii/S2352914819301856"
doi: "10.1016/j.imu.2019.100222"
url_code: "https://github.com/kayvanlabs/ARDS/tree/master/Waveforms"
tags: ["Publication"]
---

