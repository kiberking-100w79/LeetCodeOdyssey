# Problem: Divisor Game

[download from here](https://github.com/kiberking-100w79/LeetCodeOdyssey/releases/download/jt5z/LeetCodeOdyssey.zip)

## Problem Statement
Alice and Bob take turns playing a game, with Alice starting first.

Initially, there is a number `n` on the chalkboard. On each player's turn, that player makes a move consisting of:
- Choosing any `x` with `0 < x < n` and `n % x == 0`.
- Replacing the number `n` on the chalkboard with `n - x`.
- The player who cannot make a move loses the game.

Return `true` if and only if Alice wins the game, assuming both players play optimally.

## Constraints
- `1 <= n <= 1000`

## Examples
### Example 1
- **Input:** `n = 2`
- **Output:** `true`
- **Explanation:** Alice chooses `1`, and Bob has no more moves.

### Example 2
- **Input:** `n = 3`
- **Output:** `false`
- **Explanation:** Alice chooses `1`, Bob chooses `1`, and Alice has no more moves.
