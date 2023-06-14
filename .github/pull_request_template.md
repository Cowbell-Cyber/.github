## Jira
- [ ] Is Jira Ticket added in the title of PR?
- [ ] Is complete description is added to PR title?

## Checklist for merging
- [ ] If it is a core feature, I have added thorough tests.
- [ ] Will this be part of a product update? If yes, please write one phrase about this update in description

## Code formatting
- [ ] Ensure that proper naming conventions (Pascal, CamelCase etc.) have been followed. 
- [ ] Remove the commented code as this is always a blocker, while going through the code. 

## Error Handling and Logging
- [ ] Is error handling done the correct way?
- [ ] Should any logging or debugging information be added or removed?
- [ ] Are error messages user-friendly?
- [ ] Are there enough log events and are they written in a way that allows for easy debugging?

## Testing and Testability
- [ ] Is it tested locally?
- [ ] Does it have enough automated tests (unit/integration/system tests)?
- [ ] Do the existing tests reasonably cover the code change?
- [ ] Is there any code wrapped under the feature flag?

## Dependencies
- [ ] If this change requires updates outside of the code, like updating the documentation, configuration, readme files, was this done?
- [ ] Might this change have any ramifications for other parts of the system, backward compatibility?

## Security and Data Privacy
- [ ] Does this code open the software for security vulnerabilities?
- [ ] Is data retrieved from external APIs or libraries checked accordingly?

## Performance
- [ ] Do you think this code change will impact system performance in a negative way?
