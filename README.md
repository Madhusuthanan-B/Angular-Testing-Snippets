# Angular Unit Testing Snippets for VSCode (Angular 2+)
-------------------

[![Version](https://vsmarketplacebadge.apphb.com/version/madhusuthanan.angular-unit-testing-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=madhusuthanan.angular-unit-testing-snippets)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/madhusuthanan.angular-unit-testing-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=madhusuthanan.angular-unit-testing-snippets)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating/madhusuthanan.angular-unit-testing-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=madhusuthanan.angular-unit-testing-snippets)

Visual Studio Code Angular Unit Testing Snippets in Jasmine

These snippets were created after observing that, these code blocks / mocks / techniques were used a lot while we write unit tests in angular.

If you want to learn angular unit testing. Please refer https://angular.io/guide/testing

## Usage
Type jat- to get the snippet intellisense. Press enter to select a snippet

### Available Snippets

| Snippet                             | Purpose                                                                                                                                 |
| ----------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| jat-component-basic                 | Unfold the unit test setup for component (Runs in isolation)                                                                            |
| jat-component-with-service-mock     | Component unit test setup with a sample mock service (Runs in isolation)                                                                |
| jat-mock-observable-success-service | Mock service which returns an observable, to use in useClass provider                                                                   |
| jat-suite                           | Generates a jasmine describe block  (Test suite)                                                                                        |
| jat-spec                            | Generates an it block (Test spec)                                                                                                       |
| jat-timer-spec                      | Generates a it block to test the methods which contains timers (SetTimeout, SetInterval etc)                                            |
| jat-use-value-provider              | Angular useValue provider to inject mock value as dependency instead of an injection token or injected service.                         |
| jat-use-class-provider              | Angular useClass provider to inject a mock class as dependency instead of an injection token or injected service.                       |
| jat-mock-router                     | Mock Class to use as a mock for the injected Router class (Has minimal methods like navigate, navigateByUrl etc. These can be extended) |
| jat-http-success-spec                     | Spec that makes use of angular HttpTestingController to test http requests |
| jat-http-error-spec                     | Spec that makes use of angular HttpTestingController to test http requests that may return error |
| jat-dispatch-event-spec                     | Spec that dispatches an event to simulate user interactions in unit tests |
| jat-before-each                     | Generates an empty before each block |
| jat-before-each-async                     | Creates an asynchronous before each block (Deprecated) |
| jat-before-each-wait-for-async                     | Creates an asynchronous before each block |
| jat-service-before-each                    | Creates a before each block for testing your service |
| jat-test-bed-inject                     | Utilizes TestBed to inject a service instance (From Angular 9) |
| jat-test-bed-get                     | Utilizes TestBed to inject a service instance (Before Angular 9) |
