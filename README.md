# Bedtime Stories

A simple page for listening to Diary of a Wimpy Kid audiobooks at bedtime.

Live at: https://polyaccount.github.io/bedtime/

## How to add a story

1. Open `index.html` on GitHub and click the pencil icon (Edit).
2. Find the `STORIES` list near the top of the `<script>` section.
3. Add a new line like this, keeping the commas:

   ```js
   { title: "Book 18 – No Brainer", url: "https://www.youtube.com/watch?v=XXXXXXXXXXX" },
   ```

   Any YouTube link format works (`watch?v=`, `youtu.be/`, or just the 11-character video ID).
4. Click **Commit changes**. The site updates within a minute.
