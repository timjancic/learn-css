CSS tricks:

Use alternative box model in entire webpage:
(https://css-tricks.com/inheriting-box-sizing-probably-slightly-better-best-practice/)

html {
  box-sizing: border-box;
}
*, *:before, *:after {
  box-sizing: inherit;
}
