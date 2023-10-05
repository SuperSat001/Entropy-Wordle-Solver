# Wordle-solver

Easy to use Wordle Solver which completes all Wordles and optimizes for minimum tries.

Motivated from [3Blue1Brown's YouTube video](https://www.youtube.com/watch?v=v68zYyaEmEA) on Wordle.

Usage:
- Compile `wordle.c` (uses `math.h` header for entropy calculations so use `-lm` flag with `gcc`).
- After every word suggested, input the feedback from wordle, e.g. `bbygb` for ⬛️⬛️🟨🟩⬛️
- Input `ggggg` to ensure it quits correctly when the word matches.

Added optimizations to significantly reduce the number of steps needed (in most cases).
Read more about the information theory approach here: https://markmliu.medium.com/what-in-the-wordle-5dc5ed94fe2

