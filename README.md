# Featured

Files for the "What's New?" sections on [PRI](https://priweb.org), [CNC](https://cayuganaturecenter.org) and [MOTE](https://museumoftheearth.org).

> [!WARNING]
> Any changes made here will auto-populate to all three sites, so make sure you're all set before you push any updates!

## How to Update

The Events and Videos sections should automatically update by pulling from [Tockify](https://tockify.com/paleontological) and [YouTube](https://youtube.com/c/PaleontologicalResearchInstitution) respectively. That leaves the Blogs and More sections, which have to be updated manually.

### 1. Add New `<li>` 📝

Each section has an HTML file that feeds into the main [featured.html](featured.html) code on page load.

The structure of [blogs.html](blogs.html) or [more.html](more.html) is three `<li>` elements (indicated by `<!-- notes -->`). Typically, the easiest way to update is to cut and paste the `<li>` section from the bottom of the list to the top.

### 2. Update Link URL 🔗

The new `<li>` has two `<a>` tags that need to be updated with the URL pointing to the new blog post or "more" item. Paste the URL into the both `href=` spots.

Next, update the text for the title and date or external site name.

### 3. Update Image URL 🖼️

The new `<li>` also has one `img src=` that should be updated with the URL for the thumbnail image. This will scale, so no need to edit the image, but smaller images (~300px wide) are generally better.

### 4. That's All! 😎

Pat yourself on the back for a job well done (also, probably refresh the PRI home page one more time to make sure your changes work correctly!).

## How to Add to a Page

Add the content of [featured.html](featured.html) to a code block if you're using Squarespace or other similar web builder. Otherwise, you can pull what you need out of the code and repurpose it.
