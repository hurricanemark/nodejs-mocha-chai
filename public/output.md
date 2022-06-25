## Funtional Tests Output

 npm start

> automated-testing-app@0.0.1 start /home/runner/boilerplate-mochachai
> node server.js

Listening on port 3000

Running Tests...


  Unit Tests

    Basic Assertions

      ✔ #isNull, #isNotNull

      ✔ #isDefined, #isUndefined

      ✔ #isOk, #isNotOk

      ✔ #isTrue, #isNotTrue

    Equality

      ✔ #equal, #notEqual

      ✔ #strictEqual, #notStrictEqual

      ✔ #deepEqual, #notDeepEqual

    Comparisons

      ✔ #isAbove, #isAtMost

      ✔ #isBelow, #isAtLeast

      ✔ #approximately

    Arrays

      ✔ #isArray, #isNotArray

      ✔ Array #include, #notInclude

    Strings

      ✔ #isString, #isNotString

      ✔ String #include, #notInclude

      ✔ #match, #notMatch

    Objects

      ✔ #property, #notProperty

      ✔ #typeOf, #notTypeOf

      ✔ #instanceOf, #notInstanceOf



  Functional Tests

    Integration tests with chai-http

      ✔ Test GET /hello with no name

      ✔ Test GET /hello with your name

      ✔ Send {surname: "Colombo"}

      ✔ Send {surname: "da Verrazzano"}


  Functional Tests with Zombie.js

    Headless browser

      ✔ should have a working "site" property

    "Famous Italian Explorers" form

      ✔ Submit the surname "Colombo" in the HTML form (256ms)

      ✔ Submit the surname "Vespucci" in the HTML form (358ms)


  25 passing (3s)

