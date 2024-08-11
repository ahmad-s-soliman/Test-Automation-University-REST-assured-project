# What API is used for the samples?
The code samples invoke the [Zippopotam.us API](https://api.zippopotam.us/).

In those cases where the actual API could not be used (it doesn't support HTTP operations other than GET, plus it doesn't have an option to return XML response bodies), calls have been mocked using [WireMock](https://wiremock.org/).

# In this course I got to learn the following:

 1. REST assured
 2. WireMock
 3. Hamcrest matchers: equalTo, hasItem, hasSize
 4. Check status code
 5. Check content type
 6. Logging request and response
 7. Data provider
 8. Request and response specification
 9. Working with xml responses
 10. Serialization and deserialization of java objects
