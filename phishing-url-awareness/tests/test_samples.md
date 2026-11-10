
# Test Results

Python version used: Python 3.13.14
Operating system: Windows
Date: 2026-11-10

| # | Input | Expected result | Actual result | Pass/Fail |
|---|---|---|---|---|
| 1 | https://www.example.com/login | No listed warning signs | [PASS] |
| 2 | http://192.0.2.10/account | IP address + HTTP | [PASS] |
| 3 | http://example.com@sample.invalid/login | @ symbol + HTTP | [PASS] |
| 4 | https://a.b.c.d.e.example.invalid/path | Many hostname segments | [PASS] |
| 5 | https://xn--example.invalid/ | Punycode-style hostname | [PASS] |

## Notes

1. I learned how Python can inspect URL text.
2. I understood how different URL warning signs work.
3. I learned that no warning signs do not guarantee URL safety.
