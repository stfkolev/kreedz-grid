About
--------
This is a SASS/SCSS grid system with fully customization set in mind.

Customization
--------
To modify the Flexbox grid, declare the following variables on your layout .scss

#### Fix the user-agent 8px addition to the margin (used for full width container/wrapper) -- can be customized by you
`$body-fix: 0;`

#### Max Wrapper width (100% for full-width, default is 1200px)
`$max-width: 100%;`

#### Set the number of columns you want to use on your layout.
`$grid-columns: 12;`

#### Set the gutter between columns.

`$gutter-width: 1rem;`

#### Set a margin for the container sides.

`$outer-margin: 1rem;`

####  Create or remove breakpoints for your project
You can modify, remove or create breakpoints before generating the final CSS. An example is given in layout.scss onto how one can modify them.

```
$breakpoints:
  sm 48rem,
  md 64rem,
  lg 80rem,
  xlg 90rem,
  impossiblebutveryhard 120rem;
```