# support-data
Data for the WebProfiles support center.

---

# How to Contribute

## New Article
1. Find the category that you would like to add an article to. (e.g. `categories/announcements` folder)
2. Edit the `data.json` file to include the following details: 
```json
{
	"category": "announcements",
	"data": [
		{
			...
		},
		{
			"name": "Article Title Here",
			"slug": "article-title-here"
		}
	]
}
```
3. Create a file named after the slug you provided above (e.g. `article-title-here.json`).
4. In the file that you have just created, add the following data (*Note:* You can fetch the ISO date by running `new Date().toISOString()` in your browser's console):
```json
{
  "title": "Article Title Here",
  "author": "Your Name Here (e.g. Joshua M)",
  "date": "ISO date (e.g. 2021-10-17T02:41:19.198Z)"
}
```
5. Create a file in the `markdown` folder, named after your article's slug (e.g. `markdown/announcements/article-title-here.md`).
6. In the Markdown file, write the support article using [Markdown](https://www.markdownguide.org/getting-started/).
7. Create a pull request on the main repository located at [https://github.com/WebProfiles-me/support-data](https://github.com/WebProfiles-me/support-data).
