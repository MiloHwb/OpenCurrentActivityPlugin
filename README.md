Open Current Activity Android Studio / IntelliJ Plugin
====

A little plugin for Android development (Android Studio or IntelliJ).

Adds an action under **Navigate / Current Activity** (default shortcut: `Ctrl` `F10` on PC, `⌘` `F10` on Mac) that opens the class
corresponding to the currently shown Activity on the attached device or emulator.

Why?
----
To save a few seconds ;)

If your project contains lots of Activities and you can't always quickly remember their names, this is for you.

That's it!

How does it work?
----
By executing `adb shell dumpsys activity activities` and parsing the results.

