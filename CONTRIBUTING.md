# Contributing

Thank you so much for your interest in contributing to WWDC Notes! ❤️

## Create a New Session Note

### Name

All notes are named after their WWDC session number, for example `216.md`.

<details>
<summary>Click here to find out how to get a WWDC session number.</summary>

> To find the session number of a WWDC video, please refer to its url.
> 
> E.g.:  
> The [`SwiftUI Essentials`](https://developer.apple.com/videos/play/wwdc2019/216/) session url is `https://developer.apple.com/videos/play/wwdc2019/216/`: its session number is `216`.  
> 
> Therefore the file containing its notes will be named `216.md`.

</details>

### Location

All notes are placed in the `/content/notes/wwdcXX` folder, where `XX` is the WWDC year (e.g. `wwdc20` for WWDC 2020).

### Content

Add the contributors metadata at the top of each note:

```
---
contributors: yourNameHandle, anotherContributor
---

...your notes here...
```

Beside that, the rest of the file is for you to use, try to be as concise and as clear as possible 🚀

Do not worry about the session title, description, video link, etc: 
all of that will be automatically added later 🎉

## Update a Note

It's totally ok to update an existing note with more content, corrections, and further enhancements, even if you're not the one who wrote it originally.

If your change is substantial (a.k.a. more than adding a link, adjusting a few sentences, or fixing typos), you can add yourself in the note contributors.

## Use Images in a Note

Two steps:

1. Add the image(s) in the folder `/images/notes/wwdcXX/YYY` where `XX` is the session WWDC year (e.g. `wwdc20` for WWDC 2020) and `YYY` the session number (e.g. `216`).

2. Link them in your note using the url `../../../images/notes/wwdcXX/YYY/imageName.png`.

> the `../../../` prefix is used to make it possible to preview the images in the note on GitHub.

## Add yourself as a contributor

At the bottom of each note there is a list of all its contributors, with a picture and short bio.

### Picture

Place your picture in the `/images/community` folder, the image should be a square of any format, the image name must be the same as your contributor handle (used in the notes).

### Bio

Place your bio (another markdown file) in the `/content/community` folder: write something about yourself, you can add links to your Twitter/Github/apps/company/website/etc.

If you'd like your real name to be shown, please set it as the `title` metadata of the file.

The bio file name must be the same as your contributor handle (used in the notes).

<details>
<summary>Click here for an example.</summary>

```
---
title: Federico Zanetello
---
[Federico Zanetello][twitter] is an iOS Engineer with strong passion for Swift, minimalism, and design. 
When he’s not busy automating things, he can be found writing at [fivestars.blog][blog] and/or playing with the latest shiny toys.

[twitter]: https://twitter.com/zntfdr
[blog]: https://fivestars.blog/
```
</details>

## More Questions

If you need any further help or clarification, please [contact me on Twitter](https://twitter.com/zntfdr) or [email](mailto:wwdcnotes@fivestars.blog).

Thank you and please enjoy! 🎉
