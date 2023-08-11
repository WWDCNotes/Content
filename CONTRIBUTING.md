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

...your notes here (no session title needed) ...
```

Besides adding your GitHub username among the contributors, the rest of the file is for you to use: try to be as concise and straightforward as possible.

Do not worry about the session title, tags, description, video link, etc.: all of that will be added automatically later.

### Where to Save the Note Images

Two steps:

1. Add the image(s) in the folder `/images/notes/wwdcYY/SSS` where `YY` is the session WWDC year (e.g., `wwdc23` for WWDC 2023) and `SSS` the session number (e.g., `101`) (it's the same path as your note).

2. Link them in your note using the URL `../../../images/notes/wwdcYY/SSS/file-name.png`, for example:

```Markdown
![I am a description for the image.][reference-name]

[reference-name]: ../../../images/notes/wwdc23/101/file-name.jpg
```

> Use exactly this format including the `../../../` prefix to make it possible to preview the images both on the website and on GitHub.
> You can place the `[reference-name]: <link>` part at the end of the document or inline, there's no strict rulem, both will work.

### Guidelines for Incorporating Images and Screenshots

1. **Privacy Considerations**: Prioritize presenter privacy by cropping out any individuals from the screenshots.

2. **Image Quality**: Maintain high-quality screenshots that remain clear and crisp even on larger displays like external monitors or MacBooks, avoiding any pixelation.

3. **Image Resizing for Server Optimization**: To optimize server load, follow these steps to resize images:

   **On a Mac**:
   a. Open the image in Preview.
   b. Utilize the selection tool to crop unnecessary portions, like black bars at the top and bottom, by dragging with the mouse.
   c. Crop the selected area using `Command + K`.
   d. Save the edited image.
   e. For exporting, either choose `File > Export`, pick `JPG` format, assign a filename, and save it in the designated WWDC folder on your Mac.
   
   **Or**, you can right-click on the screenshot (typically a PNG file), then select: `Quick Actions -> Convert Image`.  
   
   **On an iPad**:
   The Photo app on an iPad doesn't directly support image resizing. However, you can use the **Shortcut** app ([Link](https://apps.apple.com/us/app/shortcuts/id915249334)) to create a custom shortcut. This will allow you to automate the resizing process for your images. When preparing images for the web and MacBook Pro displays, for web use, common sizes include 1920x1080 (Full HD), 2560x1440 (2K), and 3840x2160 (4K) for background images or banners. But widths around **800 to 1200 pixels** are often suitable for accommodating various screen sizes without excessive resizing and a resolution of **72 pixels per inch (PPI)** is generally sufficient. 

4. In Preview on macOS, you have the capability to **select and copy text directly from images, even including code snippets**. Consequently, opting for a code block is more advantageous than using an image that contains text or code.

### Ensure no one else works on it in parallel

If you're providing notes durnig the week of WWDC, it's possible that others are currently watching sessions & providing notes as well. While it's totally encouraged that multiple people provide notes for the same session to combine them, if you don't want to contribute notes for a session that already is being worked on, make sure to check the latest messages in the `#wwdc23` channe on our [Slack space](https://join.slack.com/t/wwdc-notes/shared_invite/zt-1wbsoo705-bydJ430uZSRILstG5GxEzg). Also, if you do decide to work on a session during WWDC wwek, make sure to inform the community about it in the same place. Thank you! 🙏

## Update a note

It's encouraged to update an existing note with more content, corrections, and further enhancements, even if you're not the one who originally wrote it.

You can add yourself among the note contributors if your change is substantial (a.k.a. more than adding a link, adjusting a few sentences, or fixing typos).

## Community member details

Details like full name, avatar, website, etc., come automatically from your [GitHub profile][ghp]. All details are updated every time you make a new contribution to this repository.

## Add a new note manually

You're free to add notes manually instead of using [the recommended way](https://www.wwdcnotes.com/what-s-missing/): follow the note format with the header shown above and place it at the correct location.

### Note location

All notes are located in `/content/notes/wwdcYY/SSS.md`, where `YY` is the WWDC year (e.g., `wwdc21` for WWDC 2021), and `SSS` is the WWDC session number, for example `101.md`.

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
