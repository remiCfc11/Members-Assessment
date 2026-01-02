## Merge Alternatively

You are given two strings `word1` and `word2`. Merge the strings by adding letters in alternating order, starting with `word1`. If a string is longer than the other, append the additional letters onto the end of the merged string.

Return the merged string.

### Example 1:

Input: `word1 = "abc"`, `word2 = "pqr"`
Output: `"apbqcr"`

**Explanation:** The merged string will be merged as so:

```
word1:  a   b   c
word2:    p   q   r
merged: a p b q c r
```

### Example 2:

Input: `word1 = "ab"`, `word2 = "pqrs"`
Output: `"apbqrs"`

**Explanation:** Notice that as `word2` is longer, `"rs"` is appended to the end.


```
word1:  a   b 
word2:    p   q   r   s
merged: a p b q   r   s
```

### Example 3:

Input: `word1 = "abcd"`, `word2 = "pq"`
Output: `"apbqcd"`

**Explanation:** Notice that as `word1` is longer, `"cd"` is appended to the end.

```
word1:  a   b   c   d
word2:    p   q 
merged: a p b q c   d
```

### Constraints:

- `1 <= word1.length, word2.length <= 100`
- `word1` and `word2` consist of lowercase English letters.



## Instruction

The `solution.py` file in this directory contains a buggy solution to this problem. Your task is to find and fix the bug in the solution. Please do not rewrite the entire solution. Create a new file named `solution_fixed.py`, copy the existing code from `solution.py` into it, and then apply your fix there.
## GitHub Workflow

1. Fork this repository
2. Choose a problem
3. Implement your solution in your fork
4. Commit with a clear message
5. Open a Pull Request (PR) to this repository
6. Briefly explain your approach in the PR description


> Pull requests are for review only and will **not** be merged.

---

## Testing

- Test cases are not publicly available on the repo, make sure to test your work extensively

---

## Rules

- Work individually
- Do not copy solutions
- Use documentation responsibly
- Only PR submissions will be reviewed

---

## Evaluation Criteria

- Correctness
- Code readability
- Logical structure
- Edge case handling
- Adherence to instructions

---

Good luck,  
**The Programming club Team**
