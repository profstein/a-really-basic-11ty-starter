# A really basic 11ty starter.

I made this to use while I learn and experiment with 11ty.
It's supposed to be a super basic starting point so I can skip some of the setup.
I don't know if I have done this correctly or if works...

## What's been setup/installed:

- 11ty
- .eleventy.js
  ```
  return {
    markdownTemplateEngine: "njk",
    dataTemplateEngine: "njk",
    htmlTemplateEngine: "njk",
    dir: {
      input: "src",
      output: "dist",
    },
  };
  ```
- .gitignore
- package.json
- index.md

# Running locally

```
npm start
```

# References

[https://learn-eleventy.pages.dev/lesson/2/](https://learn-eleventy.pages.dev/lesson/2/)
