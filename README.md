# WCAG Success Criteria Tests
The intention is to reduce the variance of testing for accessibility between professionals and people who have an interest in web accessibility. Agreeing on what constitutes a failure is the first step towards testing in a consistent way and having consistent results.

## The Categories
These cateogries group the WCAG 2.1 success criteria according to what part of the UI you're developing. Allowing you to focus on the relevant criteria you need to apply and understand versus the criteria you can ignore. i.e. if your site doesn't have video or audio content you don't need to test against those criteria.
- [Default View (all WCAG success criteria)](https://www.notion.so/ce7f793eefe24a5da585420796a58a3a?v=8abb13a3af9b40d48c3099289e7dfbc3)
- [Forms and UI](https://www.notion.so/ce7f793eefe24a5da585420796a58a3a?v=d32b0032ed55407b95a422c450e94ef5)
- [Customs Controls](https://www.notion.so/ce7f793eefe24a5da585420796a58a3a?v=2c170a694a9246a98d9cd5acc5754016)
- [Dynamic UI](https://www.notion.so/ce7f793eefe24a5da585420796a58a3a?v=f910905db416446fa34ae6aa107a19ad)
- [Content](https://www.notion.so/ce7f793eefe24a5da585420796a58a3a?v=4ba2ada304344e4eab482769faa9075a)
- [Font Size and Colour](https://www.notion.so/ce7f793eefe24a5da585420796a58a3a?v=83f6ef5cba9247a9beaf2c75cc834b38)
- [Structure](https://www.notion.so/ce7f793eefe24a5da585420796a58a3a?v=4faa3131e6404fac817841a381d3a97d)
- [Without Audio/Video](https://www.notion.so/ce7f793eefe24a5da585420796a58a3a?v=42b43626e84547b4ac404a3718bd4039)
- [Audio/Video](https://www.notion.so/ce7f793eefe24a5da585420796a58a3a?v=696312cd4a3e44c99f4d64f01a25705f)

### Using the tests
Each test is written in a way which is clear to understand the [accessibiltiy guidance for font sizing](https://www.notion.so/ce7f793eefe24a5da585420796a58a3a?v=83f6ef5cba9247a9beaf2c75cc834b38):
- `text smaller than 18.6px and bold has a minimum contrast ratio of 4.5:1 with the background colour`
- `text at least 18.6px and bold has a minimum contrast ratio of 3:1 with the background colour`
- `text smaller than 24px and not bold has a minimum contrast ratio of 4.5:1 with the background colour`
- `text at least 24px and not bold has a minimum contrast ratio of 3:1 with the background colour`

## What this list isn't
It's not a catch-all list for things which you feel _should_ be accessibility failures but aren't. This is a list of our interpretation of what each WCAG 2.1 success criteria means and distilling that meaning into one or more tests.

## Contributing
Disagree with any of the tests? great! There are several ways to contribute:
- Log an issue in this repo, click "Issues" and follow the process of adding an issue that indicates you disagree with an issue
- Send an email to ross.mullen@canaxess.com.au to indicate you want to alter/add a test
- Send a Twitter DM to [@mrrossmullen](https://twitter.com/mrrossmullen?lang=en) to indicate you want to alter/add a test

However not every request will be added. You will need to explain how your addition is a failure against WCAG, i.e. non-sequential headings are not a WCAG 2.1 failure. 

https://www.tpgi.com/heading-off-confusion-when-do-headings-fail-wcag/
> WCAG techniques, such as H42: Using h1-h6 to identify headings and ARIA12: Using role=heading to identify headings, recommend that heading markup indicate the appropriate heading level for the content, but they don’t go so far as to define what’s “appropriate”—an issue that has been the subject of considerable discussion. So although hierarchical heading structures reflect a best practice, skipping heading levels does not represent a WCAG failure.

In short all requests are welcomed and appreciated, but are included after consensus amongst the community.

## License
MIT Licensed. Copyright (c) CANAXESS 2021.
