# Approaches

## Responsive
Basic approach:
```
html {
  font-size: 100%; // Usually 16 pixels
}

h1 {
  font-size: 3rem; // 3 × base font size (3 × 16px)
}
```
Setting break points with media queries:
```
html {
  font-size: 100%;

  @media (min-width: 768px) {
    font-size: 112.5%;
  }
}

h1 {
  font-size: 3rem;

  @media (min-width: 768px) {
    font-size: 3.5rem;
  }
}
```


## Fluid typography with min/ max sizes

https://css-tricks.com/snippets/css/fluid-typography/


# Tools

Resizing engine - https://github.com/twbs/rfs
https://github.com/liamdefty/sass-fluid-type

# Discussion

https://betterwebtype.com/articles/2019/05/14/the-state-of-fluid-web-typography/
