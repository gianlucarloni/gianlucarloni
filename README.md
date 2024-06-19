# Hi! I am Gianluca

:point_right:[About me](https://github.com/gianlucarloni/gianlucarloni/blob/main/README.md#biomedical-engineer-msc-and-bsc-working-on-ai-for-medical-imaging-applications)

:point_right:[Coding contributions](https://github.com/gianlucarloni#some-of-my-coding-contributions)

## Biomedical engineer (MSc and BSc) working on AI for Medical Imaging applications
- Graduate **research fellow** at the National Research Council (CNR) in Pisa, Italy (Sep 2021 - Ongoing)
- Last-year **PhD student** in Information Engineering at the University of Pisa (Nov 2021 - Ongoing).
  Project: _“Boosting deep learning with causality: insights on medical imaging”_.
- My current interests and expertise span **out-of-distribution** robustness, domain **generalization**, and **explainability** through **causal reasoning**, feature **disentanglement** and **contrastive learning**.

### Recent research activity in Deep Learning, Biomedical Imaging, Computer Vision and AI

- Proposed methods based on causal inference to foster DL models’ robustness to domain shift via Transformer/Conv. feature disentanglement, contrastive learning, and injection of prior knowledge. Applied to lung anomalies classification from large chest X-ray datasets.
- Investigated techniques to discover causal disposition signals in images via Attention-inspired CNNs for cancer prediction from medical imaging (prostate T2w-MRI and digital pathology).
- Proposed biologically inspired DL networks for image classification akin to human vision.
- Experienced with DDPMs (generative AI) to synthesize MRI images of prostate cancer.
- Led a systematic literature review to study the intersection of causality and Explainable AI.
- Conducted multivar analyses on clinical, biophysical, optical, and MRI data for Alzheimer's.

### Technical skills

**Programming**: Python, Bash, MATLAB, Java, Android, SQL. **Python libraries**: PyTorch, CUDA, Scikit-learn, Pandas, NumPy, OpenCV, Biopython, PyDicom. **Tools**: Git version control, Docker, SLURM-based large-scale HPC, NVIDIA DGX, DICOM/NIFTI formats.

### Publications

You can find my published research works on my [Google Scholar](https://scholar.google.com/citations?hl=it&user=b4-Ad-kAAAAJ&view_op=list_works&sortby=pubdate) profile.


## Some of my coding contributions 

- "**MRI Reconstruction**" [CMRxReconChallenge](https://github.com/VIOS-Group/CMRxReconChallenge): A group project together with other PhD students to respond to the **MICCAI 2023** challenge https://cmrxrecon.github.io/ regarding cardiac cine MR reconstruction. It was so nice to code all together! Additional contributions [here](https://github.com/VIOS-Group/CMRxRecon_Edipo_Inference) and [here](https://github.com/vios-s/CMRxRECON_Challenge_EDIPO). You can read our paper [Cine cardiac MRI reconstruction using a convolutional recurrent network with refinement](https://arxiv.org/abs/2309.13385) to discover how we performed in the MICCAI STACOM workshop 2023.
- "**OOD/DG robustness**" A causal perspective on medical image classification via neural networks (causal_medimg)(private, in progress): When it comes to medical image classification, assessing whether DL algorithms truly capture the cause-and-effect relationship between diseases and their underlying causes (or merely learn to map labels to images) remains a challenge. This work aims at leveraging ideas from causal theory, feature disentanglement and contrastive learning to improve the out of distribution performance of deep learning image classifiers. It separates the features that causally influence the diagnosis and features that act as confounders.
- "**Causality/XAI**" [Boosting CNNs with knowledge of conditional asymmetries across feature maps (causality_conv_nets)](https://github.com/gianlucarloni/causality_conv_nets): Code for experimenting with causality-aware (driven) CNNs, where the network learns and exploits intrinsic information contained in image datasets regarding the causal disposition of object in the visual scene. See our **ESWA 2024** paper [Exploiting Causality Signals in Medical Images: A Pilot Study with Empirical Results](https://doi.org/10.1016/j.eswa.2024.123433) where we introduce the architecture and the "causality factor extractor". To see how such "causality-driven" neural networks can boost performance and XAI explanations in low-data scenarios (Few-Shot), check our **ICCV 2023** paper [Causality-Driven One-Shot Learning for Prostate Cancer Grading from MRI](https://openaccess.thecvf.com/content/ICCV2023W/CVAMD/html/Carloni_Causality-Driven_One-Shot_Learning_for_Prostate_Cancer_Grading_from_MRI_ICCVW_2023_paper.html)!!
- "**Generative AI**" [(Un)conditional Denoising Diffusion Probabilistic Models](https://github.com/gianlucarloni/diffusion_models_prostatePICAI): implementation of DDPMs in PyTorch for generating synthetic medical images of prostate cancer patients. I am developing both unconditional and conditional (classifier-free guidance) generation.
- "**Explainable AI (XAI)**" [ProtoPNet](https://github.com/andreaberti11235/ProtoPNet), with [@andreaberti11235](https://github.com/andreaberti11235): In our **ICPR 2022** [paper](https://link.springer.com/chapter/10.1007/978-3-031-37660-3_38), we investigate the application of prototypical part learning to the medical imaging field. In particular, mammographic images are used. The clinical question is to determine the malignancy of breast masses, and the goal is to assess that using Deep Learning methods, without an invasive biopsy, which still remains the gold standard today
- [dataset_utils_scripts](https://github.com/gianlucarloni/dataset_utils_scripts), with [@andreaberti11235](https://github.com/andreaberti11235): useful scripts for deep learning pipelines with digital images. Includes: stratified group splitting for dataset preparation, code for early stopping in neural networks' training, image resize and histogram of dimensions, scripts for reading DICOM/NIFTI files and convert them in PNG images, pipelines for Data Augmentation, etc

### Project collaborations (Italy, Greece, Portugal)
- [ProCAncer-I](https://www.procancer-i.eu/) European Union Project funded by Horizon 2020 research and innovation programme under grant agreement No 952159
- [TAILOR](https://tailor-network.eu/) European Union Project ICT-48 Network (GA 952215). A network of AI research excellence centre
- [NAVIGATOR](http://navigator.med.unipi.it/) Tuscany Regional Project. An Imaging Biobank to Precisely Prevent and Predict cancer, and facilitate the Participation of oncologic patients to Diagnosis and Treatment
- [PRAMA](http://si.isti.cnr.it/index.php/hid-project-category-list/201-project-prama) Tuscany Regional Project. Proteomics, RAdiomics & Machine learning-integrated strategy for precision medicine for Alzheimer’s

\#DeepLearning \#MachineLearning \#ArtificialIntelligence \#MedicalImaging \#Causality \#Explainability \#GenerativeModels
