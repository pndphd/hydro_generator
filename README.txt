This file takes a vector grid and rasters of depth and velocity and makes an inSALMO hydro file.
Example bellow:

Line 1
Line 2
Flows:	75.0	150.0	
Cell	D@75	V@75	D@150	V@150	
1	0.130332946777344	0.412750512361526	0.756332397460938	0.496609389781952	
2	0	0	0.550721486409505	0.366691589355469				
3	0	0	0	0			
4	0	0	1.134698721078726	0.46637654533753			
5	0.113721838458961	4.8345757824e-05	0.384010314941406	0.020157269202173	
6	0	0	0	0		
7	0	0	0	0			



Instructions
Peter Dudley
4/4/2017
1)	The grid file must have some attributes that are deleteable (if nothing else at least and ID) 
2)	The rasters should be titled (assuming the flow is 222cms) “V222” and “D222”
3)	Highlight all the rasters you want to use.
4)	Chose the grid
5)	Chose an output location.  The program will append “.Data” to your file name
6)	Run 
