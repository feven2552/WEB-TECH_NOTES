# Bootstrap 5

pre made components like Navbars, Modals, tabs , tooltips, buttons, accordions…

responsive, 12-column, css grid system

```jsx
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
```

adding the bootstrap from CDN  on the header and on the bottom of the body section resp.

# Content

### Typography

```html
<p class="lead text-center">Hello Feven</p>
<p class="lead text-end"> Hello Feven</p>
<p class="lead text-start">Hello Feven</p> <!--Default-->
```

Make the text alignment center, start and end.

- `<mark>` represents text which is marked or highlighted for reference or notation purposes.
- `<small>` represents side-comments and small print, like copyright and legal text.
- `<s>` represents element that are no longer relevant or no longer accurate.
- `<u>` represents a span of inline text which should be rendered in a way that indicates that it has a non-textual annotation.
- `<mark>` represents text which is marked or highlighted for reference or notation purposes.
- `<small>` represents side-comments and small print, like copyright and legal text.
- `<s>` represents element that are no longer relevant or no longer accurate.
- `<u>` represents a span of inline text which should be rendered in a way that indicates that it has a non-textual annotation.
- Add `.initialism` to an abbreviation for a slightly smaller font-size.

```html
<p><abbr title="attribute">attr</abbr></p>
<p><abbr title="HyperText Markup Language" class="initialism">HTML</abbr></p>
```

- 

blockquotes 

Naming a source 

Alignmnet 

lists 

inline 

Responsive font size 

### **variable**

Headings have some dedicated variables for sizing and spacing.

```html
$headings-margin-bottom:      $spacer * .5;
$headings-font-family:        null;
$headings-font-style:         null;
$headings-font-weight:        500;
$headings-line-height:        1.2;
$headings-color:              null;
```

Headings have some dedicated variables for sizing and spacing.

```html
$lead-font-size:              $font-size-base * 1.25;
$lead-font-weight:            300;

$small-font-size:             .875em;

$sub-sup-font-size:           .75em;

$text-muted:                  $gray-600;

$initialism-font-size:        $small-font-size;

$blockquote-margin-y:         $spacer;
$blockquote-font-size:        $font-size-base * 1.25;
$blockquote-footer-color:     $gray-600;
$blockquote-footer-font-size: $small-font-size;

$hr-margin-y:                 $spacer;
$hr-color:                    inherit;
$hr-height:                   $border-width;
$hr-opacity:                  .25;

$legend-margin-bottom:        .5rem;
$legend-font-size:            1.5rem;
$legend-font-weight:          null;

$mark-padding:                .2em;

$dt-font-weight:              $font-weight-bold;

$nested-kbd-font-weight:      $font-weight-bold;

$list-inline-padding:         .5rem;

$mark-bg:                     #fcf8e3;
```

## Customize

### Color

```html
<p class="text-primary"> Primary color</p>
<p class="text-muted"> Primary color</p>

```

### bg color

```html
<p class="text-white bg-primary">  whitetext on Primary</p>
<p class="text-white bg-secondary">whitetext on secondary </p>
<p class="text-dark bg-danger">white text on secondary </p>
```

## Components

### Buttons

```html
<button type="button" class="btn btn-primary">Primary</button>
<button class="btn btn-primary"> Submit</button>
<button class="btn btn-outline-primary">Primary colore outline ou</button>
<button class="btn btn-outline-secondary btn-lg">large Primary colore outline ou</button>
```

### anchor tags

```html
<a href="#" class="btn btn-info"> info anchor</a>

```

### Button Size

```html
button class="btn btn-lg btn-danger"> large danager button </button>
<button class="btn btn-sm btn-Warning"> small warning  button </button>
```

```html
<!--using button group /// no space between them -->
<div class="btn-group">
    <a href="#" class="btn btn-primary"> button1</a>
    <a href="#" class="btn btn-secondary"> button2</a>
    <a href="#" class="btn btn-success"> button3</a>
</div>
```

## Utilities

### Margin and padding

```html
<div class="bg-primary  m-5 p-1"> small margin and padding </div>
```

margin and padding by using classes for margin m-1 ( small) m-5(lage) and same for padding 

```html
<div class="bg-primary  my-3 px-5"> margin y direction, padding in x direction </div>
```

y is the up and down direction and x is  the left and right direction 

```html
<div class="bg-primary  mt-3 mb-4  ps-5 pe-2  pb-1"> margin y direction, padding in x direction </div>
```

we ca use for each margin top margin bottom and margin start and end

###