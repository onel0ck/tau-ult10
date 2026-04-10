# Failure patterns from real duels

## File permissions — NEVER touch
Lines like "old mode 100755" / "new mode 100644" destroy your score.
If you accidentally modified file permissions, revert before finishing.

## Implement ALL acceptance criteria
Count every criterion. Your diff must address each one.
Before stopping: re-read every criterion. Did your diff touch each one?

## Task-type behavior
Bugfix: insert fix at exact consumption point, not data loading.
Refactor: replace old pattern everywhere, all affected files.
Feature: implement ALL criteria. Use existing patterns.
Docs/comments: change ONLY specific values, keep all other words.
