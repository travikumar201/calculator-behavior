# Multiplication

Scenario: Zero value multiplication

    Given I have a working calculator

    When I enter "number 1"
    and I press "*" button
    and I enter "number2"
    and I press "=" button
    and if any one of the numbers is zero

    Then I get "0" as the result
