# Test Cases – Todo Web App

| ID   | Test Case Description                 | Steps                                                                 | Expected Result |
|------|--------------------------------------|-----------------------------------------------------------------------|----------------|
| TC01 | Add a new todo                        | Enter valid todo text, click Add                                      | Todo appears in the list |
| TC02 | Add empty todo                        | Click Add with empty input                                            | Error: "Todo cannot be empty" |
| TC03 | Edit todo                             | Click Edit on a todo, change text, save                                | Text updates successfully |
| TC04 | Delete todo                           | Click Delete on a todo                                                | Todo is removed from list |
| TC05 | Mark as completed                     | Click checkbox on todo                                                | Todo appears crossed out / marked complete |
| TC06 | Persistence check                      | Add todo, reload page                                                 | Todo still appears (data saved) |
| TC07 | Multiple todos                         | Add several todos                                                     | All todos appear in correct order |
| TC08 | Responsiveness                          | Open app on mobile / tablet                                           | Layout adjusts correctly |
