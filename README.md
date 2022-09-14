# MostlyHarmless Cookbook
The goal of this website is to have a community-written cookbook that people can easily use and contribute to at their leisure. The goal is to have a modern, minimal interface with no ads and no 3-page stories about how you grew up with your mother making this recipe every time you fell off your bike and cried. It's also to be designed so that it can be read anywhere with a mobile-friendly interface.

When contributing please use the sample provided in /recipes. Pictures for the recipes are fine but please make them as professional as possible without PII. Please no stories or epiphanies.

## How to test
1. Clone the repo
```
git clone https://github.com/LizardForth/MostlyHarmless
```
	
2. Change into the cloned directory and host a server.
```
cd MostlyHarmless	
python3 -m http.server
```
	
3. Open any web browser that isn't IE and go to `http://localhost:8000` as any changes you make will be reflected there.
	- Don't try and open index.html from a file explorer or something because the links won't point to the right place.
	- Reminder to use recipes/sample.html as a template. Standard for this is going to be to name the file after the recipe, so if your recipe is Drunken Chicken you'd have the following values:
		- Filename: `drunken-chicken.html`
		- Title: `Cookbook | Drunken Chicken`
