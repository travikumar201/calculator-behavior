# Addition

Scenario: Result is too large to display (or overrunning the limits)

  Given I have a calculator that's turned on.

  When I enter "number1"
  And I press "+" button
  And I enter "number2"
  And I press "=" button
  And if the result length is greater than max display length
  
  Then I see the the result in terms of base 10
