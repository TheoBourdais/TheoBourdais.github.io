---
title: "Development and Assessment of an Artificial Intelligence-Based Tool for Ptosis Measurement in Adult Myasthenia Gravis Patients Using Selfie Video Clips Recorded on Smartphones"
collection: publications
permalink: /publication/docai_paper
excerpt: 'My first paper ! This paper describes the work we did at Doc.ai for ShareCare on Myasthenia gravis (MG) with UCB. We devellopped a Deep Learning model based on ResNet50 to predict a key symptom of MG via selfie. This would allow clinical trials to accept more patients as part of a study in order to scale it, as well as follow almost in real time the evolution of a patients symptoms using an app on their phone.'
date: 2023-05-16
venue: 'Digital Biomarkers'
paperurl: 'https://karger.com/dib/article/doi/10.1159/000531224/854396/Development-and-Assessment-of-an-Artificial?searchresult=1'
#citation: 'Meelis Lootus, Lulu Beatson, Lucas Atwood, Theo Bourdais, Sandra Steyaert, Chethan Sarabu, Zeenia Framroze, Harriet Dickinson, Jean-Christophe Steels, Emily Lewis, Nirav R Shah, Francesca Rinaldo; Development and Assessment of an Artificial Intelligence-Based Tool for Ptosis Measurement in Adult Myasthenia Gravis Patients Using Selfie Video Clips Recorded on Smartphones. Digit Biomark 2023; https://doi.org/10.1159/000531224'
---

## Context

My first paper ! This paper describes the work we did at Doc.ai for ShareCare on Myasthenia gravis (MG) with UCB. We devellopped a Deep Learning model based on ResNet50 to predict a key symptom of MG via selfie. This would allow clinical trials to accept more patients as part of a study in order to scale it, as well as follow almost in real time the evolution of a patients symptoms using an app on their phone.

[Download paper here](/files/000531224.pdf)


## Abstract

Myasthenia gravis (MG) is a rare autoimmune disease characterized by muscle weakness and fatigue. Ptosis (eyelid drooping) occurs due to fatigue of the muscles for eyelid elevation and is one symptom widely used by patients and healthcare providers to track progression of the disease. Margin reflex distance 1 (MRD1) is an accepted clinical measure of ptosis and is typically assessed using a hand-held ruler. In this work, we develop an AI model that enables automated measurement of MRD1 in self-recorded video clips collected using patient smartphones. Methods: A 3-month prospective observational study collected a dataset of video clips from patients with MG. Study participants were asked to perform an eyelid fatigability exercise to elicit ptosis while filming “selfie” videos on their smartphones. These images were collected in nonclinical settings, with no in-person training. The dataset was annotated by non-clinicians for (1) eye landmarks to establish ground truth MRD1 and (2) the quality of the video frames. The ground truth MRD1 (in millimeters, mm) was calculated from eye landmark annotations in the video frames using a standard conversion factor, the horizontal visible iris diameter of the human eye. To develop the model, we trained a neural network for eye landmark detection consisting of a ResNet50 backbone plus two dense layers of 78 dimensions on publicly available datasets. Only the ResNet50 backbone was used, discarding the last two layers. The embeddings from the ResNet50 were used as features for a support vector regressor (SVR) using a linear kernel, for regression to MRD1, in mm. The SVR was trained on data collected remotely from MG patients in the prospective study, split into training and development folds. The model’s performance for MRD1 estimation was evaluated on a separate test fold from the study dataset. Results: On the full test fold (N = 664 images), the correlation between the ground truth and predicted MRD1 values was strong (r = 0.732). The mean absolute error was 0.822 mm; the mean of differences was −0.256 mm; and 95% limits of agreement (LOA) were −0.214–1.768 mm. Model performance showed no improvement when test data were gated to exclude “poor” quality images. Conclusions: On data generated under highly challenging real-world conditions from a variety of different smartphone devices, the model predicts MRD1 with a strong correlation (r = 0.732) between ground truth and predicted MRD1.

