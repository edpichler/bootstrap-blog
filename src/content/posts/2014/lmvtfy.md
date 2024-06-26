---
author: cvrebert
date: "2014-06-25T00:00:00Z"
title: Let Me Validate That For You (LMVTFY)
video: HEXWRTEbj1I
---

If you've been following the Bootstrap issue tracker lately, you might have noticed the launch of our new bot, [@twbs-lmvtfy](https://github.com/twbs-lmvtfy), on June 15th. After seeing many reports of Bootstrap bugs that ended up actually being caused by folks using invalid HTML, we decided to do what all programmers do when confronted with a repetitive task: [Automate it!](https://github.com/twbs/bootstrap/issues/11984)

To that end, we are excited to announce the availability of **[Let Me Validate That For You (LMVTFY)](https://github.com/cvrebert/lmvtfy)**, an open-source bot that uses the power of the [GitHub webhooks API](https://docs.github.com/en/webhooks/about-webhooks) and the [validator.nu](https://github.com/validator/validator) HTML5 validator to warn about HTML validity errors in live Web examples (e.g. [JS Bins](https://jsbin.com/)) posted to GitHub issues.

The bot is generic and can be used for any GitHub project, not just Bootstrap. If you have a front-end Web project on GitHub that gets lots of issue reports, we invite you to try out LMVTFY.

For more details, setup instructions, or to give feedback, [check out the LMVTFY project on GitHub](https://github.com/cvrebert/lmvtfy).
