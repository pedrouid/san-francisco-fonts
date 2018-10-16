# San Francisco Fonts

Easy access fonts as a git submodule for using SFMono and SFProText font-faces

### Setup

1. Install git submodule from this repository
```bash
$ git submodule add git@pedrouid:san-francisco-fonts <WEBSITE_DIR>/fonts
```

2. Add font-faces link tag to html header
```html
  <link rel="stylesheet" type="test/css" href="fonts/san-francisco.css">
```

3. Use font in your stylesheet
```css
/* For using SFMono with fallbacks */
.class {
  font-family: "SFMono", "Roboto Mono", Courier New, Courier, monospace;
}

/* For using SFProText with fallbacks */
.class {
  font-family: -apple-system, system-ui, BlinkMacSystemFont, "SF Pro Text", Roboto, Helvetica, Arial, sans-serif;
}

/* Available font-weights for both font-faces */
.class {
  font-weight: 400; /* normal */
  font-weight: 500;
  font-weight: 600;
  font-weight: 700; /* bold */
}
```