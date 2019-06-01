# Japanese CSS Colors
A set of CSS variables covering 221 traditional Japanese colors

## How to Use
Use sample_table.html to find the color you want to use.  Each row contains a cell with the name of the color variable used and the original Japanese text for the name.  Further, The rows in the table are all styled inline to make it easy to find the color that was used for a given row.

From there just use the variable name inside `var()`, as shown in the following example:

```css
body {
	background: var(--benihi);
	color: var(--aijiro);
}
```
