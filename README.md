# Portfolio
I present all the relevant projects, posters, and reports I have done during my academic path (BSc in Biomedical Engineering and MSc in Neuro-X) and personal life. For most of them, you will be able to find a link to their specific repository.

## Listing of Projects
- [BSc Biomedical Engineering](#bsc-biomedical-engineering)
    - [PIC Project: Analysis and Correlation of Brain Motor Information in the Context of BMIs](#pic-project-analysis-and-correlation-of-brain-motor-information-in-the-context-of-bmis)
    - [Optimizing Pipeline for 3D Reconstruction of Protein Aggregates](#optimizing-pipeline-for-3d-reconstruction-of-protein-aggregates)
- [MSc Neuro-X](#msc-neuro-x)
- [Personal](#personal)

## BSc Biomedical Engineering
In the following section, I present all the relevant work I did during my Bachelor's in Biomedical Engineering at the Instituto Superior Técnico in Lisbon. These include:
- [PIC Project: Analysis and Correlation of Brain Motor Information in the Context of BMIs](#pic-project-analysis-and-correlation-of-brain-motor-information-in-the-context-of-bmis)
- [Optimizing Pipeline for 3D Reconstruction of Protein Aggregates](#optimizing-pipeline-for-3d-reconstruction-of-protein-aggregates)

---
### PIC Project: Analysis and Correlation of Brain Motor Information in the Context of BMIs
This is my final bachelor project (PIC Project). It was a joint work between IST and the Champalimaud Foundation. Here, we analysed how we can use machine learning algorithms to decode arm movement from neuron activity (action potentials). For it, we used the dataset from the [Neural Latents Benchmark](https://neurallatents.github.io/datasets): MC Maze.

#### Abstract
Using Brain-Machine Interfaces (BMI) to solve health problems related to the nervous system has proven a promising approach. With innovative studies that allow motor rehabilitation to companies developing and commercialising devices that grant seamless computer integration, the future solution to these problems lies with BMIs. We developed and applied two models: (a) Population vector and (2) Naïve Bayes to decode from 182 motor neurons’ hand movement from the MC Maze dataset. After optimisation, we obtained 0.24 and 0.45 in R2 correlation, respectively. They were able to shed light on many characteristics of the motor cortex, such as the tuning of the neurons and the increased amount of information they code. This information granted the possibility of improvement and adaptations of our models. However, we did not obtain correlations closer to other models applied to this dataset, as our decoders lacked developed
preprocessing steps. Nonetheless, this project works as an introduction to the BMI problem.

#### Acknowledgments
This project could not have been completed without the help of Dr Memming Park and Carolina Filipe (Champalimaud Research, Champalimaud Foundation, Portugal) and Dr Athanasios Vourvopoulos (Institute for Systems and Robotics/LaSEEB).

#### Links and Extras
> Final Grade: 19/20 <br>
> [Project Repository Link](https://github.com/GuilhermeCosta-Ferreira/PIC-Motor-Cortex-and-BMIs) <br>
> [Project Report File](./BSc%20Biomedical%20Engineering/Analysis%20and%20Correlation%20of%20Brain%20Motor%20Information%20in%20the%20Context%20of%20BMIs.pdf)

---
### Optimizing Pipeline for 3D Reconstruction of Protein Aggregates
In the [Principles of Biosignals and Biomedical Imaging](https://fenix.tecnico.ulisboa.pt/cursos/lebiom21/disciplina-curricular/845953938490063) class, with the help of João Freitas and Catarina Gonçalves, we built a new pipeline to improve on 3D cell reconstruction in Matlab. After the filtering step, we combined our Density Ascent Algorithm, the Otsu Method and Erosion and Dilation into (what we called) the Search2Segment Algorithm. We also analysed how to optimise the pipeline and proved its efficacy.

#### Abstract
Throughout different realities of the medical domain, it’s essential to study cellular structures due to the mechanism’s complexity and the biological processes. To do so, microscope observations are critical, and one of the most popular methods of structure elucidation in cell physiology is fluorescence microscopy. Given 28 histological slices from one cell containing two protein aggregates obtained by this technique, we applied fundamental steps from imaging processing. Moreover, this project has the purpose of reaching into a 3D reconstruction of the protein aggregates, which underlie the pathogenesis of neurodegenerative disorders, as well as computing the volume of these structures. Starting by removing characteristic noise from each slice through the Gaussian filter (after choosing it, compared to the median filter), we proceed to the segmentation and binarization phase, using the Search2Segment algorithm, a method developed by our group, which integrates the well-established Otsu method. During each stage, different parameters were tested and compared, aiming to preserve edges that shape aggregate form. With the masks applied, we assembled and aligned them to reconstruct the protein aggregates and calculate their volume. Based on a voxel dimension, we got to the total volume equal to 170.40 μm3.

#### Contacts
João Freitas: joao.ferreira.de.freitas@tecnico.ulisboa.pt <br>
Catarina Gonçalves: catarinamarquesgoncalves@tecnico.ulisboa.pt

#### Links and Extras
> Project Final Grade: 19.35/20 <br>
> [Project Repository Link](https://github.com/GuilhermeCosta-Ferreira/3DReconstruction) <br>
> [Project Report File](./BSc%20Biomedical%20Engineering/Optimizing%20Pipeline%20for%203D%20Reconstruction%20of%20Protein%20Aggregates.pdf)

## MSc Neuro-X
Here you will find the projects and reports I completed during my Master's degree.

## Personal
Here you will find the projects and reports I completed in my personal time.