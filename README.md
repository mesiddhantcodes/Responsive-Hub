# Responsive-Hub

## Landscape
A screen where the width is greater than the height.

## Portrait
A screen where the height is greater than the width.

## Understanding Units

- `px`: Fixed size on any screen.
- `%`: Percentage; it depends on the parent.
- `vw`, `vh`: Depend on the whole size of the screen, not on the parent (viewport width and viewport height).
- `vmax`, `vmin`: Depend on the maximum and minimum viewport size.
- `em`, `rem`: Multiples of the parent size (e.g., font size).
    - `1rem = 60px` (or depends on the root value).

## Layout of the Website

- `position: absolute;`: Minimize the use of this.
- `flex`: This is given to the parent element.
    - `display: flex;`: Divides the elements into rows and columns.
    - `flex-wrap`: Adjusts all elements within the screen.
    - `align-items`: Used for the y-axis (cross-axis).
    - `justify-content`: Used for the x-axis (main axis).

## CSS Media Queries

```css
@media (max-width: 600px) {
}


# Key point to keep in mind to take website responsive

    # CSS Flexbox
    # CSS Units
    # Responsive Typography
    # Mobile-First Approach
    #Flexible Images and Media


# Line here 

# Javascript
