A simple css system to manage breakpoints and media queries on front-end
projects. The `breakpoints.css` file serves as a reference as well as valid
code to insert media queries. In this project, this is used as reference and
basic css trickery to present on-screen documentation if relevant class is
applied to the `html` element.

A separate file is included for each of the breakpoints in the system (which
can be modified as required for your particular use-case), and it is expected
that the deployment automation would do what is required to concatenate,
minify, uglify, prettify or do whatever suits your purpose.

`responsive.css` is the file that includes all the files in proper order and
thus is the only file required to be included in the html as below:

```
<link rel="stylesheet" href="path/to/responsive.css">
```

while keeping all the rest of the css files in the same directory as 
`responsive.css`

We prefer to include `breakpoints.css` before `responsive.css` as well just
for aesthetics and to enable on-screen documentation it is primed for on demand
whenever we please. :)

