# DSA Through an Industry Lens

A beginner-friendly session for MCA first-year students: **60 minutes in the classroom + 60 minutes of hands-on Python practice**.

## Run in your browser

| Notebook | Purpose | Launch |
|---|---|---|
| [Student lab](notebooks/DSA_Student_Lab.ipynb) | Exercises, starter code, hints and tests | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kshamesh/dsa-industry-lens/blob/main/notebooks/DSA_Student_Lab.ipynb) |
| [Instructor solutions](solutions/DSA_Instructor_Solutions.ipynb) | Worked solutions, complexity analysis and teaching notes | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kshamesh/dsa-industry-lens/blob/main/solutions/DSA_Instructor_Solutions.ipynb) |

Open a notebook using its Colab button, connect to a Python runtime, and save your own copy before editing. No third-party Python packages or data downloads are required. You can also download the notebooks and use Jupyter or VS Code with a Python 3 kernel.

**Students:** work through one exercise at a time. Replace each `raise NotImplementedError` with your implementation before running its tests; these starter errors are intentional. Avoid running all cells before completing the exercises.

**Instructors:** use the solutions notebook for live demonstrations. Both notebooks are public; the solutions are intended for instructor use and after-lab review.

## Learning goals

- Model industry-oriented problems using suitable data structures.
- Apply algorithms to practical examples.
- Improve a correct baseline by removing repeated work.
- Explain time and auxiliary-space complexity.
- Practice structured problem-solving and technical interview communication.
- Connect classroom concepts with industry expectations around correctness, testing, readability and trade-offs.

## Session outline

The classroom session introduces industry uses of data structures, a structured interview approach, complexity, optimization, two pointers and sliding windows.

The lab applies these ideas in Python:

| Minutes | Activity | Focus |
|---|---|---|
| 0–8 | Count course registrations | Dictionaries and frequency counting |
| 8–23 | Find two prices within a budget | Brute force, hash lookup, time/space trade-offs |
| 23–38 | Find a pair in sorted prices | Two pointers and correctness reasoning |
| 38–53 | Find the busiest consecutive hours | Fixed-size sliding window |
| 53–60 | Test and explain | Edge cases, complexity and interview communication |

For each problem: **clarify → trace an example → propose a baseline → optimize → code → test → explain complexity**.

These exercises are simplified teaching models. The instructor notebook includes worked explanations, common mistakes, boundary cases and deterministic comparisons against baseline solutions.
