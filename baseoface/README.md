## baseof.ace test case

This demonstrates a problem with ACE templates in themes.
If you run this demo as-is:

```
$ hugo server --watch --theme=demotheme
```

then visit `localhost:1313`, the result is an empty page.
If, however, you move `themes/demotheme/layouts/_default/baseof.ace`
to `layouts/_default/` and *then* run Hugo, the site is displayed
as it ought to be.
