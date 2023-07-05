# INTRODUCTION TO CSS

## What Is CSS

CSS is a standard style sheet language used for describing the presentation (i.e. the layout and formatting) of the web pages.

## Including CSS to html

### External CSS​

Use

```css
<link rel=“stylesheet” href=“path to CSS file”>
```

### Inline CSS​

- This is using CSS in the HTML file within the selector​

### Internal CSS​

- This is using CSS in the HTML file outside the selector​

## Syntax

A CSS comprises of style rules that are interpreted by the browser and then applied to the corresponding elements in your document. A style rule is made of three parts −​

- **Selector** − A selector is an HTML tag at which a style will be applied ,eg <h1>.​

- **Property** − A property is a type of attribute of HTML tag, eg color​

- **Value** − Values are assigned to properties. Eg, color property can have value either red.​

Syntax:

```css
selector { property: value }​
```

Example:

```css
 h1 { color: red }​
```

## selectors

**Type selector** – selects elements of a specific type. Eg table, h2,  p​

**Universal selector** – matches the name of any element type.  (*)​

**Descendant selector** – selects an element only if it lies in the given element. Eg ul li​

**Class selectors** - defines style rules based on the class attribute of the elements. ​

**ID selectors** - defines style rules based on the id attribute of the elements.​

**Child selectors** - selects an element only if it is a direct child of the given element. E.g., ul > li​

**Attribute selectors** -  applies styles to HTML elements with a particular attribute. E.g., input[type=“submit”]

## CSS RULES OVERRIDING​

**Any inline style sheet takes highest priority. So, it will override any rule defined in ```css <style>...</style>``` tags or rules defined in any external style sheet file.​

**Any rule defined in ```css <style>...</style>``` tags will override rules defined in any external style sheet file.​

**Any rule defined in external style sheet file takes lowest priority, and rules defined in this file will be applied only when above two rules are not applicable.

## MEASUREMENTS UNITS​

​![css measurements](/images/measurements.png)
