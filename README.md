💡 Problem:
We have n chips, each can be moved ±2 with 0 cost or ±1 with cost = 1. Find the minimum cost to bring them all to the same position.

✅ Approach:

Moving ±2 keeps chips on the same parity (even/odd) at zero cost.

Only moves between odd and even positions cost 1.

Count chips on even positions and chips on odd positions.

Minimum cost = min(even_count, odd_count).
output
1
2
