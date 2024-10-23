---
title: Pattern Background
description: Simple animated pattern background to make your sections stand out.
---

Grid background with dot
::ComponentLoader{label="Preview" componentName="PatternBackgroundDotDemo" type="examples" id="pattern-background"}
::

Grid background with big dot and ellipse on top
::ComponentLoader{label="Preview" componentName="PatternBackgroundBigDotDemo" type="examples" id="pattern-background"}
::

## Examples

Grid background without animation
::ComponentLoader{label="Preview" componentName="PatternBackgroundGridDemo" type="examples" id="pattern-background"}
::

Small grid background with animation
::ComponentLoader{label="Preview" componentName="PatternBackgroundGridSmallDemo" type="examples" id="pattern-background"}
::

## API

| Prop Name   | Type                                                                                                   | Default   | Description                                                                                                                                                         |
| ----------- | ------------------------------------------------------------------------------------------------------ | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `animate`   | `boolean`                                                                                              | `false`   | Set `true` if you want to animate the background.                                                                                                                   |
| `direction` | `top` \| `bottom` \| `left` \| `right` \| `top-left` \| `top-right` \| `bottom-left` \| `bottom-right` | `top`     | Direction of the animation movement. You can use the const `PATTERN_BACKGROUND_DIRECTION.<key>`                                                                     |
| `direction` | `grid` \| `dot`                                                                                        | `grid`    | Type of pattern. You can use the const `PATTERN_BACKGROUND_VARIANT.<key>`                                                                                           |
| `size`      | `xs` \| `sm` \| `md` \| `lg`                                                                           | `md`      | Size of the background pattern.                                                                                                                                     |
| `mask`      | `ellipse` \| `ellipse-top`                                                                             | `ellipse` | Add a mask over the background pattern. You can use the const `PATTERN_BACKGROUND_MASK.<key>`                                                                       |
| `speed`     | `number`                                                                                               | `10000`   | Duration of the animation in `ms`, the bigger it is, the slower the animation. (`20000` slower than `5000`). You can use the const `PATTERN_BACKGROUND_SPEED.<key>` |

### Custom variants, values and constants

You can customize your needs directly within the `index.ts` file. See code below.

## Component Code

You can copy and paste the following code to create these components (put them under the same folder):

::code-group

::CodeViewerTab{label="PatternBackground.vue" language="vue" componentName="PatternBackground" type="ui" id="pattern-background"}
::

::CodeViewerTab{filename="index.ts" language="typescript" componentName="index" type="ui" id="pattern-background" extension="ts"}
::

::

## Credits

- Inspired by [Magic UI's Dot Pattern](https://magicui.design/docs/components/dot-pattern) component.
- Inspired by [Magic UI's Grid Pattern](https://magicui.design/docs/components/grid-pattern) component.
- Inspired by [Magic UI's Animated Grid Pattern](https://magicui.design/docs/components/animated-grid-pattern) component.
- Credits to [Nathan De Pachtere](https://github.com/nathan-de-pachtere) for porting this component.