# STRICH Partner Link Package

Contains STRICH logo for dark and light website backgrounds as transparent PNG and SVG (preferred) files.
Tinting the logo to your primary brand color is allowed, in that case use SVG and change the fill color.

## Link data

Link URL: https://strich.io
Link text: "Scanning powered by", to the left (horizontal layout) or above (vertical layout) of the logo.

## Sample HTML/CSS

### Horizontal Layout

Horizontal layout, text to the left of logo, with gap and centered vertically.

```html
<div id="#strich-partner-link">
<a href="https://strich.io"><img src="strich_dark.svg" width="128" height="32" alt="STRICH Logo"></a>
</div>
```

```css
#strich-partner-link {
    display: flex;
    gap: 4px;
    align-items: center;
}
```

### Vertical Layout

Vertical layout with right-aligned edges (switch for left-aligned if you place it at the start of your footer).

```css
#strich-partner-link {
    display: flex;
    flex-direction: column;
    align-items: end;
    gap: 4px;
}
```
