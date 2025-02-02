---
title: "SpeCollate: Deep cross-modal similarity network for mass spectrometry data based peptide deductions"
order: 99
collection: publications
permalink: /publication/paper99
excerpt: 'SpeCollate is the first of its kind deep learning based peptide database search engine. By embedding both the query spectra and the database peptides using a dual encoder network, SpeCollate can efficiently rank high quality peptides for each query spectrum providing up to 95% search accuracy.'
date: 2021-10-29
venue: 'PloS one'
paperurl: 'https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0259349'
citation: 'Tariq, M. U., & Saeed, F. (2021). &quot;SpeCollate: Deep cross-modal similarity network for mass spectrometry data based peptide deductions.&quot; <i>PloS one</i>. 16(10), e0259349.'
---
Historically, the database search algorithms have been the de facto standard for inferring peptides from mass spectrometry (MS) data. Database search algorithms deduce peptides by transforming theoretical peptides into theoretical spectra and matching them to the experimental spectra. Heuristic similarity-scoring functions are used to match an experimental spectrum to a theoretical spectrum. However, the heuristic nature of the scoring functions and the simple transformation of the peptides into theoretical spectra, along with noisy mass spectra for the less abundant peptides, can introduce a cascade of inaccuracies. In this paper, we design and implement a Deep Cross-Modal Similarity Network called SpeCollate, which overcomes these inaccuracies by learning the similarity function between experimental spectra and peptides directly from the labeled MS data. SpeCollate transforms spectra and peptides into a shared Euclidean subspace by learning fixed size embeddings for both. Our proposed deep-learning network trains on sextuplets of positive and negative examples coupled with our custom-designed SNAP-loss function. Online hardest negative mining is used to select the appropriate negative examples for optimal training performance. We use 4.8 million sextuplets obtained from the NIST and MassIVE peptide libraries to train the network and demonstrate that for closed search, SpeCollate is able to perform better than Crux and MSFragger in terms of the number of peptide-spectrum matches (PSMs) and unique peptides identified under 1% FDR for real-world data. SpeCollate also identifies a large number of peptides not reported by either Crux or MSFragger. To the best of our knowledge, our proposed SpeCollate is the first deep-learning network that can determine the cross-modal similarity between peptides and mass-spectra for MS-based proteomics. We believe SpeCollate is significant progress towards developing machine-learning solutions for MS-based omics data analysis.

[Download paper here](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0259349')

Recommended citation: Tariq, M. U., & Saeed, F. (2021). "SpeCollate: Deep cross-modal similarity network for mass spectrometry data based peptide deductions." <i>PloS one</i>, 16(10), e0259349.
