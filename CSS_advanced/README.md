# CSS Advanced

- **[0. Let's get some images!](./index.html)**
- Download 10 high resolution images from Unsplash matching the final product design, along with the required 2 logos and favicon.

- **[1. Effortless transitions when scrolling](./index.html)**
- Enable fluid and effortless scrolling transitions when triggered directly on the HTML element.

- **[2. Do you know your color values?](./styles/1-style.css)**
- Set the default foreground colors for body and anchor elements to `#161616`, hide `.visually-hidden` elements, and color `.card-category` and `.section-tagline` with `#D73953`.

- **[3. Reuse and repeat. A programmer's life should be simple with variables](./styles/2-style.css)**
- Define root custom properties for primary, black, white, light-grey, dark-grey, and text-color. Reuse them for taglines, categories, body, and anchors.

- **[4. Variables for storing certain font types](./styles/3-style.css)**
- Target the root element to create `font-family-base` and `font-family-title` using a stack of Helvetica Neue, Helvetica, Arial, and sans-serif. Apply to body and headings.

- **[5. Variables for the font size](./styles/4-style.css)**
- Define small to xx-large custom font size variables. Set global html font size to 62.5% and body fonts to medium.

- **[6. Variables for the font-weight](./styles/5-style.css)**
- Set up `font-weight-regular` (400) and `font-weight-bold` (700). Apply the regular weight to the body and bold to headings.

- **[7. Integrating Google Fonts into the CSS file](./styles/6-style.css)**
- Shift your custom font variables to incorporate Open Sans as the primary base font and Raleway as the primary title font.

- **[8. Defining line heights](./styles/7-style.css)**
- Add `line-height-small`, `line-height-base`, and `line-height-big` root variables. Enforce the minimum line height in the body.

- **[9. Links are decorated by default, time to remove them](./styles/8-style.css)**
- Style all anchor elements globally to remove any default text decorations.

- **[10. Centering the section titles](./styles/9-style.css)**
- Introduce a `section-header-align` center property and apply it dynamically targeting the `.section-header` class.

- **[11. Add more styles to the section tagline](./styles/10-style.css)**
- Build a text-transform custom property and enforce uppercase, bold, title-family styling on `.section-tagline`.

- **[12. Adding more styling to the section title](./styles/11-style.css)**
- Target `.section-title` to give it a custom zero margin, black color, bold weight, and xx-large font size utilizing custom CSS variables.

- **[13. Pseudo Classes](./styles/12-style.css)**
- Ensure anchors have hyperlinks. Apply italic text to visited links, an underline on hover, and a light-grey background when active.

- **[14. Resetting the CSS stylesheet for browser consistency](./styles/13-style.css)**
- Include and implement Necolas' normalize.css to enforce unified cross-browser element definitions.

- **[15. Add universal box-sizing](./styles/14-style.css)**
- Implement a universal CSS box-sizing rule just before the html styling tags.

- **[16. Styling the container](./styles/15-style.css)**
- Assign a 960px width to `.container` elements and correctly distribute horizontal margins evenly.

- **[17. Adding padding to sections](./styles/16-style.css)**
- Create varied padding variables for standard sections, headers, bodies, footers, and dynamically enforce them via class selectors.

- **[18. Customizing the navbar](./styles/17-style.css)**
- Construct variables and navigation styles targeting `.navbar-menu`, `.nav`, `.nav-item`, and `.nav-link` for a clear, inline-block navigation bar.

- **[19. Grid styling and custom variables](./styles/18-style.css)**
- Set up essential responsive grid styling classes like `.row`, `.col-1-3`, `.col-1-2`, manipulating widths, floats, and zero default stylings.

- **[20. Clear the context of the grid](./styles/19-style.css)**
- Write a clearing rule for `.row` classes that ensures layout elements display as a table and block floating elements automatically.

- **[21. Simplify the col- selector](./styles/20-style.css)**
- Restructure all generic `.col-` classes with an attribute selector to apply unified standard padding and floating behaviors seamlessly.

- **[22. Add a dark theme to sections](./styles/21-style.css)**
- Target custom attribute `data-section-theme="dark"` styling to flip text colors, title colors, and background rendering into a night mode.

- **[23. Fix issues for dark theme](./styles/22-style.css)**
- Address contrast issues in dark theme mode applied on `.footer-address` text and fill correct foreground coloring onto `.social-link` SVG children.

- **[24. Add background and hover state to services](./styles/23-style.css)**
- Remove margins for `.card-title` in `.card-services`, and style internal anchor elements to react dynamically to hover focus.

- **[25. Add border to the button](./styles/24-style.css)**
- Construct button rendering variables for padding, borders, decoration, font sizing, and hover effects, then build the main `.button` selector.

- **[26. Add border radius to images](./styles/25-style.css)**
- Centralize content in `.card-testimonial`, round internal `.card-avatar` images perfectly by 50%, and style block-level `<cite>` elements.

- **[27. Styling the section hero](./styles/26-style.css)**
- Target `.section-hero` to explicitly render a 90rem width background setup, adjusting titles and layout dimensions independently via padding and margin properties.

- **[28. Fixing the header and menu navigation bar](./styles/27-style.css)**
- Define structural header variables positioning the main logo elements relatively and rendering logo links into absolute layout slots.

- **[29. Styling and custom properties for the nav](./styles/28-style.css)**
- Upgrade navigation hover visuals by absolute positioning empty `::before` pseudo elements that animate into primary background highlights.

- **[30. Fix the works section](./styles/29-style.css)**
- Optimize visuals on `.card-work`, utilizing `object-fit` parameters, precise vertical positioning, lowered opacities, and z-index definitions.

- **[31. Add quotes decoration on testimonials](./styles/30-style.css)**
- Introduce aesthetic massive quote markings directly structured around the `::before` pseudo-element of internal `.card-quote` entries.

- **[32. Incorporating transitions](./styles/31-style.css)**
- Produce variables for bezier curve durations and apply scaling transformations over `.card-work`, pseudo nav links, and button background hovers.
