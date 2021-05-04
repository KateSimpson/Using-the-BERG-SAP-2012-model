# Using-the-BERG-SAP-2012-model
Hi there,

This is a repository for the inputs I have used to carry out a simple trial on local sensitivity analysis using the BERG SAP 2012 Python model, developed by Steven Firth and Ben Halls, available with full documentation via: https://sap2012.readthedocs.io/en/latest/.

The inputs are JSON files and labelled as follows:
* 16-21: Represents the heating set point used (16-21C), all other inputs remain the same

* 16-21 WF: Represents Wall and Floor upgrades to minimum building regulation standards, for each heating set point (16-21)

* 16-21 FF: Represents Full Fabric upgrade to stringent U-Values, for each heating set point (16-21)

The table below summarises this.

|Element      |Area      |A: Base Case (16-21)   |B: Partial fabric retrofit (16-21 WF)|C: Full fabric retrofit (16-21 FF)  |
|-----        |----           |----              |-----              |-----             |
|             |(m2)           |U-Values (W/m2/K) |U-Values (W/m2/K)  |U-Values (W/m2/K) |                      
|Door	        |6.2	          |3                 |3                  |	0.80            |
|Windows	    |15.1	          |1.85              |1.85               |	0.80            |
|Floor	      |41.4           |1.1	             |1.1                |	0.15            |
|Wall	        |96.7           |0.68              |0.30               |	0.15            |
|Roof	        |41.4           |0.68              |0.15               |	0.13            |
|Party wall   |38.5           |0.5               |0.5                |	0.5             |

It is a bit of an experiment for me to use an open model here and share input files so please get in touch if I have missed anything, something is unclear or just to discuss!

Hope this is helpful for future users of the BERG model, or anybody who wishes to reproduce findings from my own research. I am grateful to the model creators for sharing their work openly and hope it inspires further open work in energy demand research.

Thanks for reading.

Kate

kate.simpson@imperial.ac.uk
