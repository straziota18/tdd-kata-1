# tdd-kata-1
TDD Kata skeleton using Python

This project is a skeleton for a TDD workshop. The objective is to create a function that computes the current minimum score when given a complete or partial score sheet.
The workshop is meant for 2 persons that will in turn write new tests that cover all the scenarios. The tutor will force the students to go through the TDD iterations:
- Write test that fails
- Modify the tested function so that the test passes
- Refactor the tested function so that all previous tests pass

The requirements for this workshop are:
- Basic knowledge of the python programming language

The unit testing framework used is [unittest](https://docs.python.org/3/library/unittest.html)

# Recommended iterations are
- 1 frame with no pins knocked down
- 1 frame with some pins knocked down
- A list of "simple frames" (ie no spare nor strike) followed by a spare and then another simple frame
- A list of simple frames followed by a strike followed by a non strike nor spare frame
- A list of simple frames followed by a spare followed by a strike
- A list of simple frames followed by a strike followed by a spare
- A sequence of strikes
- A final complete score sheet

# Additional resources
Bowling scoring rules can be found [here](https://www.myactivesg.com/sports/bowling/how-to-play/bowling-rules/how-are-points-determined-in-bowling)
