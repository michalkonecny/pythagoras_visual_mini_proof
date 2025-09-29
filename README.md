# Pythagorean Theorem – Visual Mini Proof

An interactive, step-by-step animation illustrating a short geometric proof of the Pythagorean theorem, plus concise write-ups.

- Proof summaries: `proof.md` and `proof-gpt5mini.md`
- Interactive animation: `pythagoras_animation.html`

## Live demo

Once GitHub Pages is enabled for this repository, the animation will be available at:

- https://michalkonecny.github.io/pythagoras_visual_mini_proof/

If the link shows 404 at first, go to the repository Settings → Pages and select the `gh-pages` branch (root). Publishing can take up to a couple of minutes to go live.

## Run locally

You can also open the animation locally:

1. Open `pythagoras_animation.html` directly in your browser, or
2. Serve the folder and navigate to the page:
   - Using Python 3: `python3 -m http.server` then open `http://localhost:8000/pythagoras_animation.html`

## Publishing to GitHub Pages (optional)

If not yet published, you can publish the animation by creating/refreshing a `gh-pages` branch that contains the file as `index.html`:

```
# from the repo root
rm -rf .gh-pages
git worktree add -B gh-pages .gh-pages main
cp -f pythagoras_animation.html .gh-pages/index.html
cd .gh-pages
git add index.html
git commit -m "Publish animation as index.html for GitHub Pages"
git push -u origin gh-pages
```

Then enable GitHub Pages for the repository (Settings → Pages → Branch: `gh-pages` / `/` root).

## License

See `LICENSE`.
