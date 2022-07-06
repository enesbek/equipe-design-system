# Input

## Buttons

Use Equipe's custom Ebtn component for actions in forms, dialogs, and more. Includes support for a handful of contextual variations, sizes, states, and more.

## 

### Overview

BootstrapVue's Ebtn component generates either a "button" element, "a" element, or "router-link" component with the styling of a button.

<img src="../../assets/btn-1.png" width="103"/>
<img src="../../assets/btn-2.png" width="100"/>
<img src="../../assets/btn-3.jpg" width="100"/>

`<Ebtn>Button</Ebtn>`<br>
`<Ebtn variant="danger">Button</Ebtn>`<br>
`<Ebtn variant="success">Button</Ebtn>`<br>

### Contextual variants

Use the variant prop to generate the various Equipe contextual button variants.

By default "Ebtn" will render with the secondary variant.

The variant prop adds the Equipe on the rendered button.

#### Solid Color Variants

primary, success, danger, warning, dark, default

<img src="../../assets/btn-10.jpg" width="100"/>
<img src="../../assets/btn-3.jpg" width="100"/>
<img src="../../assets/btn-2.png" width="100"/>
<img src="../../assets/btn-11.jpg" width="100"/>
<img src="../../assets/btn-12.jpg" width="100"/>
<img src="../../assets/btn-1.png" width="100"/>

`<Ebtn variant="primary">Button</Ebtn>`<br>
`<Ebtn variant="success">Button</Ebtn>`<br>
`<Ebtn variant="danger">Button</Ebtn>`<br>
`<Ebtn variant="warning">Button</Ebtn>`<br>
`<Ebtn variant="dark">Button</Ebtn>`<br>
`<Ebtn>Button</Ebtn>`<br>

### Sizing

Fancy larger or smaller buttons? Specify lg or sm via the size prop.

<img src="../../assets/btn-4.jpg" />
<img src="../../assets/btn-5.jpg" />
<img src="../../assets/btn-6.jpg" />

`<Ebtn size="sm">Small Button</Ebtn>`<br>
`<Ebtn>Default Button</Ebtn>`<br>
`<Ebtn size="lg">Large Button</Ebtn>`<br>

### Pill Style

Prefer buttons with a more rounded-pill style? Just set the prop pill to true.

<img src="../../assets/btn-7.jpg" width="100" />
<img src="../../assets/btn-8.jpg" width="100" />
<img src="../../assets/btn-9.jpg" width="100" />

`<Ebtn pill>Small Button</Ebtn>`<br>
`<Ebtn pill variant="danger">Default Button</Ebtn>`<br>
`<Ebtn pill variant="success">Large Button</Ebtn>`<br>
