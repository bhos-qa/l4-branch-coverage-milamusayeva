# Coverage Analysis Research Findings from previous lesson
First of all I learned about sonarcloud and overall it's workflow, how it works and so on (as our previous task was adding quality gates and working with conditions). Morever, I used JaCoCo which was a free code coverage library for Java. Below I gave short information about each of the coverage types:

## Statement Coverage

- Statement coverage measures the percentage of executable code statements that have been executed during testing.
- It is a basic metric for code coverage analysis and provides a starting point for assessing the thoroughness of testing.
- Statement coverage is relatively easy to achieve but may not necessarily identify all code issues or corner cases.
- Achieving 100% statement coverage is a good practice but does not guarantee the absence of defects.
- It helps identify dead code (code that is never executed), which can be removed to simplify maintenance.

## Branch Coverage

- Branch coverage goes beyond statement coverage by assessing whether different paths within the code have been exercised.
- It is particularly valuable for identifying decision points and ensuring that both true and false branches are tested.
- Achieving high branch coverage helps uncover logical issues and boundary cases.
- However, it may not reveal issues related to complex interactions between branches or external dependencies.

## Predicate Coverage

- Predicate coverage is an advanced form of coverage analysis that evaluates the Boolean expressions (predicates) within code.
- It assesses whether all possible combinations of conditions and decisions have been tested.
- Achieving predicate coverage is challenging but valuable for detecting subtle logic errors.
- It helps ensure that the software handles all possible input scenarios, reducing the risk of unexpected behavior.
- Combining branch and predicate coverage provides a more comprehensive view of code behavior.
