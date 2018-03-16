# Activities

An **activity** represents a screen that the user sees. Sometimes people refer to each screen as a presentation layer.

Here's the actual definition from the official [document](https://developer.android.com/reference/android/app/Activity.html): "*An activity is a single, focused thing that the user can do.*"

An app can have multiple screens. That means there can also be multiple activities, and they can be switched and interacted with one another during runtime.

Activities are switched and interacted through what's called the **lifecycle**.

## Activity Lifecycle

Let's imagine that a user is using your awesome app. He sees a notification from another app and decides to open it. When he's done checking out the other app, he switches back to your app. So how should your app respond to each different event/scenario that takes place?

Now it's time to familarize yourself with the **Activity lifecycle**!

![Activity Lifecycle](../images/activity_lifecycle.png)

### onCreate()

This method is run when the activity is created (when the app is opened).

It has an `@Override` statement to let the system know that we’re not trying to recreate the method. Essentially we’re just overriding what’s inside the method by adding some more code.