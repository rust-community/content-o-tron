# Running a blog post campaign

## Assumptions

- There is a topic for the campaign, usually someone has approached the [Rust content team][link_content_team] (or the [Community team][link_community_team]) directly. If not, you can pick a [focus topic][link_focus_topics] and write a summary of what you would like the campaign to cover.

## Timeline

The days/weeks next to main bullet points are duration for these phases.

- Initiation (2 days)
  - Write an introductory blog post on the relevant blog sites i.e. community.rs, blog.rust-lang.org, etc. Don't forget to allocate time for someone to review the post.
  - Create a sub-folder in `campaigns` in the [project][link_project_folder]. This should match the name of your campaign e.g. `#Example4096` then the full path would be [github.com/rust-community/content-o-tron/campaigns/example4096](https://github.com/rust-community/content-o-tron/tree/master/campaigns/example4096). Note: we've omitted special characters like "`#`" and replaced delimited words using "`-`". You can see more details on the use of this folder in the [Review Cycle](#review-cycle) section.
  - Raise a tracking [issue][link_tracking_issue] for the campaign, clicking on the link will generate a tracking issue. Warning: you'll need to have collaborator access to the project to assign labels. If you don't, add a comment to your issue and someone from the team will add the ![code](https://img.shields.io/badge/-campaign-fc949f.svg) label.
- Review cycle (1-2 weeks)
  - Provide editorial assistance.
  - Identify any posts that could be passed onto [blog.rust-lang.org][link_brlo] or [Mozilla Hacks][link_mozhacks], discuss with author to see if it's okay to allow either of these sites to have a first claim on the post (more on this later on).
- Curation (1-3 days)
  - Gather all blog posts into an RSS feed and submit to [readrust.net][link_readrust]
  - Write up a summary/follow post on relevant blog sites i.e. community.rs, blog.rust-lang.org, etc
- Retrospective (1 day)
  - What went well
  - What could be improved?
  - Update the campaign process based on the feedback.

Total time: up to 3 weeks.

The review cycle could be much longer (or shorter) and is entirely dependant on your own requirements. The [#Rust2017][link_rust2018] campaign the Rust Community team had a review cycle of almost a month.

## Review cycle

The tracking issue serves two purposes, it is a way for contributors to register their interest to write a blog post and also a way to continue updating the progress of the campaign.

During the review cycle blog post contributors will begin to add drafts to the campaign folder that was detailed in the [Timeline](#timeline) section or link to their drafts in the tracking issue.

TODO: detail editorial process.

## First claim on blog posts

TODO: explain

[link_focus_topics]: https://github.com/rust-community/content-team/issues/16
[link_tracking_issue]: https://github.com/rust-community/content-o-tron/issues/new?template=new_campaign.md&title=Tracking:+__NAME_OF_CAMPAIGN__&labels=campaign
[link_readrust]: https://readrust.net/submit.html
[link_rust2018]: https://readrust.net/rust-2018/
[link_brlo]: https://blog.rust-lang.org/
[link_mozhacks]: https://hacks.mozilla.org/category/rust-2/
[link_content_team]: https://github.com/rust-community/content-team
[link_community_team]: https://github.com/rust-community/team
[link_project_folder]: https://github.com/rust-community/content-o-tron/tree/master/campaigns