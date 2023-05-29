# Epidemiología molecular, resistoma y viruloma de clones de alto riesgo de Pseudomonas aeruginosa de origen hospitalario.


En este repositorio se encuentran los ficheros generados durante el Trabajo de fin de máster de la UOC



Para realizar este trabajo se ha utilizado el pipeline RMAP (Rapid Microbial Analysis Pipeline https://github.com/GunzIvan28/rMAP) herramienta desarrollada para caracterizar el resistoma, viruloma y estudio del pangenoma, entre otros, de los microorganismos catalogados como ESKAPE (* *Enterococcus faecium* *, Staphylococcus aureus, Klebsiella pneumoniae, Acinetobacter baumannii, Pseudomonas aeruginosa y Enterobacter (Figura 3).  
 ![image](https://github.com/ItxaSarko/WorkflowPseudomonasTFM/assets/100303282/8a5005c5-7ec9-4bc4-ab89-fb07d476a375)

Figura 3. Flujo de trabajo llevado a cabo por la herramienta rMAP utilizada en este trabajo: Análisis de calidad de los reads (FastQC, MultiQC, Trimmomatic), reconstrucción del genoma (Megahit), anotación del genoma (Prokka), detección de mecanismos de resistencia, virulencia y búsqueda de plásmidos (AMRFinder, Abricate, Blastn), análisis del pangenoma (Roary, FastTree) y caracterización de secuencias de inserción (ISMapper). Adaptada de 
https://www.microbiologyresearch.org/content/journal/mgen/10.1099/mgen.0.000583
Para la identificación bacteriana y detección de posibles contaminaciones se ha utilizado la herramienta Kraken2 (Versión 2.1.1) del entorno Galaxy Europe (http://usegalaxy.eu/) y para el estudio del resistoma mutacional se ha empleado Snipyy. Esta herramienta consiste en identificar aquellas posiciones nucleotídicas que son diferentes con respecto al genoma de referencia (PA01).

A lo largo del trabajo se ha utilizado Rstudio con la librería ggplot2, para representar las gráficas correspondientes. Los scripts utilizados para el análisis de este estudio que permiten la automatización de procesos en la plataforma Linux (SH-SCRIPTS) se encuentran publicados en este repositorio.


