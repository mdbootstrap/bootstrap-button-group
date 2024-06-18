# Free Bootstrap Button Group Component

Responsive button group built with the latest Bootstrap 5. Button group wraps a series of buttons together into a single line (navbar) or stack in a vertical column. Many examples and simple tutorials.

Group a series of buttons together on a single line with the button group.

<p><strong>How to use it?</strong></p>
<p class="mb-2">
<strong>1. </strong>Download<a target="_blank" href="https://mdbootstrap.com/docs/standard/"> MDB 5 - free UI KIT</a></p>
<p class="mb-2"><strong>2. </strong>Choose your favourite customized example and click <code>show code</code> to see the code</p>
<p class="mb-3"><strong>3. </strong>Copy & paste the code into your MDB project</p>

--------------------

[📄 **Documentation & usage guide**](https://mdbootstrap.com/docs/standard/components/button-group/)

These components were built with a **free Material Design UI Kit for the latest Bootstrap 5**.

<img height="25" src="https://mdbootstrap.com/img/Marketing/general/logo/medium/mdb-r.png">  [![GitHub Stars](https://img.shields.io/github/stars/mdbootstrap/mdb-ui-kit?label=Star%20now&style=social)](https://github.com/mdbootstrap/mdb-ui-kit/)

---------------------

 <h2 class="mb-4">Basic example</h2> 
 
```html
<div class="btn-group" role="group" aria-label="Basic example">
  <button type="button" class="btn btn-primary"  data-mdb-ripple-init>Left</button>
  <button type="button" class="btn btn-primary"  data-mdb-ripple-init>Middle</button>
  <button type="button" class="btn btn-primary"  data-mdb-ripple-init>Right</button>
</div>
```

```html
<div class="btn-group">
  <a href="#!" class="btn btn-primary active"  data-mdb-ripple-init>Active link</a>
  <a href="#!" class="btn btn-primary"  data-mdb-ripple-init>Link</a>
  <a href="#!" class="btn btn-primary"  data-mdb-ripple-init>Link</a>
</div>
```

```css
// Initialization for ES Users
import { Ripple, initMDB } from "mdb-ui-kit";

initMDB({ Ripple });
```

 
 <hr class="my-5">
 
 <h2 class="mb-4">Outlined styles</h2> 
 
```html
<div class="btn-group shadow-0" role="group" aria-label="Basic example">
  <button type="button" class="btn btn-outline-secondary" data-mdb-color="dark"  data-mdb-ripple-init>Left</button>
  <button type="button" class="btn btn-outline-secondary" data-mdb-color="dark"  data-mdb-ripple-init>Middle</button>
  <button type="button" class="btn btn-outline-secondary" data-mdb-color="dark"  data-mdb-ripple-init>Right</button>
</div>
```

```css
// Initialization for ES Users
import { Ripple, initMDB } from "mdb-ui-kit";

initMDB({ Ripple });
```

 <hr class="my-5">
 
 <h2 class="mb-4">Toolbar</h2> 
 
```html
<div class="btn-toolbar" role="toolbar" aria-label="Toolbar with button groups">
  <div class="btn-group me-2" role="group" aria-label="First group">
    <button type="button" class="btn btn-primary"  data-mdb-ripple-init>1</button>
    <button type="button" class="btn btn-primary"  data-mdb-ripple-init>2</button>
    <button type="button" class="btn btn-primary"  data-mdb-ripple-init>3</button>
    <button type="button" class="btn btn-primary"  data-mdb-ripple-init>4</button>
  </div>
  <div class="btn-group me-2" role="group" aria-label="Second group">
    <button type="button" class="btn btn-primary"  data-mdb-ripple-init>5</button>
    <button type="button" class="btn btn-primary"  data-mdb-ripple-init>6</button>
    <button type="button" class="btn btn-primary"  data-mdb-ripple-init>7</button>
  </div>
  <div class="btn-group" role="group" aria-label="Third group">
    <button type="button" class="btn btn-primary"  data-mdb-ripple-init>8</button>
  </div>
</div>
```

```html
<div class="btn-toolbar mb-3" role="toolbar" aria-label="Toolbar with button groups">
  <div class="btn-group me-2" role="group" aria-label="First group">
    <button type="button" class="btn btn-primary"  data-mdb-ripple-init>1</button>
    <button type="button" class="btn btn-primary"  data-mdb-ripple-init>2</button>
    <button type="button" class="btn btn-primary"  data-mdb-ripple-init>3</button>
    <button type="button" class="btn btn-primary"  data-mdb-ripple-init>4</button>
  </div>
  <div class="input-group">
    <div class="input-group-text" id="btnGroupAddon">@</div>
    <input
      type="text"
      class="form-control"
      placeholder="Input group example"
      aria-label="Input group example"
      aria-describedby="btnGroupAddon"
    />
  </div>
</div>

<div class="btn-toolbar justify-content-between" role="toolbar" aria-label="Toolbar with button groups">
  <div class="btn-group" role="group" aria-label="First group">
    <button type="button" class="btn btn-primary" data-mdb-ripple-init>1</button>
    <button type="button" class="btn btn-primary" data-mdb-ripple-init>2</button>
    <button type="button" class="btn btn-primary" data-mdb-ripple-init>3</button>
    <button type="button" class="btn btn-primary" data-mdb-ripple-init>4</button>
  </div>
  <div class="input-group">
    <div class="input-group-text" id="btnGroupAddon2">@</div>
    <input
      type="text"
      class="form-control"
      placeholder="Input group example"
      aria-label="Input group example"
      aria-describedby="btnGroupAddon2"
    />
  </div>
</div>
```

```html
// Initialization for ES Users
import { Ripple, initMDB } from "mdb-ui-kit";

initMDB({ Ripple });
```

 <hr class="my-5">
 <h2 class="mb-4">Sizing

</h2> 
 
```html
<!-- Large -->
<div class="btn-group btn-group-lg" role="group" aria-label="Basic example">
  <button type="button" class="btn btn-primary"  data-mdb-ripple-init>Left</button>
  <button type="button" class="btn btn-primary"  data-mdb-ripple-init>Middle</button>
  <button type="button" class="btn btn-primary"  data-mdb-ripple-init>Right</button>
</div>

<!-- Standard -->
<div class="btn-group" role="group" aria-label="Basic example">
  <button type="button" class="btn btn-primary"  data-mdb-ripple-init>Left</button>
  <button type="button" class="btn btn-primary"  data-mdb-ripple-init>Middle</button>
  <button type="button" class="btn btn-primary"  data-mdb-ripple-init>Right</button>
</div>

<!-- Small -->
<div class="btn-group btn-group-sm" role="group" aria-label="Basic example">
  <button type="button" class="btn btn-primary"  data-mdb-ripple-init>Left</button>
  <button type="button" class="btn btn-primary"  data-mdb-ripple-init>Middle</button>
  <button type="button" class="btn btn-primary"  data-mdb-ripple-init>Right</button>
</div>
```

```html
// Initialization for ES Users
import { Ripple, initMDB } from "mdb-ui-kit";

initMDB({ Ripple });
```

 <hr class="my-5">
 <h2 class="mb-4">Pills

</h2> 
 
```html
<span class="badge rounded-pill badge-primary">Primary</span>
<span class="badge rounded-pill badge-secondary">Secondary</span>
<span class="badge rounded-pill badge-success">Success</span>
<span class="badge rounded-pill badge-danger">Danger</span>
<span class="badge rounded-pill badge-warning">Warning</span>
<span class="badge rounded-pill badge-info">Info</span>
<span class="badge rounded-pill badge-light">Light</span>
<span class="badge rounded-pill badge-dark">Dark</span>
```

 <hr class="my-5">
 <h2 class="mb-4">Nesting
</h2> 
 
```html
<div class="btn-group" role="group" aria-label="Button group with nested dropdown">
  <button type="button" class="btn btn-primary" data-mdb-ripple-init>1</button>
  <button type="button" class="btn btn-primary" data-mdb-ripple-init>2</button>
  <div class="btn-group" role="group">
    <button
      id="btnGroupDrop1"
      type="button"
      class="btn btn-primary dropdown-toggle"
      aria-expanded="false"
      data-mdb-ripple-init
      data-mdb-dropdown-init
    >
      Dropdown
    </button>
    <ul class="dropdown-menu" aria-labelledby="btnGroupDrop1">
      <li><a class="dropdown-item" href="#">Dropdown link</a></li>
      <li><a class="dropdown-item" href="#">Dropdown link</a></li>
    </ul>
  </div>
</div>
```
```css
// Initialization for ES Users
import { Ripple, Dropdown, initMDB } from "mdb-ui-kit";

initMDB({ Ripple, Dropdown });
```

 <hr class="my-5">
 <h2 class="mb-4">Vertical variation
</h2> 
 
```html
<div class="btn-group-vertical" role="group" aria-label="Vertical button group">
  <button type="button" class="btn btn-primary"  data-mdb-ripple-init>Button</button>
  <button type="button" class="btn btn-primary"  data-mdb-ripple-init>Button</button>
  <button type="button" class="btn btn-primary"  data-mdb-ripple-init>Button</button>
  <button type="button" class="btn btn-primary"  data-mdb-ripple-init>Button</button>
  <button type="button" class="btn btn-primary"  data-mdb-ripple-init>Button</button>
  <button type="button" class="btn btn-primary"  data-mdb-ripple-init>Button</button>
</div>
```
```html
<div class="btn-group-vertical" role="group" aria-label="Vertical button group">
  <button type="button" class="btn btn-primary" data-mdb-ripple-init>Button</button>
  <button type="button" class="btn btn-primary" data-mdb-ripple-init>Button</button>
  <div class="btn-group" role="group">
    <button
      id="btnGroupVerticalDrop1"
      type="button"
      class="btn btn-primary dropdown-toggle"
      aria-expanded="false"
      data-mdb-ripple-init
      data-mdb-dropdown-init
    >
      Dropdown
    </button>
    <ul class="dropdown-menu" aria-labelledby="btnGroupVerticalDrop1">
      <li><a class="dropdown-item" href="#">Dropdown link</a></li>
      <li><a class="dropdown-item" href="#">Dropdown link</a></li>
    </ul>
  </div>
  <button type="button" class="btn btn-primary" data-mdb-ripple-init>Button</button>
  <button type="button" class="btn btn-primary" data-mdb-ripple-init>Button</button>
  <div class="btn-group" role="group">
    <button
      id="btnGroupVerticalDrop2"
      type="button"
      class="btn btn-primary dropdown-toggle"
      aria-expanded="false"
      data-mdb-ripple-init
      data-mdb-dropdown-init
    >
      Dropdown
    </button>
    <ul class="dropdown-menu" aria-labelledby="btnGroupVerticalDrop2">
      <li><a class="dropdown-item" href="#">Dropdown link</a></li>
      <li><a class="dropdown-item" href="#">Dropdown link</a></li>
    </ul>
  </div>
  <div class="btn-group" role="group">
    <button
      id="btnGroupVerticalDrop3"
      type="button"
      class="btn btn-primary dropdown-toggle"
      aria-expanded="false"
      data-mdb-ripple-init
      data-mdb-dropdown-init
    >
      Dropdown
    </button>
    <ul class="dropdown-menu" aria-labelledby="btnGroupVerticalDrop3">
      <li><a class="dropdown-item" href="#">Dropdown link</a></li>
      <li><a class="dropdown-item" href="#">Dropdown link</a></li>
    </ul>
  </div>
  <div class="btn-group" role="group">
    <button
      id="btnGroupVerticalDrop4"
      type="button"
      class="btn btn-primary dropdown-toggle"
      aria-expanded="false"
      data-mdb-ripple-init
      data-mdb-dropdown-init
    >
      Dropdown
    </button>
    <ul class="dropdown-menu" aria-labelledby="btnGroupVerticalDrop4">
      <li><a class="dropdown-item" href="#">Dropdown link</a></li>
      <li><a class="dropdown-item" href="#">Dropdown link</a></li>
    </ul>
  </div>
</div>
```
```javascript
// Initialization for ES Users
import { Ripple, initMDB } from "mdb-ui-kit";

initMDB({ Ripple });
```

 <hr class="my-5">
 <h2 class="mb-4">Colors

</h2> 
 
```html
<div class="btn-group shadow-0" role="group">
  <button type="button" class="btn btn-light"  data-mdb-ripple-init data-mdb-color="dark">Left</button>
  <button type="button" class="btn btn-light"  data-mdb-ripple-init data-mdb-color="dark">Middle</button>
  <button type="button" class="btn btn-light"  data-mdb-ripple-init data-mdb-color="dark">Right</button>
</div>

<div class="btn-group shadow-0" role="group">
  <button type="button" class="btn btn-link"  data-mdb-ripple-init data-mdb-color="dark">Left</button>
  <button type="button" class="btn btn-link"  data-mdb-ripple-init data-mdb-color="dark">Middle</button>
  <button type="button" class="btn btn-link"  data-mdb-ripple-init data-mdb-color="dark">Right</button>
</div>

<div class="btn-group" role="group">
  <button type="button" class="btn btn-primary"  data-mdb-ripple-init>Left</button>
  <button type="button" class="btn btn-primary"  data-mdb-ripple-init>Middle</button>
  <button type="button" class="btn btn-primary"  data-mdb-ripple-init>Right</button>
</div>

<div class="btn-group" role="group">
  <button type="button" class="btn btn-success"  data-mdb-ripple-init>Left</button>
  <button type="button" class="btn btn-success"  data-mdb-ripple-init>Middle</button>
  <button type="button" class="btn btn-success"  data-mdb-ripple-init>Right</button>
</div>

<div class="btn-group" role="group">
  <button type="button" class="btn btn-danger"  data-mdb-ripple-init>Left</button>
  <button type="button" class="btn btn-danger"  data-mdb-ripple-init>Middle</button>
  <button type="button" class="btn btn-danger"  data-mdb-ripple-init>Right</button>
</div>

<div class="btn-group" role="group">
  <button type="button" class="btn btn-warning"  data-mdb-ripple-init>Left</button>
  <button type="button" class="btn btn-warning"  data-mdb-ripple-init>Middle</button>
  <button type="button" class="btn btn-warning"  data-mdb-ripple-init>Right</button>
</div>

<div class="btn-group" role="group">
  <button type="button" class="btn btn-info"  data-mdb-ripple-init>Left</button>
  <button type="button" class="btn btn-info"  data-mdb-ripple-init>Middle</button>
  <button type="button" class="btn btn-info"  data-mdb-ripple-init>Right</button>
</div>

<div class="btn-group" role="group">
  <button type="button" class="btn btn-dark"  data-mdb-ripple-init>Left</button>
  <button type="button" class="btn btn-dark"  data-mdb-ripple-init>Middle</button>
  <button type="button" class="btn btn-dark"  data-mdb-ripple-init>Right</button>
</div>
```

```javascript
// Initialization for ES Users
import { Ripple, initMDB } from "mdb-ui-kit";

initMDB({ Ripple });
```

