# Python Week 7 Assignment: File I/O and CSV Processing

## Project Files
* **`my_notes.py`**: Demonstrates text file creation, appending, iterative line reading, and line counting.
* **`my_notes.txt`**: Generated text file storing the saved notes.
* **`hubs.csv`**: Source dataset containing learner names, hubs, and scores.
* **`report_builder.py`**: Safely reads CSV data, handles missing files, calculates pass/fail statistics, and outputs a summary report.
* **`report.txt`**: Generated summary report detailing learner counts and average scores.

## Reflection Question
**What would happen if you changed `"a"` to `"w"` in Question 1?**
Changing the mode from `"a"` (append) to `"w"` (write) would overwrite the entire contents of `my_notes.txt` instead of appending to it. Consequently, the first three notes written earlier in the script would be erased, and only the newly written note would remain in the file, reducing the final total line count to 1.