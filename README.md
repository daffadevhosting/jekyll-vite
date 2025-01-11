# Jekyll Boilerplate

Jekyll Boilerplate is a lightweight and cleaned up version of the initial [Jekyll](https://jekyllrb.com/) setup. The motivation behind this project was for me to avoid doing the same things over and over every time I build yet another site with Jekyll.

## Features

- ⚡️ Blazing fast hot reload
- 📦 Zero-config builds
- 🎨 Use your favorite tools (TypeScript, Tailwind CSS, etc.)

## Documentation 📖

The [documentation website][website] is built using `jekyll-vite`.

You can [check the source to see an example setup][example], or visit it to
[learn how to use `jekyll-vite`][website].

## Installation 💿

Add this line to your site's Gemfile:

```ruby
gem 'jekyll-vite'
```

Then, run:

```bash
bundle install
bundle exec vite install
```

Additional [installation instructions][installation] are available in the [documentation website][installation].

## Credits

* [Jekyll](https://jekyllrb.com/)
* [Daffa aditya](https://blog-daffa.vercel.app)

## Acknowledgements

- [Jekyll] — Even after all this time, it's still a great static site generator.
- [Vite.js] — Frontend tooling with a focus on the developer experience.

## Why Vite? 🤔

[Jekyll] does not have an extensible asset pipeline, which limits the amount of
integrations that exist for different languages and preprocessors. By default,
assets are not fingerprinted which is problematic for caching.

[Vite.js] has an extensible architecture and is built on top of [rollup.js], and as
a result there is an active ecosystem of plugins and tooling available. In addition,
its [no bundling] design provides a very fluid authoring experience—changes to
your assets are reflected instantly in your browser.

