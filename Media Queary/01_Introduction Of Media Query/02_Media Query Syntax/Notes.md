# Media Query Notes

## Introduction to Media Queries

Media queries help make a website **responsive** by adjusting styles based on screen width (breakpoints). A responsive website is mobile-friendly and adapts to different device sizes.

### Common Breakpoints:
| Breakpoint Name       | Width Range          |
|----------------------|--------------------|
| Extra Small (XS)    | width < 576px      |
| Small (SM)          | 576px to 767px     |
| Medium (MD)         | 768px to 991px     |
| Large (LG)          | 992px to 1199px    |
| Extra Large (XL)    | 1200px to 1399px   |
| Extra Extra Large (XXL) | width >= 1400px |

---

## Width Usage in Media Queries

Media queries can use:
- **`min-width`**: Applies styles to screens larger than a certain width.
- **`max-width`**: Applies styles to screens smaller than a certain width.

### Examples:
```css
/* Applies styles to screens 768px and larger */
@media (min-width: 768px) {
    /* Your styles here */
}

/* Applies styles to screens smaller than 768px */
@media (max-width: 767px) {
    /* Your styles here */
}
```

---

## How to Use Media Queries Effectively

1. **Write default CSS** for the main layout.
2. **Use media queries only when needed** to override styles at breakpoints.
3. **Avoid repeating styles** inside media queries if already defined in the main CSS.

### Example:
If `.navbar` already has styles in the main CSS, only add new styles in the media query:
```css
@media (min-width: 500px) and (max-width: 800px) {
    .navbar {
        /* Add only the styles that need to change for this screen range */
    }
}
```

