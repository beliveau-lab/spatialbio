# [SpatialBio](https://spatialbioseattle.org) (Forked from [TeXt Theme](https://github.com/kitian616/jekyll-TeXt-theme))

![SpatialBio Demo](/assets/images/general/README_Banner.png)

```
bundle exec jekyll serve  --port 6998 --host 0.0.0.0 --livereload --livereload-port 6997 --force_polling --watch
People's pictures...
```

## Updating
1. Configure ``title`` and ``description`` in ``_config.yml``
2. Backup ``index.md`` to ``/_posts`` and rename accordingly
3. Update the contents of ``index.md``, ``/assets/images/sponsors``
4. For further customizations, see [Files Modified](#files-modified)

## Files Modified

- [/_includes/head/custom.html](_includes/head/custom.html) - Stylesheet Headers (Bootstrap, etc.)
- [/_includes/head/favicon.html](_includes/head/favicon.html) - Favicon Customization (assets)
- [/_includes/svg/logo.svg](_includes/svg/logo.svg) - Logo Customization (assets)
- [/_includes/footer.html](_includes/footer.html) - Footer Styling
- [/_layouts/sblanding.html](_layouts/sblanding.html) - SpatialBio Layout
- [/_layouts/sbpage.html](_layouts/sbpage.html) - SpatialBio Layout
- [/_posts](_posts) - SpatialBio Archive
- [/_sass/common/components/_modal.scss](_sass/common/components/_modal.scss) - TeXT modal.scss; Commented out to avoid conflicts with Bootstrap
- [/_sass/custom.scss](_sass/custom.scss) - Custom SCSS File
- [/assets](assets) - Asset Customization
- [/_config.yml](_config.yml) - Configuration File
- [/about.md](about.md) - About Page
- [/index.md](index.md) - Current SpatialBio Page

#### Notes

- Liquid isn't executable in frontmatter
- Some links may be broken dependending on base url (can be fixed with absolute paths or configuring base url in [/_config.yml](_config.yml))
- Favicon needs to be sized to specification in order to show up properly on Google