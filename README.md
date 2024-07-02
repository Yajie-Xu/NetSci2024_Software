# Software Tools for Network Science
A NetSci 2024 Satellite Workshop <br>
18 June 2024, Québec City, Canada <br>

Website Link: https://netsci.nascol.net/school

School / Workshop
Tutorial on cross-package network analysis in Python using igraph, NetworkX and graph-tool.

Time and place
Location: room 2104AB

Time: 14:30 to 18:00 with a coffee break between 16:00–16:30.

Instructors:
- [Tamás Nepusz](https://github.com/ntamas/)
- [Tiago Peixoto](https://skewed.de/tiago/)
- [Matt Schwennesen](https://www.schwennesen.org/)

Content
The workshop will be roughly broken up into three parts, one for each library.

NetworkX
Time: 14:30 – 15:30

NetworkX is a pure-python library for network analysis which aims to be both easy to install and easy to use while also being feature rich. Currently the library features around 400 network analysis algorithms ranging from classics like shortest path and spanning trees to approximate algorithms for problems like graph isomorphism and the traveling salesperson problem. With the recent addition of a backend system, NetworkX is now capable of utilizing faster implementations of supported algorithms from other graph analysis libraries like Python GraphBLAS Algorithms and CuGraph. In this workshop, we’ll cover how to get started with NetworkX as well as topics like graph visualization, some classical algorithms, graph input/output, a network analysis case study and finally the new dispatching system.

Tutorial material can be found here.

graph-tool
Time: 15:30 to 17:00, with coffee break between 16:00 – 16:30

In this interactive workshop we will briefly cover the basic and some of the more advanced functionalities of the graph-tool library. After an introduction, participants will be given some hands-on exercises, which will be discussed during the session.

To participate in the interactive session, please create an account at:

https://hub.skewed.de

and open the notebook from here.

Graph-tool is an efficient Python module for manipulation and statistical analysis of graphs and networks.

The core data structures and algorithms are implemented in C++, making extensive use of template metaprogramming, based heavily on the Boost Graph Library. This confers it a level of performance that is comparable (both in memory usage and computation time) to that of a pure C/C++ library.

graph-tool can be orders of magnitude faster than pure Python alternatives, and therefore it is specially suited for large-scale network analysis.

Some of the unique functionalities of graph-tool include:

Comprehensive framework for inferential community detection, build upon statistically principled approaches that avoid overfitting and are interpretable.

Support for network reconstruction from dynamics.

Support for uncertainty quantification in network data.

Support for OpenMP shared memory parallelism for several algorithms.

High-quality network visualization, both static and interactive, supporting animations and matplotlib integration.

Filtered graphs, i.e. graphs where nodes and edges are temporarily masked. These are first class citizens in the library, and are accepted by every function. Due to the use of C++ template metaprogramming, this functionality comes at no performance cost when filtering is not being used.

Efficient and fully documented binary format for network files.

Integration with the Netzschleuder network data repository, enabling easy loading of network data.

Support for writing custom C++ extensions.

igraph
Time: 17:00 – 18:00

An IPython notebook containing the material of the tutorial is available on Google Colab here. You can also download a copy of the notebook here. The Zachary karate club network used in the tutorial is available here.

igraph is a high-performance general-purpose library for complex network analysis, designed to be used from high-level languages like R, Python and Mathematica. The core library and data structures are implemented in C and C++, making it suitable for the analysis of large networks consisting of millions of vertices and even billions of edges given enough RAM.

In this workshop, we will cover the basics of getting started with igraph, including the essential graph generation and graph analysis methods and the attribute handling system. We will cover the creation of publication-quality plots using Cairo or Matplotlib as backends, graph input/output, in-memory conversion to other popular tools such as NetworkX and graph-tool, and a few popular algoritms used in network science like community detection algorithms and motif search.
