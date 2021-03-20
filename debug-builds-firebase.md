

TODO Title is too long and terrible 


https://firebase.google.com/docs/perf-mon/disable-sdk?platform=android


```groovy
android {
  // ...
  buildTypes {
    debug {
      FirebasePerformance {
        // Set this flag to 'false' to disable @AddTrace annotation processing and
        // automatic monitoring of HTTP/S network requests
        // for a specific build variant at compile time.
        instrumentationEnabled false
      }
    }
  }
}
```