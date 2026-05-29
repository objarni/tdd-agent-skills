---
name: tdd-next-test
description: Load TDD skill, work on next unticked test in TESTLIST.md (red, green phases), then tick it off
---

# TDD Next Test Workflow

## Load TDD Skill

First, load the foundational TDD skill:

> Use the TDD skill to guide the overall approach and principles.

## Workflow Steps

### 1. Read TESTLIST.md

- Examine TESTLIST.md to find the next test that is **not yet ticked** (indicated by `- [ ]` or similar unchecked markers)
- This is the test you'll work on

### 2. Red Phase

- Write ONE failing test that describes the desired behavior
- Ensure it fails for the RIGHT reason (not syntax/import errors)
- Run the test to confirm it fails
- Report the failure

### 3. Green Phase

- Write MINIMAL code to make the test pass
- Only implement what's needed for this specific test
- Run tests to confirm they pass
- Report the passing state

### 4. Tick Off the Test

- Update TESTLIST.md to mark the completed test as ticked (`- [x]`)
- Commit or note the completion

## Key Principles

- **One test at a time** - complete the red-green cycle for the current test before moving to the next
- **Minimal implementation** - only code needed to pass the current test
- **Visible progress** - confirm each phase with test output
- **Clear communication** - report the test name, failure reason, and implementation before marking complete

## Continue Conversation

Please proceed with finding the next unticked test in TESTLIST.md and begin the red-green cycle.
