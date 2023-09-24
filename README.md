# Description:
The data of (i) heats of transport values and (ii) coefficients for expressions of free energy density of phases used to generate the results in the paper [1]  titled "Preferential growth of intermetallics under temperature gradient at Cu–Sn interface during transient liquid phase bonding: insights from phase field simulation" are provided in this dataset.
The heats of transport (Q*) values of Cu and Sn species in LIQUID (Sn-rich), IMC (CU6SN5) and FCC (Cu-rich) phases at 523.15 K are available in heat_of_transport.csv file. The numerical quantities in the Q* column of the file are expressed in the unit of kJ/mol.  
The chemical free energy density of a phase i (i = LIQUID, IMC or FCC ) at 523.15 K has been expressed with  the function f_i = 0.5 * A_i * (c_i - c_eq,i)^2 + B_i * (c_i - c_eq,i) + C_i; where c_i is the mole-fraction (composition) of Sn in a phase.  The data consisting of the numerical values of coefficients A_i, B_i and C_i on the units of J/m^3 are provided in the file free_energy_density.csv. Besides these coefficients, the file also consists the quantified values of the equilibrium composition c_eq,i at each phase. It is to be noted that c_eq,i has no units.





[1] S. Liang, A. Kunwar, C. Liu, H. Jiang, and Z. Zhou, “Preferential growth of intermetallics under temperature gradient at Cu–Sn interface during transient liquid phase bonding: insights from phase field simulation,” Journal of Materials Research and Technology, vol. 19, pp. 345–353, 2022, doi: 10.1016/j.jmrt.2022.05.047.
