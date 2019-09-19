# SCRTP
The SCRTP manages high performance computing (HPC) facilities that are available for you to use.  First you will need an SCRTP account (which differs from, but requires your normal Warwick ITS account).  Obtain your SCRTP account [here](https://warwick.ac.uk/research/rtp/sc/desktop/gettingstarted).

## MathSys SCRTP Machines (CPUs)
MathSys have their own machines and list of hostnames for the complexity SCRTP machines are:

adobo  
bulalo  
halabos  
inihaw  
jamon  
kinilaw 
niliga  
okoy  
pinakbet  
sinuglaw  
rilyeno  
galunggong

You can access these machines using the following command in the terminal:

ssh username@hostname.complexity.warwick.ac.uk

Once you have your scrtp account, try accessing one of the complexity machines. You could also apply the techniques learnt earlier in the week regarding bash and ubuntu. Note that some machines are no longer maintained so if you do not connect withing 20 seconds, try another hostname.

## MathSys SCRTP Machines (GPUs)
MathSys also have machines with GPUs since Summer 2019. The hostnames are:

keiko  
kumeta

You can access these machines usng the following command in the terminal:

ssh username@hostname.scrtp.warwick.ac.uk

## Cluster of Workstations (CoW)
The CoW is a set of Linux desktops that you access remotely. They are similar to the MathSys machines but are maintained by the Centre for Scientific Computing (CSC) at Warwick.

The main node of the CoW is called godzilla, which can be accessed via:

ssh username@godzilla.csc.warwick.ac.uk

Note - **do not** run scripts directly on godzilla. Instead, you submit jobs, but this will be explained in a Computational Techniques session.

Once you have your scrtp account, try accessing godzilla.

## Orac, Tinis

These are two supercomputers that you have to register for access for separately (no need to do so now, it can take a while to obtain access).  The main strengths of these machines are as follows ([more information](https://warwick.ac.uk/research/rtp/sc/hpc/)):

Orac -> Parallel computing

Tinis -> Parallel computing and GPU computing
