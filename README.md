# EmoteTexturePacker - Making Reddit emotes easy!

## Crash Course

**Requires [TexturePacker](https://www.codeandweb.com/texturepacker/) Pro**

1) Add the contents of this repo into your TexturePacker exporter folder. For Windows, it is at `C:/Program Files/CodeAndWeb/TexturePacker/bin/exporters` and it is at `Applications/TexturePacker.app/Contents/Resources/exporters` for macOS.

2) Use [TexturePacker](https://www.codeandweb.com/texturepacker/)'s trial (or full version) as normal, selecting the "Reddit  Stylesheet Emotes (BPM)" option

3) Name the output file as you want your stylesheet to be called in Reddit. If you want to call it stylesheet "a", set the name as "a".

4) After exporting it, open the generated CSS file (a Markdown file is generated with the list of emotes on it too, as with an image you would upload to Reddit) and remove the last comma in the sequence of `A[href|="/emotename"],` so the CSS doesn't fail. It would be on the line before the comment generated.

5) Copy and paste the remaining CSS into your Reddit stylesheet and upload the generated image.

6) Submit your subreddit to [/r/BetterPonymotes](https://betterponymotes.reddit.com) if you are a pony subreddit (optional).

7) Use the emote codes in the generated Markdown file to have the emotes appear in comments!
