# Ruby: Phone Number

Write a program that cleans up user-entered phone numbers so that they can be sent SMS messages.

The rules are as follows:

- If the phone number is less than 10 digits assume that it is bad
  number
- If the phone number is 10 digits assume that it is good
- If the phone number is 11 digits and the first number is 1, trim the 1
  and use the last 10 digits
- If the phone number is 11 digits and the first number is not 1, then
  it is a bad number
- If the phone number is more than 11 digits assume that it is a bad
  number

We've provided tests, now make them pass.

Hint: Only make one test pass at a time. Disable the others, then flip
each on in turn after you get the current failing one to pass.

The tests use the Minitest testing framework. To install it run the command:

    gem install minitest

Run the tests with the `ruby` command:

    ruby phone_number_test.rb

## Resources

If you have never used Minitest, check out [Intro to TDD][tdd] tutorial from Jumpstart Lab.

[tdd]: http://tutorials.jumpstartlab.com/topics/testing/intro-to-tdd.html

## Source

Event Manager by JumpstartLab [http://tutorials.jumpstartlab.com/projects/eventmanager.html](http://tutorials.jumpstartlab.com/projects/eventmanager.html)

This exercise is from the [Ruby][ruby] track on [Exercism][exercism]

[exercism]: http://exercism.io
[ruby]: http://exercism.io/languages/ruby



