![current WCAG version 2.1](https://img.shields.io/badge/current%20version-WCAG%202.1-%230a5470?style=flat)
# Screen Reader Tests
- Testing with [NVDA (Windows 10 v2020)](https://github.com/govau/accessibility/blob/main/NVDA-TESTING.md)
- Testing with [VoiceOver (iOS v14.6)](https://github.com/govau/accessibility/blob/main/VOICEOVER-TESTING.md)
- Testing with [TalkBack (Android v10, Android v11)](https://github.com/govau/accessibility/blob/main/TALKBACK-TESTING.md)
- Testing with [VoiceOver (macOS 11.1 Big Sur)](https://github.com/govau/accessibility/blob/main/VOICEOVER-MACOS-TESTING.md)

# WCAG Success Criteria Tests
The intention is to reduce the variance of testing for web accessibility between professionals and people who have an interest in accessibility. Agreeing on what constitutes a failure is the first step towards testing in a consistent way and having consistent results.

Portions of the tests are sourced from the [Deque University](https://dequeuniversity.com/) Introduction to WCAG Conformance Testing detailed methodology and Melbourne university responsibilities by project role.

## The Tests
* [All WCAG 2.1 AA tests](https://govau.github.io/accessibility/)

### Using the tests
Each test is written in a way which is clear to understand and straightforward to apply to web content. For example [accessibility guidance for font sizing](https://www.notion.so/5bf080c521c5486db8a4995cce275f1b?v=ec4067a1e3d146319b47b909b501388a) contains the following test:
- `text smaller than 18.6px and bold has a minimum contrast ratio of 4.5:1 with the background colour`
- `text at least 18.6px and bold has a minimum contrast ratio of 3:1 with the background colour`
- `text smaller than 24px and not bold has a minimum contrast ratio of 4.5:1 with the background colour`
- `text at least 24px and not bold has a minimum contrast ratio of 3:1 with the background colour`

If you ensure these tests are applied to new content you will have passed the success criteria 1.4.3 Contrast (Minimum). 
Some tests are conditional:

> * A test followed by **AND** <other test> = the previous test AND this test must be applied to pass the success criteria
> * A test followed by **OR** <other test> = the previous test OR this test must be applied to pass the success criteria

### Interpreting the tests

* 1.1.1 Non-text Content - two different modalities of CAPTCHA are provided
* 1.1.1 Non-text Content - **or**, providing access to a human to bypass CAPTCHA
* 1.1.1 Non-text Content - **or**, not requiring CAPTCHA for authorised users  
  
> **Apply any of the 3 tests**

* 1.3.1 Info and Relationships - two or more radio buttons, or checkbox controls must be grouped using a `<fieldset>`
* 1.3.1 Info and Relationships - **and**, the `<fieldset>` must have a succinct `<legend>` element  

> **Apply both tests**

### The Categories
These cateogries group the [WCAG 2.1 level AA success criteria](https://www.w3.org/TR/WCAG21/) according to the section of the website you're developing or your role. Allowing you to focus on the relevant criteria you need to apply and understand versus the criteria which can be ignored. For example, if your website doesn't have video or audio content you don't need to test against those criteria.  
  
## What this list isn't
It's not a catch-all list for things which you feel _should_ be accessibility failures but aren't. This is a list of our interpretation of what each WCAG 2.1 success criteria means and distilling that meaning into one or more tests. 
  
Accessibility best practice (those things which should be WCAG failures but aren't) will be in a separate filterable list.

## Contributing
Disagree with any of the tests? great! There are several ways to contribute:
- Log an issue in this repo, click "Issues" and follow the process of adding an issue
- Send an email to designsystem@dta.gov.au to indicate you disagree and want to alter a test/add a test

If your request is to add a further test, you will need to justify how the test fails against WCAG, for example non-sequential headings are not a WCAG 2.1 failure. 

https://www.tpgi.com/heading-off-confusion-when-do-headings-fail-wcag/
> WCAG techniques, such as H42: Using h1-h6 to identify headings and ARIA12: Using role=heading to identify headings, recommend that heading markup indicate the appropriate heading level for the content, but they don’t go so far as to define what’s “appropriate”—an issue that has been the subject of considerable discussion. So although hierarchical heading structures reflect a best practice, skipping heading levels does not represent a WCAG failure.

In short all requests are welcomed and appreciated, but are included only after consensus amongst the community. 
  
This project is aimed at conveying facts. Tests should strive to avoid personal preferences for identifying accessibility failures.

## License
MIT Licensed.
