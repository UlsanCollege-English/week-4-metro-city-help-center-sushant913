[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/KuuIFSwK)

# Weekly Coding #3 — Metro City Help Center

## Summary
This homework uses one connected story to practice stack and queue behavior in Python.

Metro City Help Center needs a small support system for recent staff actions, waiting citizens, request-note checks, and service-line processing.

## How to run
\`\`\`bash
pytest -q
\`\`\`

## Complexity
### \`ActionStack.pop\`
- Time: O(1)
- Why: Removing the last element from a list takes constant time because it directly accesses the end.

### \`RequestQueue.dequeue\`
- Time: O(1)
- Why: deque.popleft() removes from the front in constant time.

### \`is_note_balanced\`
- Time: O(n)
- Why: We check each character in the string once.

### \`process_request_line\`
- Time: O(n)
- Why: Each citizen is added and removed from the queue once.

## Edge-case checklist
- [x] empty action stack
- [x] empty request queue
- [x] empty string for \`is_note_balanced\`
- [x] note with no brackets
- [x] empty citizen list

## Assistance & sources
- AI used? (Y/N): Y
- What it helped with:
Helped me understand how stacks and queues work and how to implement the functions.
- Other sources:
Python documentation and class notes