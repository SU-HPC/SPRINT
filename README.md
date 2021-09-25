# SPRINT

## Sparse Storage Formats

1. **COO**
- Mode Generic
- [Paper](https://ieeexplore.ieee.org/document/4072891)
- [Repo](https://github.com/hpcgarage/ParTI)

2. **HiCOO**
**Published in** SC18: International Conference for High Performance Computing, Networking, Storage and Analysis
- Mode Generic
- [Paper](http://fruitfly1026.github.io/static/files/sc18-li.pdf)
- [Repo](https://github.com/hpcgarage/ParTI)

3. **F-COO**
- Mode Generic
- [Paper](https://par.nsf.gov/servlets/purl/10049150)
- [Repo](https://github.com/kobeliu85/mttkrp-gpu)

4. **CSF**
- Mode Specific
- [Paper](https://par.nsf.gov/servlets/purl/10049150)
- [Repo](https://github.com/ShadenSmith/splatt)

5. **B-CSF**
- Mode Specific
- [Paper](https://arxiv.org/pdf/1904.03329.pdf)
- [Repo](https://github.com/isratnisa/B-CSF)

6. **HB-CSF**
- Mode Specific
- [Paper](https://arxiv.org/pdf/1904.03329.pdf)
- [Repo](https://github.com/isratnisa/B-CSF)

7. **MM-CSF**
- Mode Specific
- [Paper](https://dl.acm.org/doi/pdf/10.1145/3295500.3356216)
- [Repo](https://github.com/isratnisa/MM-CSF)

8. **CISS**
- Mode Specific
- [Paper](https://www.csl.cornell.edu/~zhiruz/pdfs/tensaurus-hpca2020.pdf)

9. **ALTO**
- Mode Generic
- [Paper](https://arxiv.org/pdf/2102.10245.pdf)

10. **2:4 Sparsity (Matrix Only)**
- Mode Specific
- [Slide](https://drive.google.com/file/d/1ORZ_arxlqMYiD-_eSRjRyY0Wdmpu4eZG/view)

## Frameworks

### Tensor
1. [The Surprisingly ParalleL spArse Tensor Toolkit (SPLATT)](https://github.com/ShadenSmith/splatt)
2. [ParTI!](https://github.com/hpcgarage/ParTI)
3. [Cyclops Tensor Framework (CTF)](https://github.com/cyclops-community/ctf)
4. [FROSST (Data)](http://frostt.io/)
4. [TACO](http://tensor-compiler.org/)

### Graph
1. [Gunrock](https://github.com/gunrock)
2. [GraphBLAST](https://github.com/gunrock/graphblast)
3. [cuGRAPH](https://github.com/rapidsai/cugraph)
4. [CombBLAS](https://github.com/PASSIONLab/CombBLAS)
5. [GraphBLAS](https://github.com/GraphBLAS)
6. [nvGraph](https://developer.nvidia.com/nvgraph)
7. []

### Matrix

1. [Eigen](https://eigen.tuxfamily.org/index.php?title=Main_Page)
2. [LAPACK](http://www.netlib.org/lapack/)
3. [ScaLAPACK](http://www.netlib.org/scalapack/)
4. [BLAS](http://www.netlib.org/blas/)
5. [suitesparse](https://people.engr.tamu.edu/davis/suitesparse.html)
5. [Armadillo](http://arma.sourceforge.net/)
6. [MAGMA](http://icl.cs.utk.edu/magma/)
7. [sparseX](http://research.cslab.ece.ntua.gr/sparsex)
8. [Pardiso](https://www.pardiso-project.org/)

## Papers

### Tensor

1. [Efficient MATLAB computations with sparse and factored tensors](https://www.kolda.net/publication/SIAM-67648.pdf)
	, SIAM Journal on Scientific Computing, vol. 30, no. 1, pp. 205–231, December 2007
20. [Tensor Decompositions and Applications](https://www.kolda.net/publication/TensorReview.pdf)
	, SIAM Review, vol. 51, no. 3, pp. 455–500, 2009
1. [GigaTensor: Scaling Tensor Analysis Up By 100 Times](https://www.cs.cmu.edu/~christos/PUBLICATIONS/kdd12-gigatensor.pdf)
2. [SpTFS: sparse tensor format selection for MTTKRP via deep learning](https://dl.acm.org/doi/abs/10.5555/3433701.3433724)
3. [Load-Balanced Sparse MTTKRP on GPUs](https://arxiv.org/pdf/1904.03329.pdf)
4. [ALTO: Adaptive Linearized Storage of Sparse Tensors](https://arxiv.org/pdf/2102.10245.pdf)
5. [DFacTo: Distributed Factorization of Tensors](https://arxiv.org/pdf/1406.4519.pdf)
6. [Software for Sparse Tensor Decomposition on Emerging Computing Architectures](https://arxiv.org/pdf/1809.09175.pdf)
7. [Format Abstraction for Sparse Tensor Algebra Compilers](https://arxiv.org/pdf/1804.10112.pdf)
8. [Implementing a high performance tensor library](https://downloads.hindawi.com/journals/sp/2003/205264.pdf)
9. [Optimizing sparse tensor times matrix on GPUs](https://www.sciencedirect.com/science/article/abs/pii/S0743731518305161)
10. [Efficient and Scalable Computations with Sparse Tensors](http://www.ieee-hpec.org/2012/index_htm_files/Baskaranpaper.pdf)
	, High Performance Extreme Computing (HPEC), 2012
11. [Scalable sparse tensor decompositions in distributed memory systems](https://hal.inria.fr/hal-01148202v2/document)
	, International Conference for High Performance Computing, Networking, Storage and Analysis, 2015
12. [High-performance parallel algorithms for the Tucker decomposition of higher order sparse tensors](https://hal.inria.fr/hal-01219316/document)
13. [HaTen2: Billion-scale Tensor Decompositions](https://www.cs.ucr.edu/~epapalex/papers/haten2_icde2015.pdf)
	, International Conference on Data Engineering (ICDE), 2015
14. [SPLATT: Efficient and Parallel Sparse Tensor-Matrix Multiplication](https://conservancy.umn.edu/bitstream/handle/11299/215973/15-008.pdf;jsessionid=0DB8D6E0AE1089BFB9B6C410AA9F1A3F?sequence=1)
	, Parallel & Distributed Processing Symposium, ser. IPDPS, 2015
15. [Tensor-Matrix Products with a Compressed Sparse Tensor](https://dl.acm.org/doi/pdf/10.1145/2833179.2833183)
16. [Efficient and effective sparse tensor reordering](https://hal.inria.fr/hal-02306569/document)
17. [HiCOO: Hierarchical Storage of Sparse Tensors](http://fruitfly1026.github.io/static/files/sc18-li.pdf)
18. [An Eficient Mixed-Mode Representation of Sparse Tensors](https://par.nsf.gov/servlets/purl/10172913)
19. [Sparse Tensor Algebra as a Parallel Programming Model](https://arxiv.org/pdf/1512.00066.pdf)
	2015
29. [Tensor-Matrix Products with a Compressed Sparse Tensor](http://glaros.dtc.umn.edu/gkhome/node/1177)
	, 5th Workshop on Irregular applications: Architectures and Algorithms, Supercomputing, 2015
30. [Optimizing Sparse Tensor Times Matrix on Multi-core and Many-Core Architectures](https://ieeexplore.ieee.org/document/7833300)
	 , 2016 6th Workshop on Irregular Applications: Architecture and Algorithms (IA3)
19. [A Unified Optimization Approach for Sparse Tensor Operations on GPUs](https://par.nsf.gov/servlets/purl/10049150)
	, 2017 IEEE International Conference on Cluster Computing (CLUSTER), Sept 2017
21. [Tensaurus: A Versatile Accelerator for Mixed Sparse-Dense Tensor Computation](https://www.csl.cornell.edu/~zhiruz/pdfs/tensaurus-hpca2020.pdf)
	2020 IEEE International Symposium on High Performance Computer Architecture (HPCA)
22. [The Surprisingly ParalleL spArse Tensor Toolkit (SPLATT)](https://github.com/ShadenSmith/splatt)
23. [Sparta: High-Performance, Element-Wise Sparse Tensor Contraction on Heterogeneous Memory](http://pasalabs.org/papers/2021/ppopp21_sparta.pdf)
	Proceedings of the 26th ACM SIGPLAN Symposium on Principles and Practice of Parallel Programming 2021
24. [Efficient MATLAB computations with sparse and factored tensors](https://old-www.sandia.gov/~tgkolda/pubs/pubfiles/SAND2006-7592.pdf)
25. [A High-Performance Sparse Tensor Algebra Compiler in sMulti-Level IR](https://arxiv.org/pdf/2102.05187.pdf)
26. [The Tensor Algebra Compiler](https://dl.acm.org/doi/pdf/10.1145/3133901)
27. [Sparse Tensor Algebra Compilation (thesis)](http://fredrikbk.com/publications/kjolstad-thesis.pdf)
28. [High performance rearrangement and multiplication routines for sparse tensor arihtmetic](https://arxiv.org/pdf/1802.02619.pdf)

### Matrix
1. [On the Representation and Multiplication of Hypersparse Matrices](https://crd.lbl.gov/assets/pubs_presos/hypersparse-ipdps08.pdf)
2. [Bridging the Gap between Deep Learning and Sparse Matrix Format Selection](https://people.engr.ncsu.edu/xshen5/Publications/ppopp18.pdf)
3. [Load-balancing Sparse Matrix Vector Product Kernels on GPUs](https://dl.acm.org/doi/pdf/10.1145/3380930)
4. [OuterSPACE: An Outer Product based Sparse Matrix Multiplication Accelerator](http://tnm.engin.umich.edu/wp-content/uploads/sites/353/2018/10/2018.02.outerspace.pdf)

### Graph
1. [Mathematical Foundations of the GraphBLAS](https://arxiv.org/pdf/1606.05790.pdf)
	IEEE High Performance Extreme Computing (HPEC) conference 2016
2. [GraphBLAST: A High-Performance Linear Algebra-based Graph Framework on the GPU](https://arxiv.org/pdf/1908.01407.pdf)
	2019
3. [LAGraph: Linear Algebra, Network Analysis Libraries, and the Study of Graph Algorithms](https://arxiv.org/pdf/2104.01661.pdf)
    2021, GrAPL (Workshop on Graphs, Architectures, Programming, and Learning) at IPDPS