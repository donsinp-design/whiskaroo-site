# Changing the featured recipes

The Whiskaroo app shows the recipes listed in `featured.json` under "Featured" on the home screen.
Phones pick up changes the next time the app is opened. No app update needed.

## How to edit (about 2 minutes)
1. Go to github.com/donsinp-design/whiskaroo-site and open `featured.json`.
2. Click the pencil icon to edit.
3. Add, remove or reorder items. Each item looks like this:

       { "title": "Dish name", "blurb": "One short line", "source": "Who made it", "link": "https://link-to-the-recipe-or-video" }

   - `link` can be a recipe website, TikTok, Instagram Reel or YouTube video.
   - Optional: `"image": "https://link-to-a-photo.jpg"`. Without it, the photo comes from the recipe page.
   - Optional: `"tags": ["korean", "quick"]`. People who picked those in "What do you love to cook?" see the recipe
     first. Use any of: quick, korean, italian, thai, mexican, indian, healthy, vegetarian, seafood, baking,
     desserts, mealprep.
   - `heading` at the top is the title shown above the row.
4. Click "Commit changes". It goes live in about a minute.

Keep the commas between items, and no comma after the last one.
Featured recipes are free for everyone: they never use up someone's free recipe.
