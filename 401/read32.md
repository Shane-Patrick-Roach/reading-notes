# Android Intent Filters


## Purpose: Allowing Other Apps to Start Your Activity

- If your app can perform an action that might be useful from another app, your app should be prepared to respond to action requests by specifying the appropriate intent filter in your activity.
- For example, if you build a social app that can share messages or photos with the user's friends, you should support the ACTION_SEND intent


## What is an Intent?

- An intent is a messaging object you can use to request an action from another app component.

### Starting an activity

- An activity represents a single screen in an app. The intent describes the activity to start and carries any necessary data.

### Intent filters

- An intent filter is an expression in an apps manifest that specifies the type of intents that the componenet would lkke to recieve.
- For instance, by declaring an intent filter for an activity, you make it possible for other apps to directly start your activity with a certain kind of intent. 


## Resources/Citations

--- 

- [Intent filters](https://developer.android.com/guide/components/intents-filters)
