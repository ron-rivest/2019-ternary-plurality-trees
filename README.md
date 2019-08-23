# 2019-ternary-plurality-trees
Note on using ternary plurality trees as a voting method having an efficient audit.

The TPT voting method arranges ballots at the leaves of a ternary tree.
Each internal node computes a value (vote) that is the plurality vote of its
three children.  The value at the root is the winner of the contest.

An audit of a TPT contest outcome may require confirming that the relevant
plurality nodes have correct values.  In a typical case with only two candidates,
the relevant nodes constitute a binary tree that is a proper subset of the overall
ternary tree.
