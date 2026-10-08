# IS 218 Test 1 — Python Calculator

## Student Information
**Name:** Zeel Patel  
**Course:** IS 218 — Introduction to Professional Programming

## Project Description
This project is a simple Python calculator created for IS 218 Test 1. The calculator supports two basic operations: addition and subtraction. I used pytest to test both functions and GitHub to manage my branches, commits, and issues.

## Environment Setup

This project uses Python 3.13 and pytest.

### 1. Create a Virtual Environment

Open PowerShell in the project directory and run:

```powershell
py -3.13 -m venv .venv
```

### 2. Activate the Virtual Environment

```powershell
.\.venv\Scripts\Activate.ps1
```

### 3. Install Dependencies

```powershell
python -m pip install -r requirements.txt
```

## Running Tests

To run the six student tests:

```powershell
python -m pytest tests -v
```

To run both the student tests and the provided acceptance checks:

```powershell
python -m pytest tests checks -v
```

**Test Results:** All 12 tests passed locally, including six student tests and six provided acceptance checks.

## GitHub Issues

I organized my project using four GitHub issues:

1. **Issue #1 — Python Setup:** https://github.com/Zeel153/is218_test1_official/issues/1
2. **Issue #2 — Addition:** https://github.com/Zeel153/is218_test1_official/issues/2
3. **Issue #3 — Subtraction:** https://github.com/Zeel153/is218_test1_official/issues/3
4. **Issue #4 — Delivery:** https://github.com/Zeel153/is218_test1_official/issues/4

Each task was completed using a separate Git branch and merged into the main branch.

## Test Assertion Explanation

One of my addition tests checks whether the calculator returns the correct result when adding two positive integers. For example, adding 2 and 3 should return 5. The assertion compares the actual result with the expected value. If the values match, the test passes; otherwise, pytest reports a failure.

## Conclusion

This assignment helped me practice creating a Python project, using a virtual environment, writing unit tests, and managing code with Git and GitHub. I also learned how to organize development tasks using issues and branches and verify my work through automated testing.