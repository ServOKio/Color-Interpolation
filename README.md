# Color-Interpolation
Fixing the colors in the browser

## Beginning
We started creating this library because we got bored and decided to do [Photoshop](https://servokio.ru/test6) in the browser, but we ran into a problem when working with colors.

## Filters
![2022-04-27_09-35 (1)](https://user-images.githubusercontent.com/51263003/196129163-e777583d-b626-4a95-b9a6-da8287d41129.png)

| Name               | PS Code     | Status | Firefox | Chromium | Opera | Safari |
| ---                | ---         | ---    | ---     | ---      | ---   | ---    |
| Normal             | `norm`      | ✅     | ✅      | ✅      | ?     | ?      |
| Dissolve           | `diss`      | -      | -       | -        | -     | -      |
| Darken             | `dark`      | ✅     | ✅      | ✅      | ?     | ?      |
| Multiply           | `mul`       | ✅     | ✅      | ✅      | ?     | ?      |
| Color Burn         | `idiv`      | -      | -       | -        | -     | -      |
| Linear Burn        | `lbrn`      | -      | -       | -        | -     | -      |
| Derken Color       | `dkCl`      | -      | -       | -        | -     | -      |
| Lighten            | `lite`      | ✅     | ✅      | ✅      | ?     | ?      |
| Screen             | `scrn`      | ✅     | ✅      | ✅      | ?     | ?      |
| Color Dodge        | `div`       | ✅     | ✅      | ✅      | ?     | ?      |
| Linear Dodge (Add) | `lddg`      | ✅     | ⚠️Own support (has a problem with `color-burn` filter) | ✅      | ?     | ?      |
| Lighter Color      | `lgCl`      | -      | -       | -        | -     | -      |
| Overlay            | `over`      | ✅     | ✅      | ✅      | ?     | ?      |
| Soft Light         | `sLit`      | ✅     | ✅      | ✅      | ?     | ?      |
| Hard Light         | `hLit`      | ✅     | ✅      | ✅      | ?     | ?      |
| Vivid Light        | `vLit`      | -      | -       | -        | -     | -      |
| Linear Light       | `lLit`      | -      | -       | -        | -     | -      |
| Pin Light          | `pLit`      | -      | -       | -        | -     | -      |
| Hard Mix           | `hMix`      | -      | -       | -        | -     | -      |
| Difference         | `diff`      | -      | -       | -        | -     | -      |
| Exclusion          | `smud`      | -      | -       | -        | -     | -      |
| Subtract           | `fsub`      | -      | -       | -        | -     | -      |
| Divide             | `fdiv`      | -      | -       | -        | -     | -      |
| Hue                | `hue`       | -      | -       | -        | -     | -      |
| Saturation         | `sat`       | -      | -       | -        | -     | -      |
| Color              | `colr`      | -      | -       | -        | -     | -      |
| Luminosity         | `lum`       | -      | -       | -        | -     | -      |

Why: [webcolorisstillbroken.com](https://webcolorisstillbroken.com/)
