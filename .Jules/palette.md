## 2024-05-22 - Feedback for Long-Running CLI Scripts
**Learning:** Users running data processing scripts often face a "frozen" terminal state with no indication of progress, leading to uncertainty about whether the process is working or hung.
**Action:** Always implement progress bars (like `txtProgressBar` in R or `tqdm` in Python) or periodic status messages for loops that perform network requests or heavy computations.
