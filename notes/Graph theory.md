---
tags:
- 📋/🗺️ 
---

reminder of [[mathematical notation in markdown]]

### connected graph
#### Definition


- *Open Neighborhood* of $v$ in $G$: $N_{G}(v) = \{u$ | $uv \in E(G)\}$
- *Closed Neighborhood* of $v$ in $G$: $N_{G}[v] = N_{G}(v) \cup \{v\}$
- *Degree* of $v \in V(G)$: $deg_{G}(v) = |N_{G}(v)|$
- A graph $G$ is *regular* $\Leftrightarrow \forall v \in V(G), deg_{G}(v) =  r$
- A *path* $P_{n} = [v_{1}, ... v_{n}]$ where $E(P_{n}) = \{v_{i}v_{i+1}$ | $i = 1, ... n-1\}$
- *A graph is connected* $\Leftrightarrow \forall (u,v) \in V(G), \exists$ a *path* from $u$ to $v \subset G$
- A *simple graph* contains no *graph loops* or *multiple edges* between 2 nodes
- The *trivial graph* = 1 node + 0 edge

#### Theorem

 - $\sum_{v\in V(G)} deg(v) = 2|E(G)|$
	 - Corollary: the number of edges $v$ | $deg_{G}(v) = 2k+1 (k \in \mathbb{N})$ is even 
