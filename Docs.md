
# Angular
    [https://ngrefs.com/] <- examples of angular configurations (not only typescript, styles too and more)

# Debugging Angular (ng probe)

    [http://www.damirscorner.com/blog/posts/20190719-InspectingAngularAppsFromBrowserConsole.html]
    [https://blog.angularindepth.com/everything-you-need-to-know-about-debugging-angular-applications-d308ed8a51b4]


# Testing with Jasmine
    [https://codecraft.tv/courses/angular/unit-testing/angular-test-bed/]

    ### Getting Started
    [https://dev.to/mustapha/angular-unit-testing-101-with-examples-6mc]
    [https://medium.com/frontend-fun/angular-unit-testing-jasmine-karma-step-by-step-e3376d110ab4]
    [https://scotch.io/tutorials/testing-angular-with-hasmine-and-karma-part-1]
    [https://codecraft.tv/courses/angular/unit-testing/jasmine-and-karma/]
    [https://codecraft.tv/courses/angular/unit-testing/classes-and-pipes]

    ### Overriding, spying
    [https://angular-2-training-book.rangle.io/testing/components/injecting-dependencies/overriding]
    [https://www.arroyolabs.com/2017/04/angular-2-unit-test-mocks-stubs/]
    [https://itnext.io/angular-testing-module-wrap-mock-test-26dd8d590d35]
    [https://blog.angularindepth.com/testing-and-faking-angular-dependencies-886495057121] <- Tree Shakable Dependencies
    
    ### Reference
    [https://jasmine.github.io/api] <- reference for matchers etc.

## Testing NgRx

    https://ngrx.io/docs <- what is ngrx
    https://christianlydemann.com/the-comlpete-guide-to-ngrx-testing


# E2E Testing

## Cypress
    [https://testautomationu.applitools.com/cypress-tutorial/]

    1. [https://www.cypress.io/blog/2018/04/02/sliding-down-the-testing-pyramid/]
    2. [https://docs.cypress.io/guides/core-concepts/introduction-to-cypress.html]
    3. [https://docs.cypress.io/guides/references/best-practices.html]
    4. [https://example.cypress.io/]
    5. [https://jonnyreeves.co.uk/2015/using-chai-with-typescript-and-mocha/]
    6. [https://docs.cypress.io/guides/references/bundled-tools.html#Chai-jQuery]
        6.1 [https://www.chaijs.com/plugins/chai-jquery]
        6.2 [https://www.chaijs.com/plugins/chai-dom]
        6.3 [https://www.chaijs.com/plugins/sinon-chai]
        6.4 [https://mochajs.org/#assertions]

    ### Terms:  
    Mocha runs Chai
    BDD Assertions
    should vs expect
    ng probe
    Stubs  
    Spies  
    Clocks  
    Chainers, Subjects, 
    Laziness and timeouts
    Cucumber


## Protractor

    [https://coryrylan.com/blog/introduction-to-e2e-testing-with-the-angular-cli-and-protractor]

# Observables in general

    [https://medium.com/@luukgruijs/understanding-creating-and-subscribing-to-observables-in-angular-426dbf0b04a3]
    [https://medium.com/@benlesh/hot-vs-cold-observables-f8094ed53339]
    [https://medium.com/@benlesh/learning-observable-by-building-observable-d5da57405d87]

    ### Error Handling
    [https://blog.angular-university.io/rxjs-error-handling]

    ### Operators
    [https://stackoverflow.com/questions/43101064/debounce-without-initial-delay]

    ### Stream redirection
    [https://rangle.io/blog/thinking-in-nested-streams-with-rxjs]
    [https://medium.com/@shairez/a-super-ninja-trick-to-learn-rxjss-switchmap-mergemap-concatmap-and-exhaustmap-forever-88e178a75f1b]
    [https://www.learnrxjs.io/operators/combination/]


    ### Manuals
    [https://xgrommx.github.io/rx-book] <- (4.0)

# Testing Observables
## Group 1
    [https://netbasal.com/testing-observables-in-angular-a2dbbfaf5329]
    [https://dev.to/mokkapps/how-i-write-marble-tests-for-rxjs-observables-in-angular-4l0k]

    [https://github.com/ReactiveX/rxjs/blob/master/docs_app/content/guide/testing/marble-testing.md]
    [https://medium.com/@bencabanes/marble-testing-observable-introduction-1f5ad39231c]

    [https://itnext.io/finding-about-rxjs-marble-testing-and-the-testscheduler-b23c6bdf6b49]

    # RTFM is an initialism for the expression "read the fucking manual".
    [https://blog.angularindepth.com/how-to-test-observables-a00038c7faad]
    [https://blog.angularindepth.com/rxjs-marble-testing-rtfm-a9a6cd3db758]
    [https://gbksoft.com/blog/angular-marble-testing-a-brief-introduction/]

## Group 2

    [https://stackoverflow.com/questions/48328292/unit-testing-value-of-observable-returned-from-service-using-async-pipe]

    RxJS Testing Marble Diagrams
    [https://rxjs-dev.firebaseapp.com/guide/testing/marble-testing]
    [https://angular.io/guide/testing]

    Examples
    [https://stackblitz.com/edit/jasmine-marbles-testing]
    [https://github.com/synapse-wireless-labs/jasmine-marbles/blob/master/spec]

        marble scheduler injector
        [https://gist.github.com/pavel-agarkov/9e7badefd14b725ca7867a25774d7a0e]

## Life



# Terms

TestScheduler  
toBeObservable()  
expectObservable() looks old