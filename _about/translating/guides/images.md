---
title: "Translating Images"
nav_title: Translating Images
github:
  repository: w3c/wai-about-wai
  path: '_about/translating/guides/images.md'
permalink: /about/translating/guides/images/
ref: /about/translating/guides/images/
lang: en
last_updated: 2024-03-19

description: Help make the Web accessible to people with disabilities around the world. We appreciate your contributions to translating W3C WAI accessibility resources.
image: /content-images/wai-about-wai/social-translations.png

feedbackmail: wai@w3.org
footer: |
  <p><strong>Date:</strong> Updated 19 March 2024.</p>
  <p><strong>Editor:</strong> Rémi Bétin.</p>
---

{::options toc_levels="2" /}
{::nomarkdown}
{% include toc.html type="start" title="Page Contents" %}
{:/}

-   TOC is created automatically.
{:toc}

{::nomarkdown}
{% include toc.html type="end" %}
{:/}

To translate the images, you will need to translate the SVG source files, then export as PNG.

SVG source files of the images are located in the `content-images/source/` folder of the repository.

**What you will need:**
- An SVG editor. The following instructions apply to the [Inkscape](https://inkscape.org/) editor that have been used by some volunteers.
- The "Noto Sans" font family, including the _Regular_ and _Bold_ weights, installed on your computer.

**Steps:**
1. Duplicate the SVG file and add your language subtag in the filename. Example: `bridge.fr.svg`
2. Open the SVG file in your SVG editor.
3. In Inkscape, select the "Text Tool" on the lateral toolbar (or use the keyboard shortcut <kbd>T</kbd>)
4. Select the text objects and translate them. If necessary, you can slightly adjust the font size to prevent the text from going beyond the frame.
5. Change the language (`dc:language`) value of the file, with your language subtag. For example: `fr` instead of `en`.\
   In Inkscape, you can go to `File > Document Properties…`, then in the "Metadata" tab, and change the value of the "Language" field.
6. Save the SVG file.
7. Export the file as a PNG image, with your language subtag in the middle. Example: `bridge.fr.png`. Locate the file in the same location as the English version of the PNG file (generally at the root of the 'content-images/' folder) /
   In Inkscape, go to `File > Export…`. Make sure the Export area is "Page" (not "Document"), and that PNG is the selected export format. Then click on the "Export" button.
8. Include