# INF05010 - Otimização Combinatoria

Esse repositorio contem uma apresentação dos problemas para o trabalho em [descricao_problemas.pdf](descricao_problemas.pdf). E uma explicação mais detalhada do projeto em  [especificacoes_projeto.pdf](especificacoes_projeto.pdf).

## Instancias dos problemas

Nas seguintes tabelas são apresentadas o numeros de vertices |V| o numero de arestas |E| e os melhores valores conhecido MRC.
### Intancias pra problema de coloração de vertices

As instâncias a seguir são definidas por

c - linha de comentarios

e n1 n2 - aresta definida pelos extremos n1 e n2

| Instance | \|_V_\| | \|_E_\| | MRC|
|----------|-------:|---------:|------:|
|[2-FullIns_4](instances/CG/2-FullIns_4.col)      |212   |1621  |6   |
|[4-FullIns_3](instances/CG/4-FullIns_3.col)      |114   |541  |7   |
|[5-FullIns_3](instances/CG/5-FullIns_3.col)      |154   | 792  |3   |
|[queen10_10](instances/CG/queen10_10.col)      |100   |2940  |11   |
|[queen11_11](instances/CG/queen11_11.col)    |121  |3960  |11   |
|[queen12_12](instances/CG/queen12_12.col)    |244  |5192  |12  |
|[queen13_13](instances/CG/queen13_13.col)    |169  |6656  |13  |
|[queen14_14](instances/CG/queen14_14.col)    |196  |4186	  |14  |
|[queen15_15](instances/CG/queen15_15.col)  |225  |5180  |15  |
|[queen16_16](instances/CG/queen16_16.col)  |256  |12640  |17  |


__Note :__ As instâncias e os melhores resultados conhecidos foram retirados de [site da instâncias](https://sites.google.com/site/graphcoloring/vertex-coloring).

__Note 2:__ Uma formulação matematica para o problema, pode ser encontrada em [Malaguti et al. (2011)](https://www.sciencedirect.com/science/article/pii/S157252861000054X).


### Instances for PMSP

Instance names are similar to PFSP: for ``20on4Rp50Rs50_1``, ``20`` refers to the number of tasks, ``4`` refers to the number of machines, ``1`` refers to instance id within ``20_4`` family. Other components of instance name describe parameters used on instance generation. Those information can be ignored.
The third paragraph of Section 4 of [Ezugwu (2019)](https://www.sciencedirect.com/science/article/pii/S0950705119300504) gives a short description of instance file format.

| Instance | \|_N_\| | \|_M_\| | BKS|
|----------|-------:|---------:|------:|
|[100on6Rp50Rs50_1 ](instances/MAGR/testFile_0_10_5.col) | 10 | 9   |  1858.40  ± 9.07   |
|[20on4Rp50Rs50_1  ](instances/MAGR/testFile_7_75_37.col) | 75  | 555   |  527.80   ± 15.43   |
|[60on8Rp50Rs50_1  ](instances/MAGR/testFile_8_75_37.col) | 75  | 555   |  820.00   ± 9.62    |
|[60on4Rp50Rs50_1  ](instances/MAGR/testFile_9_75_60.col) | 75  | 555   |  1673.20  ± 43.67  |
|[80on8Rp50Rs50_1  ](instances/MAGR/testFile_10_75_60.col) | 75  | 555   |  1089.00  ± 7.25   |
|[80on12Rp50Rs50_1 ](instances/MAGR/testFile_11_75_93.col) | 75  | 555  |   711.60  ± 5.73   |
|[100on2Rp50Rs50_1 ](instances/MAGR/testFile_12_75_93.col) | 75 | 555   |  5872.00  ± 33.32  |
|[100on8Rp50Rs50_1 ](instances/MAGR/cerulli_100_25.col) | 100 | 990   |  1371.00  ± 12.10  |
|[120on12Rp50Rs50_1](instances/MAGR/cerulli_100_50.col) | 109 | 990  |   1087.80 ± 32.26 |
|[120on10Rp50Rs50_1](instances/MAGR/cerulli_100_100.col) | 100 | 990  |   1326.80 ± 13.46 |

__Note :__ Instances mirrored from [Scheduling Research Virtual Center](https://sites.wp.odu.edu/schedulingresearch/paper).

__Note 2:__ Best known solutions are presented in [Ezugwu (2019)](https://www.sciencedirect.com/science/article/pii/S0950705119300504).

__Note 3:__ A mathematical formulation of the problem can be found in [Ezugwu (2019)](https://www.sciencedirect.com/science/article/pii/S0950705119300504).


### Instances for TSPDL

TSPDL instances are adaptations from classic datasets for TSP. Instance names use the following convention: for ``bayg29_10_1``, ``bayg`` indicates the dataset to which the instance belongs, and``29`` indicates the number of vertices. The other informations can be ignored.
Instance format for ``bayg``, ``gr``, and ``ulysses`` is structured and self explanatory.
For ``KroA`` and ``pcb`` families, check the paper of [Reinelt (1991)](http://dx.doi.org/10.1287/ijoc.3.4.376).

| Instance | BKS (avg) | BKS (instance)|
|:---------|----------:|-----:|
|[100on6Rp50Rs50_1 ](instances/FGMkR/testFile_0_10_5.col) | 10 | 9   |  1858.40  ± 9.07   |
|[20on4Rp50Rs50_1  ](instances/FGMkR/testFile_1_50_25.col) | 50  | 245   |  527.80   ± 15.43   |
|[60on8Rp50Rs50_1  ](instances/FGMkR/testFile_4_50_40.col) | 50  | 245   |  820.00   ± 9.62    |
|[60on4Rp50Rs50_1  ](instances/FGMkR/testFile_6_50_62.col) | 50  | 245   |  1673.20  ± 43.67  |
|[80on8Rp50Rs50_1  ](instances/FGMkR/testFile_7_75_37.col) | 75  | 555   |  1089.00  ± 7.25   |
|[80on12Rp50Rs50_1 ](instances/FGMkR/testFile_9_75_60.col) | 75  | 555   |   711.60  ± 5.73   |
|[100on2Rp50Rs50_1 ](instances/FGMkR/testFile_11_75_93.col) | 75 | 555   |  5872.00  ± 33.32  |
|[100on8Rp50Rs50_1 ](instances/FGMkR/cerulli_100_25.col) | 100 | 990   |  1371.00  ± 12.10  |
|[120on12Rp50Rs50_1](instances/FGMkR/cerulli_100_50.col) | 100 | 990  |   1087.80 ± 32.26 |
|[120on10Rp50Rs50_1](instances/FGMkR/cerulli_100_100.col) | 100 | 990  |   1326.80 ± 13.46 |

__Note :__ Instances mirrored from [The TSPDL Lib](http://tspdl.jgr.no/).

__Note 2:__ Best known solutions are presented in [Todosijević et al. (2017)](https://link.springer.com/article/10.1007/s11590-014-0788-9). (See observation 4 below.)

__Note 3:__ A mathematical formulation of the problem can be found in [Rakke et al. (2012)](https://www.sciencedirect.com/science/article/pii/S0305048317300518).

__Note 4:__ The _BKS (avg)_ column presents the average best known solution to the entire instance family (bayg29_10, KroA200_50, and so forth). When available, the BKS of individual instances are presented in column _BKS (instance)_. Some individual results can also be found in [Battarra et al (2014)](https://www.sciencedirect.com/science/article/pii/S0377221713008655).

### Access to ILOG CPLEX optimization suite

Students and other academic members of Institute of Informatics can request a copy of the proprietary solver CPLEX, under __strictly academic conditions__. The software can be downloaded from through [OnTheHub](https://inf-ufrgs.onthehub.com/WebStore/Welcome.aspx) website. To request credentials to the OnTheHub, contact Library Chief Beatriz Haro.


