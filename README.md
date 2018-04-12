# cssgridlayout
A collection of CSS classes to be used in the building of a website.
These classes are based on the W3C CSS Grid Layout system.
## Naming convention
### grid
Declare as a grid.
### single
One column/row.
#### Example
`<section class="grid single">This is a single column/row.</section>`
## two-columns
2 auto columns.
#### Example
```
<div class="grid two-columns">
    <article>The article</article>  
    <aside>The aside</aside>
</div>
```
## two-rows
2 auto rows.
#### Example
```
<div class="grid two-rows">
    <article>The article</article>
    <aside>The aside</aside>
</div>
```
### golden-columns
Uses 2fr 1fr. The golden ratio of 66.6% 33.3% is applied to 2 columns.
#### Example
```
<div class="grid golden-columns">
    <article>The article</article>
    <aside>The aside</aside>
</div>
```
### golden-rows
Uses 2fr 1fr. The golden ratio of 66.6% 33.3% is applied to 2 rows.
#### Example
```
<div class="grid golden-rows">
    <article>The article</article>
    <aside>The aside</aside>
</div>
```
### inverse-golden-columns
Uses 1fr 2fr. The inversed golden ratio of 33.3% 66.6% is applied to 2 columns.
#### Example
```
<div class="grid inverse-golden-columns">
    <article>The article</article>
    <aside>The aside</aside>
</div>
```
### inverse-golden-rows
Uses 1fr 2fr. The inversed golden ratio of 33.3% 66.6% is applied to 2 rows.
#### Example
```
<div class="grid inverse-golden-rows">
    <article>The article</article>
    <aside>The aside</aside>
</div>
```
### three-columns, three-rows, four-columns, four-rows
Number of columns or rows.
#### Examples
```
<div class="grid three-columns">
    <section>The section</section>
    <article>The article</article>
    <aside>The aside</aside>
</div>
<div class="grid three-rows">
    <section>The section</section>
    <article>The article</article>
    <aside>The aside</aside>
</div>
<div class="grid four-columns">
    <section>The section</section>
    <article>The article</article>
    <aside>The aside</aside>
</div>
<div class="grid four-rows">
    <section>The section</section>
    <article>The article</article>
    <aside>The aside</aside>
</div>
```
### subgrid
Begins a subgrid.
#### Example
```
<div class="grid golden-columns">
  <div class="grid two-rows">
    <article>The article 1</article>
    <div class="subgrid two-columns">
      <article>The article 2</article>
      <aside>The aside</aside>
    </div>
  </div>
  <section>The section</section>
</div>
```
### More examples to try
```
<div class="grid two-columns">
    <section>The section</section>
    <div class="two-rows">
      <article>The article</article>
      <aside>The aside</aside>
    </div>          
</div>
```
```
<div class="grid golden-columns">
  <div class="two-rows">
    <article>The article</article>
    <aside>The aside</aside>
  </div>
  <section>The section</section>                    
</div>
```
```
<div class="grid three-columns">
  <section>The section 1</section>
  <div class="two-rows">
    <article>The article</article>
    <aside>The aside</aside>
  </div>
  <section>The section 2</section>
</div>
```
