# Riham Blogs' Text Analyzer
**Try it out at:** [https://cigarettesprettysmokes.pages.dev/analyze/](https://cigarettesprettysmokes.pages.dev/analyze/)
 
## Overview
Paste text into the analyzer to see real-time statistics as you type. It breaks down characters, words, sentences, paragraphs, lines, reading time, and word frequency.
 
 
## Statistics
 
### Characters
Analyze the characters as a whole, or break it down by type: numeric, special, spaces, punctuations, uppercase, and lowercase. A special character is any remaining character that doesn't belong to the other categories.
Emojis are composed of multiple Unicode characters, so a single emoji may register as more than one character.
 
### Words
Shows total and unique words, average word length, and the longest word. The character length is shown in parentheses for the longest word.
A word is a sequence of letters, digits, apostrophes ('), periods (.), and hyphens (-). Outer apostrophes, periods, and hyphens are trimmed from display.
Unique words are case-insensitive. Average word length is measured in characters per word. Ties for the longest word are broken by first occurrence.
 
### Sentences
Shows the total sentences and the shortest, average, and longest sentence lengths. Sentence length is measured in words, so the longest sentence has the most words and the shortest has the fewest.
A sentence ends when it hits a terminator character, but only if the terminator is followed by a space or the end of the text. So "Riham. Blogs." registers as two sentences, while "Riham.Blogs" registers as one.
 
### Paragraphs
A paragraph is a section of non-empty text. Two paragraphs are separated by a blank line. A single line break doesn't start a new paragraph.
 
### Lines
A line is a row of non-empty text between newlines.
 
### Reading Time
Reading Time = (Words / WPM) × 60, shown as **00h 00m 00s**, with zero-value units omitted (except for seconds). Uses the total words from the **Words** statistic.
 
### Word Frequency Table
Sorted by **frequency, descending**. Ties broken **alphabetically**. Words are treated case-insensitively but display in first-seen casing.
Percentages are rounded to one decimal place. For example, a word that appeared once out of three times shows **1 (33.3%)**.
Pure numbers (e.g. "2025") and standalone punctuation are excluded, unlike the **Words** statistic. This table shows only words that contain at least one letter.
 
 
| Column | Description |
| --- | --- |
| Word | The word in its first-seen casing |
| Frequency (%) | How many times it appears and its share of total words |
 
 
## Settings
 
### Target Length
Set a character limit if your text needs to fit a fixed number of characters. Pick a preset from the dropdown, or choose **Custom** to set your own limit between 25 and 8,000 characters. The default is **3000**.
**Meta** refers to HTML meta tags for SEO. The presets are industry-standard estimates, as search engines truncate by pixel width, so the true limit can vary by roughly ±10 characters from the number shown.
Instagram may truncate captions at around 100 to 125 characters (per third-party sources). The platform allows up to 2,200 characters, as stated by Meta. "Reddit Title (300)" comes from a third-party documentation.
 
 
| Preset | Limit | Source |
| --- | --- | --- |
| Twitter/X Post | 280 | [Twitter/X Help: Post](https://help.x.com/en/using-x/how-to-post) |
| Twitter/X Biography | 160 | [Twitter/X Help: Profile](https://help.x.com/en/managing-your-account/how-to-customize-your-profile) |
| Meta Title | 60 | **N/A** |
| Meta Description | 150 | **N/A** |
| Pinterest Title | 100 | [Pinterest Help](https://help.pinterest.com/en/article/review-pin-specs) |
| Pinterest Description | 800 | (Same as above) |
| YouTube Title | 100 | [Google Support](https://support.google.com/youtube/answer/57404) |
| YouTube Description | 5,000 | (Same as above) |
| Instagram Caption | 2,200 | [Facebook Developers](https://developers.facebook.com/documentation/ads-commerce/instagram/ads-api/reference/media-requirements.md) |
| LinkedIn Post | 3,000 | [LinkedIn Help](https://www.linkedin.com/help/sales-navigator/answer/a528176/) |
| Reddit Title | 300 | [Zernio Docs: Reddit](https://docs.zernio.com/platforms/reddit) |
 
 
### Sentence Ends With
Choose which characters end a sentence when followed by a space or end of text. Separate multiple terminators with a space. The default terminators are period (.), question mark (?), and exclamation mark (!).
 
### Reading Speed
**Reading Speed (WPM)** sets how fast the analyzer assumes you read. The default is **250** WPM. WPM stands for Words Per Minute.
 
### Export Word Frequency
Click **Export Word Frequency** to download a high-quality Word Cloud image, generated from the most frequent words in your text.
The image is 1920×1080 (16:9) with a white background. The font is bold monospace, and each word is colored automatically with guaranteed contrast against the white background.
Export requires at least 25 words. Up to the 100 most frequent words are considered (or fewer if the text is shorter).
Font size scales linearly with frequency, so the most common words dominate visually. Layout uses spiral placement from the canvas center, with about 25% of words rotated 90°. Placement is randomized, so each export produces a different image.
 
 
## Privacy
Everything is processed locally in your web browser. Your text is not uploaded, transmitted, or stored on any server. Closing the tab clears it (see Riham Blogs' [Privacy Policy](https://cigarettesprettysmokes.pages.dev/privacy/) for details). 
Report bugs or request features on Riham Blogs' [Submit Feedback](https://cigarettesprettysmokes.pages.dev/feedback/) page.
 
## Desktop Preview
 
## Mobile Preview
 
