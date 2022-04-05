# Simple Pytest Example

This is the code for my video tutorial for getting started with Pytest.

* [Pytest Documentation](https://docs.pytest.org/en/6.2.x/getting-started.html#getstarted)
* [unittest.mock Documentation](https://docs.python.org/3/library/unittest.mock.html)

### Install Pytest

```bash
pip install pytest
```

### Run the tests

```bash
pytest
```

### Run a specific file

```bash
pytest test_shopping_cart.py
```

### Run a specific test

```bash
pytest test_shopping_cart.py::test_can_get_total_price
```
