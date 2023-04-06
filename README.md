# DNApoly-v2.0 
Create your DNA box using DNA Polyominoes. The original publication describing the self-organised fabrication strategy can be found here: Self-assembly programming of DNA polyominoes - https://doi.org/10.1016/j.jbiotec.2016.08.017

### Description
DNApoly is a nature-inspired approach to construct biocomputers mimicking the 80s video game [Tetris](https://en.wikipedia.org/wiki/Tetris). You can construct three-dimensional structures by combining DNA walls (technical term, DNA network configurations). You can find the program to create these walls in this repository (DNApoly-v1.0). In this project, you can use the interactive python notebook `N_construct` to generate links to combine these walls into a box. You can change the box dimensions by modifying the number of walls.

### Requirements
* Python 3.x
* Jupyter Notebook
* You need to run DNAPoly v1.0 to generate the relevant DNA network configuratios (3x4, or 4x4). `DNApoly-v1.0` is available in this repository for local installation. You need to run `RNAStructure` (https://www.urmc.rochester.edu/rna/) to run the sequence-structure optimisation mode. You need to install the package locally on your machine.

---
* Please cite this article if you are running `DNApoly-v1.0`:  
  DNA Tetrominoes: The Construction of DNA Nanostructures Using Self-Organised Heterogeneous Deoxyribonucleic Acids Shapes Ong HS, Rahim MS, Firdaus-Raih M, Ramlan EI (2015) DNA Tetrominoes: The Construction of DNA Nanostructures Using Self-Organised Heterogeneous Deoxyribonucleic Acids Shapes. PLOS ONE 10(8): e0134520. https://doi.org/10.1371/journal.pone.0134520

* Please cite this articule if you are running `RNAStructure`:  
  Reuter, J.S., Mathews, D.H. RNAstructure: software for RNA secondary structure prediction and analysis. BMC Bioinformatics 11, 129 (2010). https://doi.org/10.1186/1471-2105-11-129

---
### Installation
* Clone this repository: git clone https://github.com/eiramlan/DNApoly.git

### Usage
1. Start Jupyter Notebook: jupyter notebook
2. Open the notebook file: n_contruct.ipynb
3. Follow the instructions in the notebook to run the program.

### License
This project is licensed under the GNU General Public License v3.0. See the LICENSE file for more details.
