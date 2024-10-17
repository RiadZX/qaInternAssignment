# QA Intern Assignment

## Things to Test as a QA

Functionality Testing:

- Test wide ranges of valid dates in all supported formats: think about all possible edge cases, leap-years, non-leap years, months with 28-31 days.
- Test invalid dates: again account for edge cases: leap years, invalid months, negative values, NaN.
- Testing boundaries: first/last days of each month, leap year dates.

UI Testing:

- Verify that the input field is clearly labeled + with placeholder.
- Test behavior with copy-pasting dates into the field.
- Ensure that the buttons work: clear/action buttons.
- Make sure that the output day is displayed properly.

Error Handling:

- Test if the system is robust and can handle all kinds of errors: invalid inputs.

Compatibility Testing:

- Make sure it works on different browsers: Chrome, Edge, Firefox, Safari.

## Improvements

Improve User Experience:

- Instead of alerts, you can have it show the day on the page itself.
- Real-time input validation: you can highlight the box red if the input is wrong.

Enhance Functionality:

- Add a calendar to choose the date rather than inputting the date as text.
- Add support for other date formats such as: MM:DD:YYYY, YYYY:MM:DD (RTL).

Improve Accessibility:

- High contrast colors.
- Keyboard navigation.
- ARIA attributed for users with screen users.

Add More Styling to the Page:

- Apply CSS to make the page look better
