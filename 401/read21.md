# Tasks and the back stack


## What are Tasks and Back Stacks?

- A task is a stack of activities.
- These activites are arranged in a stack -- the back stack -- in the order in which each activity is opened.


## Lifcycle

- When act A start Act B, Act A is stopped, but the system retains its state. If the user uses the back or gesture while in activity b, act a resumes with its state restored.
- If the user presses or gesture Back, the current activity is popped from the stack and destroyed.
- Activities can be instantiated multiple times, even from other tasks.

## Manage Tasks

- The way android manages tasks and the back stack is by placing all activites started in succession in the same task and in a last in, first out stack. You can modify these within the manifest.

## Handle Affinities

- These indicate which task an activity prefers to belong to.

## Shared Preferences

- If you have a small collection of key-values that youd like to save, you should us the `sharedPreferences` APIs.
- Each file is managed by the frameworkd and can be private or shared.
- The SharedPreferences APIs are for reading and writing key-value pairs, and you should not confuse them with the Preference APIs, which help you build a user interface for your app settings

## Resources/Citations

---

- [Tasks and the back stack](https://developer.android.com/guide/components/activities/tasks-and-back-stack)
- [Shared Preferences](https://developer.android.com/training/data-storage/shared-preferences)
