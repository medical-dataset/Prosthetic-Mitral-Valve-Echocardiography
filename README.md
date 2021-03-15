# Prosthetic-Mitral-Valve-Echocardiography

The first step in the automatic evaluation of the cardiac prosthetic valve is the recognition of such valves in echocardiographic images. This research surveyed whether a deep convolutional neural network (DCNN) could improve the recognition of prosthetic mitral valve in conventional 2D echocardiographic images. An efficient intervention to decrease the misreading rate of the prosthetic mitral valve is required for non-expert cardiologists. This intervention could serve as a section of a fully-automated analysis chain, alleviate the cardiologist’s workload, and improve precision and time management, especially in an emergent situation. Additionally, it might be suitable for pre-labeling large databases of unclassified images. We, therefore, introduce a large publicly-available annotated dataset for the purpose of prosthetic mitral valve recognition.
The database incorporated images, physician reports, and clinical data from patients with waived consent in compliance with the institutional review board at a tertiary referral heart center. Our accredited echocardiography laboratory obtains cardiac imaging from patients with various cardiac conditions such as coronary artery disease, cardiomyopathy, congenital heart disease, and valvular disease. For this study, the data were collected from studies on patients who referred to one of the authors between November 2018 and April 2020. These studies were conducted on adults via the use of Philips equipment (Philips, Affinity 70C, Andover, MA, USA) with an S5-1 probe at an average frame rate of 41 ± 8 frames per second. All patients were in non-emergency setting or in outpatient setting.
A total of 2046 comprehensive non-stress transthoracic echocardiography cases were gathered: 1597 patients with natural MV and 447 patients with prosthetic MV. Natural MV images consisted of normal, prolaptic, and stenotic MV. Although the structural properties of the prosthetic mitral valve are different from the natural mitral valve, the interaction of ultrasound and prosthetic mitral valve such as shadowing and reverberation artifact produce more distinguishing properties.
For each case, cardiac cycle videos of both A4C and PLA views were stored in the Digital Imaging and Communications in Medicine (DICOM) format.  
Then for each view, each clip was visually classified and labeled as prosthetic or natural MV by a single cardiologist highly experienced in advanced echocardiography with more than a decade of experience. Note that all the frames of 1 cycle were classified as natural or prosthetic MV images. 

# Download dataset : 
Please fill the request form (registerform.docx) and send it to majvaf@gmail.com to receive the download link.



If you find this dataset useful in your research, please use the following BibTeX entry for citation.

@misc{xxx,
  author =       {Majid Vafaeezadeh, Hamid Behnam, Ali Hosseinsabet, Parisa Gifani },
  title =        {A Deep Learning Approach for the Automatic Recognition of Prosthetic Mitral Valve in Echocardiographic Images },
  howpublished = {\url{xxx}},
  year =         {2021}
}

