# Voiceover (iOS 14.6)
Understand the core gestures for navigating VoiceOver on iOS with the [mobile testing guide Android & iOS from The Paciello Group](https://www.tpgi.com/mobile-accessibility/).

## Screen reader tests
- `Ensure the screen readers output matches the visual output of all headings`
- `Ensure the screen readers output matches the visual output of all links (as a minimum)`
- `Ensure the screen readers output matches the visual output of all list elements`
- `Ensure the screen readers output the first 2 rows of a table and announces the columns`
- `Ensure the screen readers output every visual error message`
- `Ensure the screen readers output all significant page activity (ajax spinner icon etc)`
- `Ensure the screen readers output a controls role and behaviour (open/close)`

## Add the accessibility shortcut
1.	Enabled this by going to **Settings** / **Accessibility** / **Accessibility Shortcut**
2.	Select **VoiceOver**

> The accessibility shortcut makes testing a lot quicker and easier as you don't have to go into settings each time to switch VoiceOver on and off.

## Add the Rotor actions
1.	Enabled these by going to **Settings** / **Accessibility** / **VoiceOver** / **Rotor**
2.	Select **Headings**, **Links**, **Form Controls**, **Tables**, **Lists**, **Landmarks**

> The Rotor is a virtual control built into VoiceOver. It allows you to select how you navigate through a dial format that lists marked-up elements on screen. It works with web content as well as native apps

## General
1.	Open Safari
2.	Go to the testing URL
3.	Turn VoiceOver on by triple clicking the home button
4.	Turn VoiceOver off by triple clicking the home button when testing has finished

## Test Headings
1.	Select from the Rotor **Headings**
2.	Swipe through the page headings
3.	TEST : `Ensure the screen readers output matches the visual output of all headings`

## Test Links
1.	Select from the Rotor **Links**
2.	Swipe through the page links
3.	TEST : `Ensure the screen readers output matches the visual output of all links (as a minimum)`

## Test Lists

1.	Select from the Rotor **Lists**
2.	Swipe through the page lists
3.	TEST : `Ensure the screen readers output matches the visual output of all list elements`

## Test Tables

~ ongoing
