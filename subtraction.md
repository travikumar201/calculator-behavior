# Subtraction

Scenario: Subtraction yields an addition

    Given that the second number is negative

    When I enter "number1"
    And I press "-" button
    And I enter "number2"
    And I press "=" button

    Then I see that the result is added
