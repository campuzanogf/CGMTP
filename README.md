#  The Clustered-Generalized Median Tour Problem

A repository with synthetic and real instances for the CGMTP

The CGMTP is an extension of the Generalized Median Tour Problem, where nodes are separated into disjoint clusters, each divided into subclusters. The nodes are connected through a two-level network structure of a primary tour, secondary tours, and assignments. The primary tour connects the clusters, visiting exactly one node per cluster, while the secondary tours connect the subclusters from the visited node by the primary tour. A secondary tour may visit one or more nodes within a subcluster, and the remaining nodes are assigned to a visited node of a secondary path within a subcluster. Therefore, the objective of the  CGMTP is to minimize the transportation costs of the two-level structure.

Comments within an instance's file start with /* and end with */ have to be ignored.

Currently, this repository only contains a modified version of the single-center instances from:

This repository contains the instances used for the paper "Modeling and Solving the Clustered Generalized Median Tour Problem1". Paredes-Belmar German, Miranda-Gonzalez Pablo, Obreque Carlos, Campuzano Giovanni, & Gutierrez-Jarpa Gabriel. DOI: 

You are kindly requested to cite this paper if these instances are relevant to your research.
