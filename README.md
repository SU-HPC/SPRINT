# SPRINT

## Sparse Storage Formats

1. **COO**
- Mode Generic
- [Paper](https://old-www.sandia.gov/~tgkolda/pubs/pubfiles/SAND2006-7592.pdf)
- [Repo](https://github.com/hpcgarage/ParTI)

2. **HiCOO**
- Mode Generic
- [Paper](http://fruitfly1026.github.io/static/files/sc18-li.pdf)
- [Repo](https://github.com/hpcgarage/ParTI)

3. **F-COO**
- Mode Generic
- [Paper](https://par.nsf.gov/servlets/purl/10049150)
- [Repo](https://github.com/kobeliu85/mttkrp-gpu)

4. **CSF**
- Mode Generic
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

### Graph
1. [GraphBLAST](https://github.com/gunrock/graphblast)
2. [cuGRAPH](https://github.com/rapidsai/cugraph)

### Matrix

## Papers

### Tensor

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
11. [Scalable sparse tensor decompositions in distributed memory systems](https://hal.inria.fr/hal-01148202v2/document)
12. [High-performance parallel algorithms for the Tucker decomposition of higher order sparse tensors](https://hal.inria.fr/hal-01219316/document)
13. [HaTen2: Billion-scale Tensor Decompositions](https://www.cs.ucr.edu/~epapalex/papers/haten2_icde2015.pdf)
14. [SPLATT: Efficient and Parallel Sparse Tensor-Matrix Multiplication](https://conservancy.umn.edu/bitstream/handle/11299/215973/15-008.pdf;jsessionid=0DB8D6E0AE1089BFB9B6C410AA9F1A3F?sequence=1)
15. [Tensor-Matrix Products with a Compressed Sparse Tensor](https://dl.acm.org/doi/pdf/10.1145/2833179.2833183)
16. [Efficient and effective sparse tensor reordering](https://hal.inria.fr/hal-02306569/document)
17. [HiCOO: Hierarchical Storage of Sparse Tensors](http://fruitfly1026.github.io/static/files/sc18-li.pdf)
18. [An Eficient Mixed-Mode Representation of Sparse Tensors](https://par.nsf.gov/servlets/purl/10172913)
19. [A Unified Optimization Approach for Sparse Tensor Operations on GPUs](https://par.nsf.gov/servlets/purl/10049150)
20. [Tensor Decompositions and Applications](https://www.kolda.net/publication/TensorReview.pdf)
21. [Tensaurus: A Versatile Accelerator for Mixed Sparse-Dense Tensor Computation](https://www.csl.cornell.edu/~zhiruz/pdfs/tensaurus-hpca2020.pdf)
22. [The Surprisingly ParalleL spArse Tensor Toolkit (SPLATT)](https://github.com/ShadenSmith/splatt)
23. [OuterSPACE: An Outer Product based Sparse Matrix Multiplication Accelerator](http://tnm.engin.umich.edu/wp-content/uploads/sites/353/2018/10/2018.02.outerspace.pdf)
24. [Sparta: High-Performance, Element-Wise Sparse Tensor Contraction on Heterogeneous Memory](http://pasalabs.org/papers/2021/ppopp21_sparta.pdf)
25. [Efficient MATLAB computations with sparse and factored tensors](https://old-www.sandia.gov/~tgkolda/pubs/pubfiles/SAND2006-7592.pdf)
26. [A High-Performance Sparse Tensor Algebra Compiler in sMulti-Level IR](https://arxiv.org/pdf/2102.05187.pdf)

### Matrix
1. [On the Representation and Multiplication of Hypersparse Matrices](https://crd.lbl.gov/assets/pubs_presos/hypersparse-ipdps08.pdf)
2. [Bridging the Gap between Deep Learning and Sparse Matrix Format Selection](https://people.engr.ncsu.edu/xshen5/Publications/ppopp18.pdf)
