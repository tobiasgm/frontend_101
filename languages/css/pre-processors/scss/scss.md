## Readings

https://sass-lang.com/

https://sass-lang.com/guide

https://sass-guidelin.es/


## Best practices

### File/ folder organization

/globals – contains Sass files that get applied site-wide like typography, colors, and grids

/components – contains Sass files with component styles like buttons, tables, or input fields

/sections – contains Sass files dedicated to specific pages or areas on a page (might work better combined into the /components/ folder)

/utils – contains third-party utilities like Normalize that can be updated dynamically with tools like Bower.

main.scss – the primary Sass file in the root folder that imports all others.

### Partials

https://sass-lang.com/guide#topic-4:

“You can create partial Sass files that contain little snippets of CSS that you can include in other Sass files. This is a great way to modularize your CSS and help keep things easier to maintain. A partial is simply a Sass file named with a leading underscore. You might name it something like _partial.scss. The underscore lets Sass know that the file is only a partial file and that it should not be generated into a CSS file. Sass partials are used with the @import directive.”

### Naming

When organizing your variables and mixins it’s recommended to split them up by category, then list them in alphabetical order. This makes editing a whole lot easier because you know exactly where to find something.

Another naming practice pertains to responsive breakpoints. When naming Sass breakpoints, try to avoid device-specific names. It’s better to write names like small, med, lg, and xlg because they’re relative to each other.

### Nesting

https://www.sitepoint.com/8-tips-help-get-best-sass/

- Never go more than 3 levels deep.
- Ensure the CSS output is clean and reusable.
- Use nesting when it makes sense, not as a default option.