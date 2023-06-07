# Contributing

Thank you so much for your interest in contributing to WWDC Notes! ❤️

## Add a new note

The recommended (and quickest) way to add a new note is to check out the [add a new note](https://www.wwdcnotes.com/what-s-missing/) page and choose the session you'd like to add from there.

> If you'd rather add a note manually, see chapter `Add a new note manually` at the end of this page. 

### Note content

Every note comes in the following format:

```
---
contributors: yourGithubHandle, anotherGithubUsername
---

...your notes here...
```

Besides adding your GitHub username among the contributors, the rest of the file is for you to use: try to be as concise and straightforward as possible.

Do not worry about the session title, tags, description, video link, etc.: all of that will be added automatically later.

### Note images

Two steps:

1. Add the image(s) in the folder `/images/notes/wwdcXX/YYY` where `XX` is the session WWDC year (e.g., `wwdc23` for WWDC 2023) and `YYY` the session number (e.g., `101`) (it's the same path as your note).

2. Link them in your note using the URL `../../../images/notes/wwdcXX/YYY/imageName.png`, for example:

```Markdown
![I am a description for the image.][reference-name]

[reference-name]: ../../../images/notes/wwdc23/101/file-name.jpg
```

> the `../../../` prefix is used to make it possible to preview the images both on the website and on GitHub.

## Update a note

It's encouraged to update an existing note with more content, corrections, and further enhancements, even if you're not the one who originally wrote it.

You can add yourself among the note contributors if your change is substantial (a.k.a. more than adding a link, adjusting a few sentences, or fixing typos).

## Community member details

Details like full name, avatar, website, etc., come automatically from your [GitHub profile][ghp]. All details are updated every time you make a new contribution to this repository.

## Add a new note manually

You're free to add notes manually instead of using [the recommended way](https://www.wwdcnotes.com/what-s-missing/): follow the note format (shown above) and place it at the correct location.

### Note location

All notes are located in `/content/notes/wwdcXX/YYYY.md`, where `XX` is the WWDC year (e.g., `wwdc21` for WWDC 2021), and `YYYY` is the WWDC session number, for example `216.md`.

<details>
<summary>Click here to find out how to get a WWDC session number.</summary>

> To find the session number of a WWDC video, please refer to its url.
> 
> e.g.,:  
> The [`SwiftUI Essentials`](https://developer.apple.com/videos/play/wwdc2019/216/) session url is `https://developer.apple.com/videos/play/wwdc2019/216/`: its session number is `216`.  
> 
> Therefore the file containing its notes will be named `216.md`.

</details>

## More Questions

If you need any further help or clarification, feel free ask in the #random channel on our [Slack space](https://join.slack.com/t/wwdc-notes/shared_invite/zt-1wbsoo705-bydJ430uZSRILstG5GxEzg) or reach out to Jeehut via a direct message there.

Thank you, and we look forward to your PRs! 🎉

[ghp]: https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/about-your-profile
