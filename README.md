AngularJS Test
=====================================

This is a test to try Angular Js using Play framework as the backend. It's based on the TO DO app shown as tutorial for Angular Js.

It integrates Jasmine via the [Sbt-Jasmine plugin](https://github.com/guardian/sbt-jasmine-plugin) so when you run *play test* it will run both Javascript and Play tests.
Not that the tests added are too useful (just there to ensure it works).

Angular templates are stored in the public folder, as they are managed by Angular itself. In this scenario Play acts as a simple backend, minimal UI defined via Scala templates. Good or bad, that depends on your taste :)

The AngularJs source is minimized via the default Play minimizer, that's why the file is located under 'app/assets/javascript'. Be aware that this requires you using DI with array notation.

Known Issues
=====================================
I couldn't manage to run the End to End tests via Jasmine, there are several issues that I couldn't solve. I believe the only way will be to use the Play Selenium test for that, using Selenium as described [in this blog](http://paulhammant.com/2012/04/09/testing-knockout-and-angular-with-selenium2/)


To improve
=====================================
- Make the app nice (a bit of css would be good)
- Integrate RequireJS to load the AngularJs controllers

Resources
=====================================
- http://docs.angularjs.org/
- http://angular-ui.github.com/


License (MIT License)
=====================================

Copyright (c) 2013 Pere Villega

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
