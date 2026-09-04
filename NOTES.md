# Notes

- Rattanak wants a gradual Data Structures & Algorithms coding course for big-tech software engineering interviews.
- Default interview language: Python.
- Teaching loop: concise concept explanation, worked example, retrieval practice, coding problem, feedback.
- Do not create learning records for mere exposure; wait for evidence from recall, explanation, or solved code.
- Lesson 3 should reinforce Python syntax after Rattanak used the right duplicate-detection algorithm with JavaScript-like set syntax.
- Lessons 8-10 extend the course into stack, binary search, and intervals after the sliding-window unit.
- Each lesson should include four common LeetCode practice links matched to that lesson's pattern.
- Rattanak asked for a consolidated Python interview cheatsheet with essential syntax, common counting patterns, libraries, and helper functions.
- Rattanak is confused about sliding-window update timing: explain that the right-side item is included once per outer loop, and the while loop repairs or improves the window by removing left-side items. Longest problems usually update after repair; shortest problems often update inside the shrink loop before removal.
- The phrase "add value to the window state while window..." was too abstract for Rattanak. Prefer the entrance/exit mental model: right edge is the entrance, left edge is the exit, and state must match what is inside.
- Rattanak asked to expand the two-pointer lesson with harder problems and visuals: Container With Most Water, 3Sum, and Move Zeroes.
- Rattanak asked for a practice page with a question picker and a simple Python editor. Keep it static, localStorage-backed, and link to curated LeetCode problems rather than depending on a LeetCode API.
- System Design is a separate product/infrastructure interview module, not mixed into the DSA lesson sidebar.
- System Design practice should use a localStorage-backed requirements/API/architecture/tradeoff workspace rather than the Python editor.
- Prefer original, accessible HTML/CSS architecture diagrams and teach a repeatable delivery framework before case studies.
