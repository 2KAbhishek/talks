# Test-Driven Development (TDD) Guide 🧪

Master the art of building robust software through test-first development

---

## Use Cases 🛠️

1. **Specification Clarity:** Clarify requirements by writing tests first.
2. **Code Quality:** Improve code quality with automated tests.
3. **Refactoring Confidence:** Safeguard against regressions during refactoring.
4. **Incremental Development:** Develop features incrementally, ensuring each part works as expected.
5. **Bug Prevention:** Catch bugs early in the development process.

---

## Red Green Refactor! 🔄

1. **Write Test:** Create a failing test that defines the desired behavior.
2. **Run Test:** Execute the test suite and watch it fail.
3. **Write Code:** Implement the minimum code required to make the test pass.
4. **Run Test Again:** Re-run the test suite to confirm the code change.
5. **Refactor:** Optimize and refactor the code while ensuring all tests still pass.
6. **Repeat:** Iterate on the process for each new feature or enhancement.

> _DEMO_

---

## Best Practices 💡

1. **Small, Focused Tests:** Write tests that focus on specific behaviors.
2. **Naming Conventions:** Use descriptive names for tests to enhance readability.
3. **Red-Green-Refactor Cycle:** Follow the TDD cycle religiously.
4. **Test Coverage:** Strive for comprehensive test coverage to catch edge cases.
5. **Keep Tests Fast:** Ensure tests run quickly to maintain developer productivity.

---

## Tips for Success 🚨

- **Test Isolation:** Ensure tests are independent of each other.
- **Mocking and Stubbing:** Use mocking and stubbing to isolate dependencies.
- **Feedback Loop:** Maintain a tight feedback loop by running tests frequently.
- **Pair Programming:** Consider pair programming for collaborative TDD sessions.

Most Importantly: **Practice!**

---

## References 📚

- Your test framework documentation
- [Katas](https://kata-log.rocks/tdd)
- [The Art of Unit Testing by Roy Osherove](https://www.manning.com/books/the-art-of-unit-testing)
- [Clean Code: A Handbook of Agile Software Craftsmanship by Robert C. Martin](https://www.goodreads.com/book/show/3735293-clean-code)

---

## Thanks 🙏

---

## fizzbuzz

### Test Code

```javascript
describe('fizzbuzz', () => {
  const fizzbuzz = require('../src/fizzbuzz');
  it('returns the argument if its not divisible by 3 or 5', async () => {
    expect(fizzbuzz(4)).toBe(4);
  });

  it('returns fizz if the argument is divisible by 3', async () => {
    expect(fizzbuzz(6)).toBe('fizz');
  });

  it('returns buzz if the argument is divisible by 5', async () => {
    expect(fizzbuzz(10)).toBe('buzz');
  });

  it('returns fizzbuzz if argument is divisible by 3 and 5', async () => {
    expect(fizzbuzz(30)).toBe('fizzbuzz');
  });
});
```

### Implementation

```javascript
function fizzbuzz(num) {
  if (num % 15 == 0) return 'fizzbuzz';
  if (num % 5 == 0) return 'buzz';
  if (num % 3 == 0) return 'fizz';
  return num;
}

module.exports = fizzbuzz;
```

---

## validatePassword

### Test Code

```javascript
describe('validatePassword', () => {
  const validatePassword = require('../src/validatePassword');

  it('returns false if password length is less than 8', async () => {
    expect(validatePassword('pass')).toEqual(false);
  });

  it('returns true if password length is more than 8, contains a number and a uppercase char', async () => {
    expect(validatePassword('Password12')).toEqual(true);
  });

  it('returns false if password does not contain at least one number', async () => {
    expect(validatePassword('password')).toEqual(false);
  });

  it('returns false if password does not contain at least one uppercase char', async () => {
    expect(validatePassword('password12')).toEqual(false);
  });
});
```

### Implementation

```javascript
function validatePassword(password) {
  const isValidLength = password.length >= 8;
  const hasNumber = /[0-9]/g.test(password);
  const hasUppercase = /[A-Z]/g.test(password);
  return isValidLength && hasNumber && hasUppercase;
}

module.exports = validatePassword;
```
