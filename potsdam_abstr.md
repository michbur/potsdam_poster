Micha&#322; Burdukiewicz^1^, Piotr Sobczyk^2^, Pawe&#322; Mackiewicz^1^ and Stefan R&#246;diger^3^

^1^University of Wroc&#322;aw, Department of Genomics, Poland 

^2^Wroc&#322;aw University of Technology, Department of Mathematics, Poland

^3^Faculty of Natural Sciences, Brandenburg University of Technology Cottbus--Senftenberg, Germany

# *dpcReport* -- Mobile-Health analysis framework  

Point-of-Care tests brings the medical examination to the patient. The hardware necessary for such diagnosis should be completed with a suitably portable analysis framework. In common scenario a POC test is accompanied by mobile health, the use of mobile devices in health care. In this spirit we introduce *dpcReport*, a versatile open source cross-platform software for analysis of digital PCR (dPCR) experiments. As any other Mobile-Health software, it might be accessed as a web server from a mobile communication device with a modern web browser. In addition to this, the *dpcReport* is also avaible on desktop machines as both web server and standalone software.

The functionalities of *dpcReport* include summary statistics alongside with appropriate charts, novel experiments comparison methods and quality control of input data. To streamline data analysis, the most fundamental elements of input objects can be edited directly in *dpcReport*, removing the need for additional data management.  

The *dpcReport* is a Graphical User Interface based on dpcR package for statistical computing environment **R**. All functionalities are also accessible through a command-line, which also allows for a more sophisticated analysis tailored for expectations of a researcher. To streamline the conversion between GUI and **R** script, the *dpcReport* automatically generates **R** code which can be easily customized.  

The dpcR web-server can be accessed under the address http://www.smorfland.uni.wroc.pl/dpcReport. The stand-alone version for the Microsoft Windows platform can be downloaded from http://sourceforge.net/projects/dpcreport/.
