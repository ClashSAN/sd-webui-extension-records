<h1 align="center">
  Optional Tools
  <br>
</h1>

Basic, but these are mostly to help with generating copy-pastable entries using the current list format.

**Index.html** and **create-copy-pastable-entry.ps1** produce the same result, just pick whichever is easiest to use.

# For adding entries - you probably want one of these
## [create-copy-pastable-entry.ps1](create-copy-pastable-entry.ps1)
Save, run it, and follow the prompts

## [Index.html](Index.html)

For now, the index.html file can be saved and then opened in the browser to make it work.

<h1 align="center">
  Misc
  <br>
</h1>

## [parse-a1111-json-blob-and-get-commit-data.ps1](parse-a1111-json-blob-and-get-commit-data.ps1)

Gets the current commits from JSON blob at Automatic's wiki and outputs a csv.


You can go to the [extension page](https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki/Extensions-index) and copy the entire JSON blob into a text file for the script to process.

Make sure to edit the top of the script so it knows where your **git** install is.
