# Coding style guide for SCSS

This is an extension to [Sass Guidelines](https://sass-guidelin.es) by Kitty Giraudel. Anything from this document overrides what could be said in the Sass Guidelines.

## Syntax & formatting

### Colours

#### Colour formats

The order of preference for colour formats is:

1.   Hexadecimal notation (lowercase and full-length)
2.   RGB notation
3.   HSL notation

The preferred colour format is long, lowercase hexadecimal. The next pre

```css
// 1st choice.
.foo {
  color: #ff0000;
}

// 2nd choice
.foo {
  color: rgb(255, 0, 0);
}

// 3rd choice
.foo {
  color: hsl(0, 100%, 50%);
}

// Avoid
.foo {
  color: #f00;
}

// Avoid
.foo {
  color: red;
}
```

### CSS ruleset

Only one selector per line.

```css
// Preferred
.foo,
.foo-bar,
.baz {
  display: block;
  overflow: hidden;
  margin: 0 auto;
}

// Avoid
.foo, .foo-bar,
.baz {
  display: block;
  overflow: hidden;
  margin: 0 auto;
}
```

