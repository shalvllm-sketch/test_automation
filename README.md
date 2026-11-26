# Widget Test Runner (QA)

1. Download `widget_test_runner.html` and open it in Chrome (on the network/VPN that can reach the QA widget).
2. **A)** Upload the test sheet (.xlsx/.csv with columns `User query` and `Test Conversation ID`).
3. **B)** Click **Run all test cases**. Keep the tab open and visible.
4. **C)** Download the output file: every input column plus Conversation ID, Run result, Run time.

If the widget does not load from a double-clicked file, run `python3 -m http.server 8000` in this folder and open `http://localhost:8000/widget_test_runner.html`.
