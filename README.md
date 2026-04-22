# CS 561 Lab 3: Branch `feature/global-css-class`

## Branch Author
William Huang (William-HuangWY)

## Summary of Work Done in This Branch
This branch updates `style.css` by adding a set of global CSS utility classes used across the application, including focus styling, hidden elements, and disabled state handling.

In addition, this branch is used to demonstrate a **merge conflict scenario**, where overlapping changes to `style.css` are intentionally introduced to simulate conflict resolution during Git merging.

## Commits

| Commit ID | Commit Message | # Lines Changed |
| --------- | -------------- | --------------- |
| fe1c4cc83 | Update style.css with GLOBAL CSS CLASSES for a variety of elements | ~15 |
| (merge)   | Merge branch 'feature/global-css-class' into feature/global-css-class | - |
| (readme)  | Update README | - |

### Total Commits Made in this Branch: 3

### Merge Conflict Description
This branch is intentionally structured to create a merge conflict by modifying the same `style.css` file as another branch. The conflict occurs when merging overlapping changes to shared CSS variables and class definitions. The conflict is resolved manually by selecting and integrating the correct CSS rules to maintain consistent styling across the application.