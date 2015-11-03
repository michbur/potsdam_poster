Micha&#322; Burdukiewicz^1,&#35;^, Piotr Sobczyk^2^, Pawe&#322; Mackiewicz^1^ and Stefan R&#246;diger^3,&#42;^

^1^University of Wroc&#322;aw, Department of Genomics, Poland 

^2^Wroc&#322;aw University of Technology, Department of Mathematics, Poland

^3^Faculty of Natural Sciences, Brandenburg University of Technology Cottbus--Senftenberg, Germany

&#35; michalburdukiewicz@gmail.com  | &#42; Stefan.Roediger@b-tu.de

*dpcReport* -- Mobile-Health analysis framework  

Mobile-Health brings the medical examination to the patient. The hardware necessary for such diagnosis should be completed with a suitably portable analysis framework. It is getting more common that test are accompanied by mobile devices. In this spirit we introduce *dpcReport*, a versatile open source cross-platform software for analysis of digital PCR (dPCR) experiments. dPCRs are gaining more relevance in medical diagnostics. This includes detection of rare mutations and applications in tumor biology [1]. As any other Mobile-Health software, it might be accessed as a web server from a mobile communication device with a modern web browser. In addition to this, the *dpcReport* is also available for desktop machines as both web server and standalone software.

The functionalities of *dpcReport* include summary statistics alongside with appropriate charts, novel experiments comparison methods and quality control of input data. To streamline data analysis, the most fundamental elements of input objects can be edited directly in *dpcReport*, removing the need for additional data management.

The *dpcReport* is a Graphical User Interface based on dpcR package for statistical computing environment **R**. All functionalities are also accessible through a command-line, which also allows for a more sophisticated analysis tailored for expectations of a researcher. To streamline the conversion between GUI and **R** script, the *dpcReport* automatically generates **R** code which can be easily customized.

dpcR web-server:  http://www.smorfland.uni.wroc.pl/dpcReport 

MS Windows desktop application: http://sourceforge.net/projects/dpcreport/

[1] Rödiger, S., Burdukiewicz, M., Blagodatskikh, K.A., Schierack, P., 2015a. R as an Environment for the Reproducible Analysis of DNA Amplification Experiments. R J. 7, 127–150.