# Hello World OJ

![Judge Result](./badge.svg)

A fork-friendly sample online judge problem repository using GitHub Actions.

## Problem
Print the following line exactly:

```text
Hello, World!
```

## How to use
1. Fork this repository.
2. Edit `solution.cpp`.
3. Push to your fork.
4. Check the Actions run and the badge in this README.

## Results
This template distinguishes:
- `AC` Accepted
- `WA` Wrong Answer
- `TLE` Time Limit Exceeded
- `MLE` Memory Limit Exceeded
- `RE` Runtime Error
- `CE` Compile Error

## Tests
This template supports multiple test cases by placing matching files in `tests/`:

- `input1.txt` / `output1.txt`
- `input2.txt` / `output2.txt`
- ...

The workflow runs the submitted program once per input file.

## Limits
Default limits in the workflow:
- Time limit per test: 2 seconds
- Memory limit per test: 256 MB virtual address space

You can change these values in `.github/workflows/judge.yml`.
