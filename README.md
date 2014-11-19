Koonkie: An Automated Software Tool for Processing Environmental Sequence Information using Hadoop
=======
Dongjae Kim, Kishori M. Konwar, Niels W. Hanson, Steven J. Hallam

Current next-generation sequencing platforms produce increasingly vast text datasets from environmental samples that must be processed and interpreted by a variety of bioinformatics tools. Processing such datasets often requires custom-designed software and high-performance computing resources that in turn require regular monitoring and maintenance. The inherent design of traditional grid systems limits user control and on-demand accessibility and availability. Recent advances in high-speed Internet bandwidth and the emergence of affordable and scalable cloud-computing services offer attractive alternatives to traditional grid systems. However, adapting cloud-computing services to use available and emerging bioinformatics tools requires non-trivial setup and expertise. Here we present Koonkie, a flexible and scalable Hadoop-based software tool that can be used to process environmental sequence information with scalable cloud-computing services. Koonkie can automatically connect, configure, and launch processes on clouds, in a pay-as-you-go manner, without incurring additional monitoring and maintenance costs. Moreover, by exploiting novel features of YARN Koonkie can perform specialized tasks, like BLAST, requiring large side-data distributions that would have necessitated prohibitive communication costs in existing versions of Hadoop. We demonstrate Koonkie’s flexibility and performance by annotating Illumina sequence data from the Human Microbiome Project in a pipeline inspired by MetaPathways, a modular pipeline for analyzing environmental sequence information. Isolating the BLAST task, we find that Koonkie’s performance scales linearly with requisitioned AWS nodes. 

Citation:

Kim D., Konwar K.M., Hanson N.W., Hallam S.J., *Koonkie: An Automated Software Tool for Processing Environmental Sequence Information using Hadoop*, [Fourth ASE International Conference on Big Data (BigData 2014)](http://www.scienceengineering.org/ase/conference/2014/bigdata/boston/website/), Cambridge MA, December 13--16, 2014 (to appear).
