# QGALookUpTable
QGA based on qutrtit by lookup table
In this project we have three folders: Function,Model,Operation

In Function folder we have three class : 
1 Formules.cs : test functions of paper are in this class
2 Translate_Decimal.cs : use to convert teneray number to decimal number
3 Translate_Tenary.cs : use to convert decimal number to teneray number

In Model folder we have three class which be used for data structure of program :
1 ClassicChromosome.cs : define strucutre of classic chromosome
2 QuantumChromosome.cs : define strucutre of quantum chromosome
3 Qutrit.cs : define strucutre of qutrit quantum gene

In Operation folder we have operation of QGA :
1 Fitness.cs : use to find best chromosome and calculate fitness function
2 Initail.cs : use to inital first population
3 Observe.cs : use to observe quantum population to make classic population
4 Rotation.cs : this class is proposed lookup table for QGA base of qutrit
5 Update.cs : use to generate next population
  
In Fitness.cs, the Calc_Function method must be modify depends of test function
In Initail.cs, chromosome size in Initial_QuantumPopulation method must be modify depends of test function
PopulationSize can be set in Program.cs
Angles of rotation gate can be set in Update.cs
we use one angle for all rotation gate, this angle is a variable named LookUpTable_Qutrit_Teta
