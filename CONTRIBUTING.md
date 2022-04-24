# Contributing

Thank you so much for your interest in contributing to WWDC Notes! ❤️

## Add a new note

The easiest (and recommended) way to add a new note is to check out the [add a new note](https://www.wwdcnotes.com/what-s-missing/) page and choose the session you'd like to add from there.

> If you'd rather add a note manually, see chapter "Add a new note manually" at the end of this document. 

### Note content

Every note comes with the following format:

```
---
contributors: yourNameHandle, anotherContributor
---

...your notes here...
```

Beside adding your name among the contributors, the rest of the file is for you to use: try to be as concise and as clear as possible 🚀

Do not worry about the session title, tags, description, video link, etc: all of that will be added automatically later 🎉

### Note images

Two steps:

1. Add the image(s) in the folder `/images/notes/wwdcXX/YYY` where `XX` is the session WWDC year (e.g. `wwdc21` for WWDC 2021) and `YYY` the session number (e.g. `216`) (it's the same path as your note).

2. Link them in your note using the url `../../../images/notes/wwdcXX/YYY/imageName.png`.

> the `../../../` prefix is used to make it possible to preview the images both on the website and on GitHub.

## Update a Note

It's totally ok to update an existing note with more content, corrections, and further enhancements, even if you're not the one who wrote it originally.

If your change is substantial (a.k.a. more than adding a link, adjusting a few sentences, or fixing typos), you can add yourself in the note contributors.

## Community member details

As a contributor of WWDC Notes, you have the possibility to tell who you are and link to your website and social media presence. These (optional) details will be automatically attached to each note you've contributed to.

### Picture

Place your picture in the `/images/community` folder, the image should be a square of any format, the image name must be the same as your contributor handle (used in the notes).

### Bio

Place your bio (another markdown file) in the `/content/community` folder: write something about yourself, you can add links to your Twitter/Github/apps/company/website/etc.

If you'd like your real name to be shown, please set it as the `title` metadata of the file.

The bio file name must be the same as your contributor handle (used in the notes).

Example:

```
---
title: Federico Zanetello
twitter: zntfdr
github: zntfdr
website: https://fivestars.blog
linkedin: federico-zanetello
medium: zntfdr
---
iOS Engineer with strong passion for Swift, minimalism, and design. When he’s not busy automating things, he can be found writing at [FIVE STARS][fs] and/or playing with the latest shiny toys.

[fs]: https://fivestars.blog/
```

## Add a new note manually

You're free to add notes manually instead of using [the recommended way](https://www.wwdcnotes.com/what-s-missing/), just make sure to follow the note format (shown above) and place the note at the correct location.

### Note location

All notes are located in `/content/notes/wwdcXX/YYYY.md`, where `XX` is the WWDC year (e.g. `wwdc21` for WWDC 2021), and `YYYY` is the WWDC session number, for example `216.md`.

<details>
<summary>Click here to find out how to get a WWDC session number.</summary>

> To find the session number of a WWDC video, please refer to its url.
> 
> E.g.:  
> The [`SwiftUI Essentials`](https://developer.apple.com/videos/play/wwdc2019/216/) session url is `https://developer.apple.com/videos/play/wwdc2019/216/`: its session number is `216`.  
> 
> Therefore the file containing its notes will be named `216.md`.

</details>

## More Questions

If you need any further help or clarification, please [contact me on Twitter](https://twitter.com/zntfdr) or [email](mailto:wwdcnotes@fivestars.blog).

Thank you and please enjoy! 🎉
