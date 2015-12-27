# JavaScript Koans - koans to learn JavaScript (the good bits)
This repo contains a bunch of failing tests, Find them in /spec.

Basic requirements:

* Make the following tests pass:
  - [ ] Expects
  - [ ] Arrays
  - [ ] Functions
  - [ ] Objects

Extra credit:

- [ ] Make the rest of the tests pass.

You shouldn't need to write any Jasmine code, but if you'd like to know more, check out [their docs](http://pivotal.github.com/jasmine/).

## Resources for code quality:

* [http://jsbeautifier.org/](http://jsbeautifier.org/)
* [http://www.jshint.com/](http://www.jshint.com/)

이 repo 의 대부분은 David Laing 에 의해 작성됐습니다. 원본 Readme 는 다음과 같습니다.

# The Original Readme
Based on Edgecase's fantastic 
[Ruby koans](http://github.com/edgecase/ruby_koans), the goal of the
Javascript koans is to teach you Javascript programming through
testing.

When you first run the koans, you'll be presented with a runtime error and a
stack trace indicating where the error occurred. Your goal is to make the
error go away. As you fix each error, you should learn something about the
Javascript language and functional programming in general.

Your journey towards Javascript enlightenment starts in the koans/AboutExpects.js file. These
koans will be very simple, so don't overthink them! As you progress through
more koans, more and more Javascript syntax will be introduced which will allow
you to solve more complicated problems and use more advanced techniques.

## Running the Koans
Simply navigate to the Javascript Koans folder using a file browser, and
double click on KoansRunnner.html. 

Any browser will do, but for the best results Firefox or Chrome is
recommended. More stack trace information shows up for javascript on these
browsers.

The first error will be in koans/AboutExpects.js. Fix the first test and
refresh the browser. Rinse and repeat until all tests turn green.

The test runner used is [Jasmine](http://jasmine.github.io/) with a customized report viewer.

### Changelog
*  v3 - Nov 2010  - Moved out of branch of functional-koans project, into own top level project
*  v2 - Sept 2010 - Second version based on jasmine (Thanks Greg Malcolm!)
*  v1 - July 2010 - First version based on jsTestDriver

### Acknowledgements
*  Dick Wall (the Java posse) - for bringing the idea of koans to my attention
*  Edgecase - for the great Ruby Koans
*  Douglas Crockford - for Javascript; the good bits

### [MIT Licensed](LICENSE)