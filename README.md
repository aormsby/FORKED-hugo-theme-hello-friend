# Forked Hello Friend Project

I use the [Hello Friend theme by @panr](https://github.com/panr/hugo-theme-hello-friend) to display my personal development blog built with the Hugo static site generator. The main reason I've forked the source is to make my own enhancements to the theme while keeping up-to-date with any changes made in the source. I often contribute to the theme by making pull requests for the enhancements I make, and it's great when they're happily received.

**Note --** I set the default branch of this repo to my **Working** branch that I use on my own site. It contains some of the improvements that were successfully pulled back to the source along with a few others that are too custom for the base theme. The **master** branch is in line with the original theme repo.

If you want to use this theme, I recommend cloning @panr's original repo and making your own modifications. :slightly_smiling_face:

**Second Note --** I added a Fork Sync action at `.github/workflows/wf-fork-sync`. If you fork or download my version of this theme, be sure to remove or change this workflow so you don't get unwanted syncing.

## Improvements Pulled to Theme Source

- Enhanced RSS feed that displays cover image and provides options to display content summary or full text
- Position param (left, center, right) in the imgproc shortcode for image positioning
- Last Modified Date display on pages (based on a file's git commit info)
- Enable/disable comments section on individual pages
- Basic Table of Contents param (auto-generated)
- Bug fix for some incorrect default Dates being displayed

## Other Local Improvements

- Projects page layouts for listing and detailing my development work
