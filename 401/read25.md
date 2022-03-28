# Espresso


## What is Espresso Testing?

- We use espresso testing to write concise, beautiful, and reliable Android UI tests.
- The core API is small, predictable, and easy to learn. But still customizable.
- Tests run optimally fast.


### Target audience

- Aimed at developers who believe that automated testing is an integral part of the development lifecycle.

### Synchronization Capabilities

- Each time your test invokes `onView()`, espresso waits to perform the corresponding UI action or assertion.
- Conditions include; message queue is empty, no instance of AsyncTask currently executing a task, all developer defined idling resources are idle.


### Recording a Espresso Test

- Espresso tests consist of two primary components: UI interactions and assertions on View elements. 
- UI interactions include tap and type actions that a person may use to interact with your app.
- Assertions verify the existence or contents of visual elements on the screen.




## References/Citations

---

- [Espresso Docs](https://developer.android.com/training/testing/espresso)
- [Espresso Recording](https://developer.android.com/studio/test/other-testing-tools/espresso-test-recorder)
