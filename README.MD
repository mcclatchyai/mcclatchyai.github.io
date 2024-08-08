# mcclatchyai.github.io

A landing page for AI journalism resources maintained by the McClatchy AI journalism innovation team.

Available publicly at: 

[mcclatchyai.github.io](https://mcclatchyai.github.io/)

*NOTE: This is a work in progress.*

## Maintenance notes

Site content is stored in the `docs/` directory in this repository running from the `gh-pages` branch.


### Local testing

To test changes more rapidly than the ~10-minute processing time, test changes to the site locally first.

```bash
cd docs
bundle exec jekyll serve
```

For more, see "Building your site locally" in [Testing your GitHub Pages site locally with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll#building-your-site-locally).

### Pushing to production

To push updates to the site to GitHub, which triggers a site rebuild under GitHub Actions, you'll need to commit changes via the `gh-pages` branch.

```bash
git checkout gh-pages
git add .
git commit -m 'COMMIT MESSAGE HERE'
git push -u origin gh-pages
```


For more information, see "Creating your site" in [Creating a GitHub Pages site with Jekyll
](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll#creating-your-site)

### Periodic updating

If the local version and production version of the site are different, you may need to update the `github-pages` gem. For more information, see [Updating the GitHub Pages gem](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll#updating-the-github-pages-gem).

