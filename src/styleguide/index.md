# Colors

<p class="lead">Below you can find the different values we created that support the primary color variable you can change at any time in <code>\_settings.scss</code></p>

---

## Brand colors

<div class="row up-1 medium-up-3">
	<div class="column">
		<div class="color-block primary-color">
			<span></span>
			Primary:&nbsp;
		</div>
	</div>
	<div class="column">
		<div class="color-block primary-color-light">
			<span></span>
			Primary light:&nbsp;
		</div>
	</div>
	<div class="column">
		<div class="color-block primary-color-dark">
			<span></span>
			Primary dark:&nbsp;
		</div>
	</div>
	<div class="column">
		<div class="color-block secondary-color">
			<span></span>
			Secondary:&nbsp;
		</div>
	</div>
	<div class="column">
		<div class="color-block secondary-color-light">
			<span></span>
			Secondary light:&nbsp;
		</div>
	</div>
	<div class="column">
		<div class="color-block secondary-color-dark">
			<span></span>
			Secondary dark:&nbsp;
		</div>
	</div>
  <div class="column">
    <div class="color-block tertiary-color">
      <span></span>
      Tertiary:&nbsp;
    </div>
  </div>
  <div class="column">
    <div class="color-block tertiary-color-light">
      <span></span>
      Tertiary light:&nbsp;
    </div>
  </div>
  <div class="column">
    <div class="color-block tertiary-color-dark">
      <span></span>
      Tertiary dark:&nbsp;
    </div>
  </div>
</div>

---

## Typography colors

<div class="row up-1 medium-up-3">
	<div class="column">
		<div class="color-block text-color">
			<span></span>
			Text:&nbsp;
		</div>
	</div>
	<div class="column">
		<div class="color-block headings-color">
			<span></span>
			Headings:&nbsp;
		</div>
	</div>
</div>

---

## Shades of grey

<div class="row up-1 medium-up-3">
	<div class="column">
		<div class="color-block grey-lighter-color">
			<span></span>
			Grey lighter:&nbsp;
		</div>
	</div>
	<div class="column">
		<div class="color-block grey-light-color">
			<span></span>
			Grey light:&nbsp;
		</div>
	</div>
	<div class="column">
		<div class="color-block grey-color">
			<span></span>
			Grey:&nbsp;
		</div>
	</div>
	<div class="column">
		<div class="color-block grey-dark-color">
			<span></span>
			Grey dark:&nbsp;
		</div>
	</div>
	<div class="column">
		<div class="color-block grey-darker-color">
			<span></span>
			Grey darker:&nbsp;
		</div>
	</div>
</div>

---

## Form colors

<div class="row up-1 medium-up-3">
	<div class="column">
		<div class="color-block valid-color">
			<span></span>
			Valid:&nbsp;
		</div>
	</div>
	<div class="column">
		<div class="color-block invalid-color">
			<span></span>
			Invalid:&nbsp;
		</div>
	</div>
	<div class="column">
		<div class="color-block warning-color">
			<span></span>
			Warning:&nbsp;
		</div>
	</div>
	<div class="column">
		<div class="color-block placeholder-color">
			<span></span>
			Placeholder:&nbsp;
		</div>
	</div>
</div>



# Typography

<p class="lead">This design uses Roboto light, regular and medium for headings and paragraph text.</p>

---

## Headings

Headings are used to denote different sections of content, usually consisting of related paragraphs and other HTML elements. They range from h1 to h6 and should be styled in a clear hierarchy (i.e., largest to smallest)

---

## Paragraphs

Paragraphs are groups of sentences, each with a lead (first sentence) and transition (last sentence). They are block level elements, meaning they stack vertically when repeated. Use them as such.

---

<div class="baseline-grid">
<h1>Heading Level 1</h1>

<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Hic quibusdam ratione sunt dolorum, qui illo maxime doloremque accusantium cum libero eum, a optio odio placeat debitis ullam aut non distinctio.</p>

<h2>Heading Level 2 Heading Level 2</h2>

<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Hic quibusdam ratione sunt dolorum, qui illo maxime doloremque accusantium cum libero eum, a optio odio placeat debitis ullam aut non distinctio.</p>

<h3>Heading Level 3 Heading Level 3 Heading Level 3</h3>

<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Hic quibusdam ratione sunt dolorum, qui illo maxime doloremque accusantium cum libero eum, a optio odio placeat debitis ullam aut non distinctio.</p>

<h4>Heading Level 4 Heading Level 4 Heading Level 4 Heading Level 4</h4>

<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Hic quibusdam ratione sunt dolorum, qui illo maxime doloremque accusantium cum libero eum, a optio odio placeat debitis ullam aut non distinctio.</p>

<h5>Heading Level 5</h5>

<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Hic quibusdam ratione sunt dolorum, qui illo maxime doloremque accusantium cum libero eum, a optio odio placeat debitis ullam aut non distinctio.</p>

<h6>Heading Level 6</h6>

<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Hic quibusdam ratione sunt dolorum, qui illo maxime doloremque accusantium cum libero eum, a optio odio placeat debitis ullam aut non distinctio.</p>
</div>




# The Grid

<p class="lead">Problem: You've got tons of content, each needing different sized vertical columns, and don't know how to quick and easily get it all done. Solution: The awesome grid!</p>

---

## Overview

The grid is built around two key elements: rows and columns. Rows create a max-width and contain the columns, and columns create the final structure. Everything on your page that you don't give a specific structural style to should be within a row or column.

---

## Nesting

In the Grid you can nest columns down as far as you'd like. Just embed rows inside columns and go from there. Each embedded row can contain up to 12 columns.

---

## How to Use

Using this framework is easy. Here's how your code will look when you use a series of <div> tags to create vertical columns.

```html
<div class="row">
	<div class="small-6 medium-4 large-3 columns">...</div>
	<div class="small-6 medium-8 large-9 columns">...</div>
</div>
```

<div class="row display">
	<div class="small-12 large-4 columns">4</div>
	<div class="small-12 large-4 columns">4</div>
	<div class="small-12 large-4 columns">4</div>
</div>
<div class="row display">
	<div class="small-12 large-3 columns">3</div>
	<div class="small-12 large-6 columns">6</div>
	<div class="small-12 large-3 columns">3</div>
</div>
<div class="row display">
	<div class="small-12 large-2 columns">2</div>
	<div class="small-12 large-8 columns">8</div>
	<div class="small-12 large-2 columns">2</div>
</div>
<div class="row display">
	<div class="small-12 large-3 columns">3</div>
	<div class="small-12 large-9 columns">9</div>
</div>
<div class="row display">
	<div class="small-12 large-4 columns">4</div>
	<div class="small-12 large-8 columns">8</div>
</div>
<div class="row display">
	<div class="small-12 large-5 columns">5</div>
	<div class="small-12 large-7 columns">7</div>
</div>
<div class="row display">
	<div class="small-12 large-6 columns">6</div>
	<div class="small-12 large-6 columns">6</div>
</div>

---

## Nesting Rows

In the Grid you can nest columns down as far as you'd like. Just embed rows inside columns and go from there. Each embedded row can contain up to 12 columns.

```html
<div class="row">
	<div class="small-8 columns">8
		<div class="row">
			<div class="small-8 columns">8 Nested
				<div class="row">
					<div class="small-8 columns">8 Nested Again</div>
					<div class="small-4 columns">4</div>
				</div>
			</div>
			<div class="small-4 columns">4</div>
		</div>
	</div>
	<div class="small-4 columns">4</div>
</div>
```

<div class="row display">
	<div class="small-8 columns">8
		<div class="row">
			<div class="small-8 columns">8 Nested
				<div class="row">
					<div class="small-8 columns">8 Nested Again</div>
					<div class="small-4 columns">4</div>
				</div>
			</div>
			<div class="small-4 columns">4</div>
		</div>
	</div>
	<div class="small-4 columns">4</div>
</div>

---

## Small Grid

As you've probably noticed in the examples above, you have access to a small, medium, and large grid. If you know that your grid structure will be the same for small devices as it will be on large devices, just use the small grid. You can override your small grid classes by adding medium or large grid classes.

```html
<div class="row">
	<div class="small-2 columns">2</div>
	<div class="small-10 columns">10, last</div>
</div>
<div class="row">
	<div class="small-3 columns">3</div>
	<div class="small-9 columns">9, last</div>
</div>
```

<div class="row display">
	<div class="small-2 columns">2</div>
	<div class="small-10 columns">10, last</div>
</div>
<div class="row display">
	<div class="small-3 columns">3</div>
	<div class="small-9 columns">9, last</div>
</div>




# Spacing

The basic unit for spacing is set by the body text line height. From this, we set different spacing sizes by multiplying or dividing the variable.

---

## Grid spacing

<div class="gutter-small">Gutter small :</div>

<div class="gutter-medium">Gutter medium :</div>

---

### Stack spacing

Vertical space between stacked elements.

**Sizes**

<div class="space-stack-xxxtiny"></div>
<div class="space-stack-xxtiny"></div>
<div class="space-stack-xtiny"></div>
<div class="space-stack-tiny"></div>
<div class="space-stack-small"></div>
<div class="space-stack-medium"></div>
<div class="space-stack-large"></div>
<div class="space-stack-xlarge"></div>
<div class="space-stack-xxlarge"></div>
<div class="space-stack-xxxlarge"></div>

---

### Inline spacing

Horizontal space between inline elements.

**Sizes**

<div class="space-inline-xxxtiny"></div>
<div class="space-inline-xxtiny"></div>
<div class="space-inline-xtiny"></div>
<div class="space-inline-tiny"></div>
<div class="space-inline-small"></div>
<div class="space-inline-medium"></div>
<div class="space-inline-large"></div>
<div class="space-inline-xlarge"></div>
<div class="space-inline-xxlarge"></div>
<div class="space-inline-xxxlarge"></div>

---

### Inset spacing

<blockquote>
	<p>An inset offers indents content on all four sides like the matte of the framed photo on a wall. It’s use is widespread, across many components at varying sizes, whether our 3-Up module and block messages medium feel, extra compact pills, or spacious footers and mastheads.</p>
	<footer>
		<i>— <a href="https://medium.com/eightshapes-llc/space-in-design-systems-188bcbae0d62#.knecyjj74">Source</a></i>
	</footer>
</blockquote>

**Sizes**

<div class="space-inset-xxxtiny"></div>
<div class="space-inset-xxtiny"></div>
<div class="space-inset-xtiny"></div>
<div class="space-inset-tiny"></div>
<div class="space-inset-small"></div>
<div class="space-inset-medium"></div>
<div class="space-inset-large"></div>
<div class="space-inset-xlarge"></div>
<div class="space-inset-xxlarge"></div>
<div class="space-inset-xxxlarge"></div>

---

### Squish inset spacing

<blockquote>
	<p>A squished inset reduces space top and bottom, in our case by 50%. While less common than its squared counterpart, a squish occurred frequently in elements (like a button) and cell-like containers like a data table or list item.</p>
	<footer>
		<i>— <a href="https://medium.com/eightshapes-llc/space-in-design-systems-188bcbae0d62#.knecyjj74">Source</a></i>
	</footer>
</blockquote>

**Sizes**

<div class="space-inset-squish-xxxtiny"></div>
<div class="space-inset-squish-xxtiny"></div>
<div class="space-inset-squish-xtiny"></div>
<div class="space-inset-squish-tiny"></div>
<div class="space-inset-squish-small"></div>
<div class="space-inset-squish-medium"></div>
<div class="space-inset-squish-large"></div>
<div class="space-inset-squish-xlarge"></div>
<div class="space-inset-squish-xxlarge"></div>
<div class="space-inset-squish-xxxlarge"></div>

---

### Stretch inset spacing

<blockquote>
	<p>Contrasted with a button or pill’s squish, we found ourselves vertically stretching the insets of textboxes, textareas, and other form elements.</p>
	<footer>
		<i>— <a href="https://medium.com/eightshapes-llc/space-in-design-systems-188bcbae0d62#.knecyjj74">Source</a></i>
	</footer>
</blockquote>

**Sizes**

<div class="space-inset-stretch-xxxtiny"></div>
<div class="space-inset-stretch-xxtiny"></div>
<div class="space-inset-stretch-xtiny"></div>
<div class="space-inset-stretch-tiny"></div>
<div class="space-inset-stretch-small"></div>
<div class="space-inset-stretch-medium"></div>
<div class="space-inset-stretch-large"></div>
<div class="space-inset-stretch-xlarge"></div>
<div class="space-inset-stretch-xxlarge"></div>
<div class="space-inset-stretch-xxxlarge"></div>




# Icons

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatem, fugit perspiciatis laudantium amet totam enim blanditiis nisi aperiam. Vitae quod voluptatum, repudiandae laboriosam repellendus optio iusto et natus distinctio maiores.

```html_example
<span class="icon-example"></span>
```




# Buttons

---

## Primary Buttons

These buttons are primary calls to action and should be used sparingly. Their size can be adjusted with the `.tiny`, `.small`, and `.large` classes.

{{#> button class="large"}}Lorem{{/button}}

```html_example
<a href="#" class="button button-primary large">Large button</a>
<a href="#" class="button button-primary">Regular button</a>
<a href="#" class="button button-primary small">Small button</a>
<a href="#" class="button button-primary tiny">Tiny button</a>
<br>
<a href="#" class="button button-primary large">Large button<br>two line</a>
<a href="#" class="button button-primary">Regular button<br>two line</a>
<a href="#" class="button button-primary small">Small button<br>two line</a>
<a href="#" class="button button-primary tiny">Tiny button<br>two line</a>
```

---

## Secondary Buttons

These buttons are used for less important, secondary actions on a page.

```html_example
<a href="#" class="button button-secondary large">Large button</a>
<a href="#" class="button button-secondary">Regular button</a>
<a href="#" class="button button-secondary small">Small button</a>
<a href="#" class="button button-secondary tiny">Tiny button</a>
<br>
<a href="#" class="button button-secondary large">Large button<br>two line</a>
<a href="#" class="button button-secondary">Regular button<br>two line</a>
<a href="#" class="button button-secondary small">Small button<br>two line</a>
<a href="#" class="button button-secondary tiny">Tiny button<br>two line</a>
```

---

## Tertiary Buttons

These buttons are used for less important, tertiary actions on a page.

```html_example
<a href="#" class="button button-tertiary large">Large button</a>
<a href="#" class="button button-tertiary">Regular button</a>
<a href="#" class="button button-tertiary small">Small button</a>
<a href="#" class="button button-tertiary tiny">Tiny button</a>
<br>
<a href="#" class="button button-tertiary large">Large button<br>two line</a>
<a href="#" class="button button-tertiary">Regular button<br>two line</a>
<a href="#" class="button button-tertiary small">Small button<br>two line</a>
<a href="#" class="button button-tertiary tiny">Tiny button<br>two line</a>
```

---

## Ghost Buttons

These buttons are used for less important, tertiary actions on a page.

```html_example
<a href="#" class="button hollow button-primary large">Large button</a>
<a href="#" class="button hollow button-primary">Regular button</a>
<a href="#" class="button hollow button-primary small">Small button</a>
<a href="#" class="button hollow button-primary tiny">Tiny button</a>
<br>
<a href="#" class="button hollow button-primary large">Large button<br>two line</a>
<a href="#" class="button hollow button-primary">Regular button<br>two line</a>
<a href="#" class="button hollow button-primary small">Small button<br>two line</a>
<a href="#" class="button hollow button-primary tiny">Tiny button<br>two line</a>
```

```html_example
<a href="#" class="button hollow button-secondary large">Large button</a>
<a href="#" class="button hollow button-secondary">Regular button</a>
<a href="#" class="button hollow button-secondary small">Small button</a>
<a href="#" class="button hollow button-secondary tiny">Tiny button</a>
<br>
<a href="#" class="button hollow button-secondary large">Large button<br>two line</a>
<a href="#" class="button hollow button-secondary">Regular button<br>two line</a>
<a href="#" class="button hollow button-secondary small">Small button<br>two line</a>
<a href="#" class="button hollow button-secondary tiny">Tiny button<br>two line</a>
```

```html_example
<a href="#" class="button hollow button-tertiary large">Large button</a>
<a href="#" class="button hollow button-tertiary">Regular button</a>
<a href="#" class="button hollow button-tertiary small">Small button</a>
<a href="#" class="button hollow button-tertiary tiny">Tiny button</a>
<br>
<a href="#" class="button hollow button-tertiary large">Large button<br>two line</a>
<a href="#" class="button hollow button-tertiary">Regular button<br>two line</a>
<a href="#" class="button hollow button-tertiary small">Small button<br>two line</a>
<a href="#" class="button hollow button-tertiary tiny">Tiny button<br>two line</a>
```

---

## Buttons with icons

These buttons are used for lesser important actions on a page, sometimes used beside a filled button to create hierarchy.

**Icon on the right:**

```html_example
<a href="#" class="button button-primary button-icon-right icon-arrow-right large">Large button</a>
<a href="#" class="button button-primary button-icon-right icon-arrow-right">Regular button</a>
<a href="#" class="button button-primary button-icon-right icon-arrow-right small">Small button</a>
<a href="#" class="button button-primary button-icon-right icon-arrow-right tiny">Tiny button</a>
<br>
<a href="#" class="button button-primary button-icon-right icon-arrow-right large">Large button<br>two line</a>
<a href="#" class="button button-primary button-icon-right icon-arrow-right">Regular button<br>two line</a>
<a href="#" class="button button-primary button-icon-right icon-arrow-right small">Small button<br>two line</a>
<a href="#" class="button button-primary button-icon-right icon-arrow-right tiny">Tiny button<br>two line</a>
```

**Icon on the left:**

```html_example
<a href="#" class="button button-primary button-icon-left icon-arrow-left large">Large button</a>
<a href="#" class="button button-primary button-icon-left icon-arrow-left">Regular button</a>
<a href="#" class="button button-primary button-icon-left icon-arrow-left small">Small button</a>
<a href="#" class="button button-primary button-icon-left icon-arrow-left tiny">Tiny button</a>
<br>
<a href="#" class="button button-primary button-icon-left icon-arrow-left large">Large button<br>two line</a>
<a href="#" class="button button-primary button-icon-left icon-arrow-left">Regular button<br>two line</a>
<a href="#" class="button button-primary button-icon-left icon-arrow-left small">Small button<br>two line</a>
<a href="#" class="button button-primary button-icon-left icon-arrow-left tiny">Tiny button<br>two line</a>
```

**It works with hollow buttons and different colors too!**

```html_example
<a href="#" class="button hollow button-secondary button-icon-right icon-arrow-right large">Large button</a>
<a href="#" class="button hollow button-secondary button-icon-right icon-arrow-right">Regular button</a>
<a href="#" class="button hollow button-secondary button-icon-right icon-arrow-right small">Small button</a>
<a href="#" class="button hollow button-secondary button-icon-right icon-arrow-right tiny">Tiny button</a>
<br>
<a href="#" class="button hollow button-secondary button-icon-right icon-arrow-right large">Large button<br>two line</a>
<a href="#" class="button hollow button-secondary button-icon-right icon-arrow-right">Regular button<br>two line</a>
<a href="#" class="button hollow button-secondary button-icon-right icon-arrow-right small">Small button<br>two line</a>
<a href="#" class="button hollow button-secondary button-icon-right icon-arrow-right tiny">Tiny button<br>two line</a>
```



# Forms

<p class="lead">Use forms to allow users to interact with the site and provide information to the company.</p>

---

## Elements of a Form

A form should be marked up using its default HTML properties. The ones we make use of include (in hierarchical order):

- Form
- Label
- Input
- Select
- Text area
- Button

---

## How to Use

Make forms great and easy to use with the following rules:

- Wrap checkboxes and radio buttons within labels for larger hit areas, and be sure to set the for, name, and id attributes for all applicable elements.
- Series of checkboxes and radio buttons below within a `<ul class="inline-list">`.
- Before selecting any set of fields to use for a required input, explore other options (e.g., radio buttons over select lists).
- Add a `class="inputrow"` to an element encompassing an input field and its label.

---

## UX optimizations

Use a `placeholder="lorem"` for any field within the form (except radio buttons and checkboxes). Use also `autocorrect="off"` to prevent this feature on touch devices.
Font size on input fields must be at least 16px to prevent iPhone devices to zoom in on focus.

### Number inputs

Use `type="tel"` to trigger the number keyboard on touch devices.

```
<div class="inputrow row">
  <div class="large-5 columns">
    <label for="montant">Montant</label>
  </div>
  <div class="large-7 columns">
    <input id="montant" type="tel" name="montant" required autocorrect="off" placeholder="Exemple : 4000 €">
  </div>
</div>
```

### Name inputs

Use `autocomplete="family-name"` and `autocomplete="given-name"`

```
<div class="inputrow row">
  <div class="large-5 columns">
    <label for="nom">Nom</label>
  </div>
  <div class="large-7 columns">
    <input id="nom" type="text" name="nom" required autocorrect="off" autocomplete="family-name" placeholder="Exemple : Garcia">
  </div>
</div>

<div class="inputrow row">
  <div class="large-5 columns">
    <label for="prenom">Prénom</label>
  </div>
  <div class="large-7 columns">
    <input id="prenom" type="text" name="prenom" required autocorrect="off" autocomplete="given-name" placeholder="Exemple : John">
  </div>
</div>
```

### Emails

Use `type="email"` to trigger the email keyboard on touch devices, `autocapitalise="off"` and `autocomplete="email"`

```
<div class="inputrow row">
  <div class="large-5 columns">
    <label for="email">e-mail</label>
  </div>
  <div class="large-7 columns">
    <input id="email" type="email" name="email" required autocorrect="off" autocapitalize="off" autocomplete="email" placeholder="Exemple : rsaintandre@email.com">
  </div>
</div>
```

### Phone numbers

Use `type="tel"` to trigger the number keyboard on touch devices and `autocomplete="tel"`. Set `maxlength="10"` to prevent wrong phone numbers.

```
<div class="inputrow row">
  <div class="large-5 columns">
    <label for="telephone">Téléphone</label>
  </div>
  <div class="large-7 columns">
    <input id="telephone" type="tel" name="telephone" required maxlength="10" autocorrect="off" autocomplete="tel" placeholder="Exemple : 0678236190">
  </div>
</div>
```

### Address

Use `autocomplete="street-address"`.

```
<div class="inputrow row">
  <div class="large-5 columns">
    <label for="adresse">Votre adresse</label>
  </div>
  <div class="large-7 columns">
    <input id="adresse" type="text" name="adresse" required autocorrect="off" autocomplete="street-address" placeholder="Exemple : 165 Rue du Faubourg Saint-Honoré">
  </div>
</div>
```

### Postal codes and cities

Use `type="tel"` on postal code input to trigger the number keyboard on touch devices and `autocomplete="postal-code"`. Set `maxlength="5"` to prevent wrong codes.
The city input is autocompleted regarding the postal code entered.

```
<div class="inputrow row">
  <div class="large-5 columns">
    <label for="insee">Code postal</label>
  </div>
  <div class="large-7 columns">
    <input id="insee" class="cp" type="tel" name="cp_insee" maxlength="5" required autocorrect="off" autocomplete="postal-code" placeholder="Exemple : 75008">
    <span class="autocomplete-input"><input type="hidden" name="insee"></span>
  </div>
</div>
```

### Dates

Use `type="tel"` to trigger the number keyboard on touch devices AND prevent a bug regarding the masked-input.js plugin on some android platforms.
Use `autocapitalise="off"` and `autocomplete="tel"`. Don't set `maxlength="8"` but higher to set room for slashes.

```
<div class="inputrow row">
  <div class="large-5 columns">
    <label for="date_naissance">Date</label>
  </div>
  <div class="large-7 columns">
    <input id="date_naissance" class="date_input date_naissance" type="tel" name="date_naissance" maxlength="20" required placeholder="JJ/MM/AAAA">
  </div>
</div>
```

---

## Form Layouts

Form elements in Foundation are styled based on their type attribute rather than a class. Inputs in Foundation have another major advantage — they are full width by default. That means that inputs will run as wide as the column that contains them. However, you have two options which make these forms extremely versatile:

- You can size inputs using column sizes, like `.medium-6`, `.small-6`.
- You can create row elements inside your form and use columns for the form, including inputs, labels and more. Rows inside a form inherit some special padding to even up input spacing.

---

## Form Example

```html_example
<form>
  <div class="inputrow row">
    <div class="medium-5 columns">
      <label>Label</label>
    </div>
    <div class="medium-7 columns">
      <input type="text" placeholder="placeholder">
    </div>
  </div>
  <div class="inputrow row">
    <div class="medium-5 columns">
      <label for="label-tooltip" data-tooltip aria-haspopup="true" class="has-tip" data-disable-hover="false" title="This label has a tooltip">Label with tooltip</label>
    </div>
    <div class="medium-7 columns">
      <input id="label-tooltip" type="text" placeholder="placeholder">
    </div>
  </div>
  <div class="inputrow row">
    <div class="medium-5 columns">
      <label>Label</label>
    </div>
    <div class="medium-7 columns">
      <div class="row collapse">
        <div class="small-9 columns">
          <input type="text" placeholder="placeholder">
        </div>
        <div class="small-3 columns">
          <span class="postfix">.com</span>
        </div>
      </div>
    </div>
  </div>
  <div class="inputrow row">
    <div class="medium-5 columns">
      <label>Label</label>
    </div>
    <div class="medium-7 columns">
      <select>
        <option value="good">Good</option>
        <option value="better">Better</option>
        <option value="best">Best</option>
      </select>
    </div>
  </div>
  <div class="inputrow row">
    <div class="medium-5 columns">
      <label>Choose Your Favorite</label>
    </div>
    <div class="medium-7 columns">
      <input type="radio" name="radio" value="radio1" id="radio1"><label for="radio1">Red</label>
      <input type="radio" name="radio" value="radio2" id="radio2"><label for="radio2">Blue</label>
    </div>
  </div>
  <div class="inputrow row">
    <div class="medium-5 columns">
      <label>Check these out</label>
    </div>
    <div class="medium-7 columns">
      <input id="checkbox1" type="checkbox" name="checkbox"><label for="checkbox1">Checkbox 1</label>
      <input id="checkbox2" type="checkbox" name="checkbox"><label for="checkbox2">Checkbox 2</label>
    </div>
  </div>
  <div class="inputrow row">
    <div class="medium-5 columns">
      <label>Textarea Label</label>
    </div>
    <div class="medium-7 columns">
      <textarea placeholder="placeholder"></textarea>
    </div>
  </div>
</form>
```
