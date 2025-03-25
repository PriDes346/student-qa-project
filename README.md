# Test Plan Notes

## Objective
As a student working on this project, my goal is to learn how to create a solid testing strategy that ensures the team delivers features that align with business objectives.

---

## Why Testing Matters
I am in the early stages of learning QA/Testing. I aim to start by focusing on foundational testing principles, including both functional and automated tests, to ensure our product meets expectations and drives company growth.

---

## Key Considerations

### Challenges
- **Lack of understanding**: Some developers are not fully convinced of the importance of unit tests. It's essential to demonstrate the value and long-term benefits of unit testing.
  
### Assumptions
- **Testing Approach**: We will begin with basic testing approaches, such as E2E, to validate the core functionalities. Automation will be progressively introduced to optimize the process.

---

## Key Metrics to Track

- **Bugs After 'Done' Status**: Aim for **0** bugs found after a story reaches 'Done' status. This indicates thorough testing.
  
- **Automation Quality Gates**: Ensure automated tests are reliable, minimizing false failures and enhancing test stability.

- **Time to Market**: Monitor feature delivery speed and avoid delays in regression testing that could impact the time to market.

---

## Testing Scope

### Functional Testing
- **Form Validation**: Ensure all mandatory fields are properly validated.
- **Navigation**: Check that the app’s navigation works as expected.
- **CRUD Operations**: Validate create, read, update, and delete functions.
- **Sorting**: Verify the correct sorting of data.
- **Visual Checks**: Ensure there are no broken images, overlaps, or UI anomalies.

### Performance & Security (To be defined)
- These areas will be explored later, and I will define performance benchmarks suitable for this project.

---

## Testing Approach

### When to Test

- **Exploratory Testing**: I will begin by exploring the application to understand its functionality and identify potential issues.
- **Regression Testing**: This will be scheduled according to the features being released, ensuring no critical regressions are introduced.

### How to Test

- **Automated Testing**: I will automate critical workflows and test cases early, but some parts will still require manual verification.
- **Manual Testing**: Edge cases and functionalities not suitable for automation will be tested manually.

---

## Tools Used

- **Python**: The primary language for test automation.
- **Pytest**: For writing and executing unit and integration tests.
- **Appium**: For automating mobile app testing.
- **Playwright**: For automating web UI tests.
- **Mailinator**: For testing email-related features.

---

## Next Steps

- **Unit Testing by Developers**: Developers will handle unit tests, and I will contribute to E2E test writing.
- **Tracking and Improving**: I will continuously track test results and refine the test plan as we progress.

---

### Conclusion

This test plan represents an evolving process as I continue to learn and apply QA principles. The objective is to improve both the quality of our product and the efficiency of our testing practices.
