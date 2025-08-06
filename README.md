# Disable UK-Sticky Behavior (UIkit)

This CSS snippet disables the sticky behavior from elements using the `.uk-sticky` and `.uk-sticky.uk-active` classes in [UIkit](https://getuikit.com/).

## Usage

Include `style.css` in your HTML file or enqueue it via WordPress/your preferred method to override UIkit's default sticky behavior.

## CSS Code

```css
.uk-sticky {
    position: static !important;
    top: auto !important;
    z-index: auto !important;
    width: auto !important;
    transition: none !important;
}

.uk-sticky.uk-active {
    position: static !important;
    top: auto !important;
    z-index: auto !important;
    width: auto !important;
    transition: none !important;
}
