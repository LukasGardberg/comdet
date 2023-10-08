Recently thought about the app "BeReal" and how each user is prompted to take a photo each day. If every user gets the prompt at the same time, the servers must get incredibly busy with photo uploads? I wonder what ways there are to mitigare this problem. Two initial ideas:

- Split up users by timezones. This seems relatively easy, as users which are in different timezenes are less likely to be friends, assuming that two users which are friends want to get their prompt at the same time.

- Split up users by friend groups. This seems to exactly be "community detection".

Algorithms:

- Louvian Method
- Girvan-Newman
- Label Propagation

Python libraries:

- [NetworkX](https://networkx.org/documentation/stable/)
	- Has some example datasets for testing!
- [igraph](https://python.igraph.org/en/stable/)