# Web101Notes
Contains PPTs, Word Documents and all source code files from the Web Dev 101 classes

---

# Content syummary of every session
#### Class 5
Basics of CSS
- Writing inline, internal and external
- Linking an external CSS file to an HTML file
- Targetting an element using ID, Class and the tag itself
- Targetting descendants of an element
- Learning properties like `color`, `font-size` and `font-family`

#### Class 6
Box model (visual examples present in the PPT)
- Learning properties like `color`, `font-size` and `font-family`
- Layers of a box: `content`, `padding`, `border`, `margin`
- Different styles of a border
- Different value for the `overflow` attribute
- `inline`, `block`, `inline-block` values for the `display` attribute
- CSS Units:
    - Absolute Units: `px`
    - Relative units: `vh`, `vw`, `%`, `rem`

### Class 7
Flexbox and Media Queries
- Default `flex-direction` : `row`
- Property to align items along main-axis: `justify-content`
- Property to align items along cross-axis: `align-items`
- Use of `flex-wrap`
- Control individual items inside a flex container using the `order` property
- `flex-shrink` and `flex-grow`
- Media query is used to change the style of a webpage based on the size (width/height) of  te viewport

| `flex-direction` value | Main Axis | Cross Axis |
| --- | --- | --- |
| `row` (default) | x-axis | y-axis |
| `row-reverse` | x-axis | y-axis |
| `column` | y-axis | x-axis |
| `column-reverse` | y-axis | x-axis |

### Class 8
`grid` display
- Use `grid-template-column` to arrange and size boxes inside the grid in different size of column
- Use `fr` to split based on ratio
- Use `gap` to space between the boxes of a grid; use `row-gap`, `column-gap` for specifically spacing rows and columns, respectively
- Use `repeat()` with `grid-template-column` or `grid-template-column` function to repeat to space items a specific number of times in a specific height or width
- Use `nth-of-type()` to target a specific element inside the grid container
- Use `grid-template-areas` and `grid-area` to draw layouts across the webpage and place items
- Flexxbox properties will also work in grid
- <b>Additional properties</b>: `grid-column`, `grid-row`, `grid-auto-rows`
- <b>NOTE</b>: Go through the PPT as it includes lot more things, in detail

### Class 9
How stylings work
- Browser Default > Internal CSS > External CSS (Top of the file) > External (Gradually to the bootom of the file)
- Precedence: Elements < Classes < IDs < Inline styles < `!important`
- Inheritence refers to the phenomenon where a (in the context of CSS) child element inherits the styles defined for the parent

---

### Repo owner: Shubham Behl
