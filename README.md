秩(zhì)序(xù) / order 🌿

不建议按属性首字母顺序声明样式，如 `position: absolute;` 中的 `top/right/bottom/left`定位，中间会被 `width/height/padding` 这类属性间隔，不方便维护。建议按属性类别声明样式：

* 影响文档流的属性 (`display`, Position (`top`, `right`, `bottom`, `left`, `z-index`), Flex/Grid/Columns )
* 盒模型的属性 (`box-sizing`, Width, Height, Margin, Padding, Overflow, Border, Outline)
* 背景装饰属性 (Backgrounds, `box-shadow`, `color`, `opacity`)
* 排版属性 (Fonts, Text, Line, Table)
* CSS3 动画属性 (Transform, Transition, Animation)
* 生成内容属性及其它属性 (`content`, `quotes`, `cursor`)


```markdown
## 影响文档流的属性 (Display, Position, Flex/Grid/Columns )

### 显示、定位 / Display, Position

- 'display'
- 'visibility'

- 'float'
- 'clear'

- 'position'
- 'top'
- 'right'
- 'bottom'
- 'left'
- 'z-index'

### Flex

- 'flex-direction'
- 'flex-wrap'
- 'flex-flow'
- 'justify-content'
- 'align-items'
- 'align-content'

- 'flex-grow'
- 'flex-shrink'
- 'flex-basis'
- 'flex'
- 'align-self'
- 'order'

### Grid

- 'grid'
- 'grid-area'
- 'grid-template'
- 'grid-template-areas'
- 'grid-template-rows'
- 'grid-template-columns'
- 'grid-column'
- 'grid-column-start'
- 'grid-column-end'
- 'grid-row'
- 'grid-row-start'
- 'grid-row-end'
- 'grid-auto-rows'
- 'grid-auto-columns'
- 'grid-auto-flow'
- 'grid-gap'
- 'grid-row-gap'
- 'grid-column-gap'
- 'justify-items'
- 'align-items'
- 'place-items'
- 'justify-self'
- 'align-self'
- 'place-self'
- 'justify-content'
- 'align-content'
- 'place-content'

### Columns

- 'columns'
- 'column-gap'
- 'column-fill'
- 'column-rule'
- 'column-rule-width'
- 'column-rule-style'
- 'column-rule-color'
- 'column-span'
- 'column-count'
- 'column-width'

## 盒模型的属性 (Box Sizing, Width, Height, Margin, Padding, Overflow, Border, Outline)

### 盒模型 / Box

- 'aspect-ratio'
- 'box-sizing'

- 'width'
- 'min-width'
- 'max-width'

- 'height'
- 'min-height'
- 'max-height'

- 'margin'
- 'margin-top'
- 'margin-right'
- 'margin-bottom'
- 'margin-left'

- 'padding'
- 'padding-top'
- 'padding-right'
- 'padding-bottom'
- 'padding-left'

- 'overflow'
- 'overflow-x'
- 'overflow-y'
- 'resize'

### Border

- 'border'
- 'border-top'
- 'border-right'
- 'border-bottom'
- 'border-left'
- 'border-width'
- 'border-top-width'
- 'border-right-width'
- 'border-bottom-width'
- 'border-left-width'

- 'border-style'
- 'border-top-style'
- 'border-right-style'
- 'border-bottom-style'
- 'border-left-style'

- 'border-radius'
- 'border-top-left-radius'
- 'border-top-right-radius'
- 'border-bottom-left-radius'
- 'border-bottom-right-radius'

- 'border-color'
- 'border-top-color'
- 'border-right-color'
- 'border-bottom-color'
- 'border-left-color'

- 'outline'
- 'outline-color'
- 'outline-offset'
- 'outline-style'
- 'outline-width'

## 背景装饰属性 (Backgrounds, Box Shadow, Color, Opacity)

- 'background'
- 'background-attachment'
- 'background-clip'
- 'background-color'
- 'background-image'
- 'background-repeat'
- 'background-position'
- 'background-size'

- 'box-shadow'

- 'color'

- 'opacity'

## 排版属性 (Fonts, Text, Line, Table)

- 'font'
- 'font-family'
- 'font-size'
- 'font-smoothing'
- 'font-style'
- 'font-variant'
- 'font-weight'

- 'letter-spacing'
- 'line-height'
- 'list-style'

- 'text-align'
- 'text-decoration'
- 'text-indent'
- 'text-overflow'
- 'text-rendering'
- 'text-shadow'
- 'text-transform'
- 'text-wrap'

- 'white-space'
- 'word-spacing'

- 'table-layout'
- 'border-collapse'
- 'border-spacing'
- 'caption-side'
- 'empty-cells'
- 'vertical-align'

## CSS3 动画属性 (Transform, Transition, Animation)

### Transform

- 'backface-visibility'
- 'perspective'
- 'perspective-origin'
- 'transform'
- 'transform-box'
- 'transform-origin'
- 'transform-style'

### Transition

- 'transition'
- 'transition-delay'
- 'transition-duration'
- 'transition-property'
- 'transition-timing-function'

### Animation

- 'animation'
- 'animation-name'
- 'animation-delay'
- 'animation-duration'
- 'animation-iteration-count'
- 'animation-play-state'
- 'animation-timing-function'
- 'animation-fill-mode'

## 生成内容属性及其它属性

- 'content'
- 'quotes'
- 'cursor'
- 'speak'
```
