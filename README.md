# A-search-with-DAM
This code is for a place-timed PN-based A* search for the efficient scheduling of resource allocation systems (RASs) with deadlock-attractor markings (DAMs), which are the markings whose corresponding states are destined to evolve into a deadlock. DAMs are collected incrementally during the search and are used to prevent the repeated exploitation of a larger number of states that correspond to them. This method behaves better in resource-scarce systems. It maintains the same optimal scheduling performance as the original PN-based A∗ search, while reducing the number of expanded states and the search effort.

The project is developed using Visual Studio 2022 with C# on the Windows platform.
