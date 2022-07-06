Genome Assembly using deBruijn Graph
====================================
Sequencing technologies can read only a small amount of bases at a time and to read the whole genome, it takes a lot of attempts. As a result, we get subsets of DNA in millions. The process of reconstructing the original sequence from the subset sequences is known as genome assembly. In this project I have used the deBruijn Graph for genome assembly. It is based on traversing the gene graph built using Euler's path to reconstruct the original genome. I have used python for the implementation of deBruijn graph and Eulerian path traversal algorithm.

Directory Layout
================
The Genome Assembly directory structure looks as follows::

    E-commerce-Website-Django/
        |---deBruijn_Final.ipynb
        |--EL_PIC.docx
        |---EL_PIC.pptx
        |----readme.md

Extra
======
The Repository also contains power point presentation and report that expalain the algorithm for creating a deBruijn graph given subsets of a gene and the Eulerian algorithm for traversing the deBruijn graph and reconstructing the genome.
