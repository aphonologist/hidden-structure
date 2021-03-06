HIDDEN STRUCTURE SUITE V3

This software package consists of a suite of constraint-based hidden structure learning algorithms, including:
- Gradual Learning Algorithm (GLA; Boersma 1997, Boersma & Hayes 2001) with Robust Interpretive Parsing (RIP; Boersma 2003, Boersma & Pater 2016), with Resampling RIP (RRIP; Jarosz 2013, Jarosz 2016a), and Expected Interpretive Parsing (EIP: Jarosz 2013, Jarosz 2016a)
———— All three GLA parsing strategies can be used with either Stochastic OT (Boersma 1997, Boersma & Hayes 2001) or Noisy HG (Boersma & Pater 2016)
- Expectation Driven Learning (EDL: Jarosz 2015, Jarosz 2016b, Nazarov 2016, Nazarov & Jarosz 2017, Nazarov 2018) for pairwise ranking grammars (Jarosz 2015) 
———— There are both batch and online versions of EDL

All learners in V3 can handle structural ambiguity (e.g. hidden prosodic structure), and the EDL learners (both batch and online) have the option of also learning underlying representations. As of V3, the EDL learners also have the option of learning in Harmonic Serialism (currently only in console mode).

RUNNING THE PROGRAM

There are two ways to run this program:

GUI version: The easiest way to is download and run the GUI jar file (gui.jar). This lets you interact with the learners through a Java GUI. Instructions can be found in the gui_instructions.txt file in the instructions directory. HS learning is not yet implemented in the GUI.

Console version: If you are interested in running code at the command line, you should use the console.jar file. You will need to have the build tool SBT installed, and you will have to compile and run the code through SBT. Instructions can be found in the console_instructions.txt file in the instructions directory.

Development: If you are interested in working with the source code and/or making modifications, see information in the development directory.

SOFTWARE CREDITS, CITING, & CONTACT INFO

Jarosz, Gaja, Carolyn Anderson, Andrew Lamont, and Brandon Prickett. 2018. Hidden Structure Suite: Version 3. http://github.com/gajajarosz/hidden-structure
Jarosz, Gaja. 2013. Learning with Hidden Structure in Optimality Theory and Harmonic Grammar: Beyond Robust Interpretive Parsing. Phonology 30(1). 27–71.
Jarosz, Gaja. 2015. Expectation Driven Learning of Phonology. University of Massachusetts, Amherst, ms.

Gaja Jarosz wrote the code for the EDL and the GLA x (RIP, RRIP, EIP) x (OT, HG) algorithms
Carolyn Anderson wrote the code to embed the algorithms within the current GUI and console environments, unify the system of parameters, and to optimize the run-time of grammar sampling for the EDL.
Andrew Lamont designed modules for HS and for construction of abstract UR distributions from paradigmatic information (to be implemented at a future point).
Brandon Prickett implemented HS modules (CON and GEN) for the EDL.
Documentation and sample files were prepared jointly.

Contact Gaja Jarosz (last name __ at __ linguist.umass.edu) with questions.

Sample grammar and distribution files in the sample_files directory:
— TS... languages were defined by Tesar & Smolensky (2000), and the learning files were created by Paul Boersma
- Pater2008... language is defined by Pater (2008) and written by Gaja Jarosz
- PAKA... input files were defined by Tesar et al. (2003) and Tesar (2006) and written by Gaja Jarosz

REFERENCES

Boersma, Paul. 1997. How we learn variation, optionality, and probability. IFA Proceedings 21. 43–58.
Boersma, Paul & Bruce Hayes. 2001. Empirical Tests of the Gradual Learning Algorithm. Linguistic Inquiry 32(1). 45–86.
Boersma, Paul & Joe Pater. 2016. Convergence Properties of a Gradual Learning Algorithm for Harmonic Grammar. In John McCarthy & Joe Pater (eds.), Harmonic Grammar and Harmonic Serialism. London: Equinox Press.
Jarosz, Gaja. 2013. Learning with Hidden Structure in Optimality Theory and Harmonic Grammar: Beyond Robust Interpretive Parsing. Phonology 30(1). 27–71.
Jarosz, Gaja. 2015. Expectation Driven Learning of Phonology. University of Massachusetts, Amherst, ms.
Jarosz, Gaja. 2016a. Investigating the Efficiency of Parsing Strategies for the Gradual Learning Algorithm. Dimensions of Phonological Stress, 201.
Jarosz, Gaja. 2016b. Learning opaque and transparent interactions in Harmonic Serialism. Proceedings of the Annual Meetings on Phonology, vol. 3.
Nazarov, Aleksei. 2016. Extending Hidden Structure Learning: Features, Opacity, and Exceptions. Doctoral Dissertations.
Nazarov, Aleksei & Gaja Jarosz. 2017. Learning Parametric Stress without Domain-Specific Mechanisms. Proceedings of the Annual Meetings on Phonology 4(0).
Nazarov, Aleksei. 2018. Learning within- and between-word variation in probabilistic OT grammars. Proceedings of the Annual Meeting on Phonology 2017.
Pater, Joe. 2008. Gradual Learning and Convergence. Linguistic Inquiry 39(2). 334–345. doi:10.1162/ling.2008.39.2.334.
Tesar B, Smolensky P. 2000. Cambridge, Massachusetts: MIT Press
Tesar B. 2006. Faithful Contrastive Features in Learning. Cognitive Science. 30(5):863–903
Tesar B, Alderete J, Horwood G, Merchant N, Nishitani K, Prince A. 2003. Surgery in Language Learning. In Proceedings of the 22nd West Coast Conference on Formal Linguistics, pp. 477–90

