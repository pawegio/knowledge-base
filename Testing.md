# Testing

#### Test Doubles

* **Dummy** - objects are passed around but never actually used. Usually they are just used to fill parameter lists.
* **Fake** - objects actually have working implementations, but usually taks some shortcut which makes them not suitable for production (an in memory database is a good example).
* **Stubs** - provide canned answers to calls made during the test, usually not responding at all to anything outside  what's programmed in for the test. Stubs may also record information about calls, such as an email gateway stub that remembers the messages it 'sent', or maybe only how many messages it 'sent'.
* **Mocks** - objects pre-programmed with expectations which form a specification of the calls they are expected to receive.

*source: http://martinfowler.com/articles/mocksArentStubs.html*