# MatSpinNet V1.0

Matlab code for quantum spin-1/2 networks. It provides code to analyse
the geometry of such networks, and some basic quantum control and 
characterisation code. Details are described in these papers: 

1. F. C. Langbein, S. G. Schirmer, E. Jonckheere. Time optimal 
   information transfer in spintronics networks. Proc. IEEE 54th 
   Annual Conference on Decision and Control (CDC), pp. 6454-6459, 
   Osaka, Japan, December 15-18, 2015. DOI:10.1109/CDC.2015.7403236
   arXiv:1508.00928 https://langbein.org/langbein2015/

2. E. Jonckheere, F. C. Langbein, S. G. Schirmer. Information Transfer
   Fidelity in Spin Networks and Ring-based Quantum Routers. Quantum 
   Information Processing, 14(12):4761-4785, 2015. 
   DOI:10.1007/s11128-015-1136-4 arXiv:1408.3765 
   https://langbein.org/jonckheere2015/

3. S. G. Schirmer, F. C. Langbein. Characterization and Control of
   Quantum Spin Chains and Rings. In: Proc. 6th Int Symp 
   Communications, Control and Signal Processing (ISCCSP), pp. 615 -
   619, May 2014. DOI:10.1109/ISCCSP.2014.6877950 arXiv:1403.0226 
   https://langbein.org/schirmer2014/

4. E. Jonckheere, F. C. Langbein, S. Schirmer. Quantum networks: 
   Anti-core of spin chains. Quantum Information Processing. 13(7):1607-
   1637, 2014. DOI:10.1007/s11128-014-0755-5 arXiv:1403.0159 
   https://langbein.org/jonckheere2014/

5. E. Jonckheere, F. C. Langbein, S. G. Schirmer. Curvature of quantum
   rings. In: Proc. 5th Int Symp Communications Control and Signal 
   Processing (ISCCSP), pp. 1-6, 2012. DOI:10.1109/ISCCSP.2012.6217863
   arXiv:1202.2556 https://langbein.org/jonckheere2012/

6. E Jonckheere, S G Schirmer, F C Langbein. Geometry and Curvature of
   Spin Networks. IEEE International Conference on Control Applicatons,
   pp. 786-791, 2011. DOI:10.1109/CCA.2011.6044395 arXiv:1102.3208 
   https://langbein.org/jonckheere2011/

To get started, go to the base directory of the package and run 
```setup('build')``` from matlab (to compile the code and extend the 
path. Runnning ```setup()``` without arguments only adds the paths.

Most functionality is provided via the qsn class. See ```help qsn``` 
and the help text for the relevant classes (```help qsn.QSN```, etc.)
for further information on how to use the code. The ```example_*``` 
scripts provide some examples for how to use the code. All this code is
in the ```+qsn``` matlab pacakge directory.

The ```timing``` directory contains timing estimation code for 
reference [2] above.

## Other Software Used

The following matlab packages have been adapted for this package and 
are in the ```@kde``` and ```GA`` sub-directory respectively:

GA - Alan de Freitas, Open Genetic Algorithm Toolbox, 2012.
Creative Commons Attribution Non-Commercial License V2.0
https://sourceforge.net/projects/gatoolbox/

@kde - Alexander Ihler, KDE Package, 2003.
GNU Lesser General Public License V2.1
https://www.ics.uci.edu/~ihler/code/kde.html

## License - AGPL v3.0

Copyright (C) 2011-2019
Frank C Langbein, Cardiff University;
Sophie G Shermer, Swansea University;
Edmond Jonckheere, USC.

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as
published by the Free Software Foundation, either version 3 of the
License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.

