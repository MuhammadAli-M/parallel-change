# parallel-change

[Parallel Change](https://kata-log.rocks/parallel-change-kata) Coding Kata.
It aims to practice refactoring.

# Project Layout

`app` directory src code
`tests` directory for test files

## Installation

Create virtual environment...

```bash
python3 -m venv .venv
```

...activate it:

```bash
source .venv/bin/activate
```

...and install requirements listed in requirements.txt file:

```shell
pip3 install -r requirements.txt
```

## Run tests with pytest

- run : ```python3 -m pytest tests/```
- run tests with coverage: ```python3 -m pytest --cov=app tests/```
- run tests for changed code using
  testmon: ```ptw --runner "pytest --picked --testmon"```

### Resources

- <http://pythontesting.net/framework/pytest/pytest-introduction/>
- <https://docs.pytest.org/en/latest/getting-started.html>

### run from docker

```shell
'./docker_test.sh'
```
