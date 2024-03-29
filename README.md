# Before

performance 48
![alt text](<Screenshot 2024-03-29 at 10.50.49.png>)

# What was suggested

1. Avoid large layout shifts 7 elements found
2. Enable text compression Potential savings of 594 KiB
3. Eliminate render-blocking resources Potential savings of 510 ms
4. Reduce unused CSS Potential savings of 399 KiB
5. Serve images in next-gen formats Potential savings of 771 KiB
6. Largest Contentful Paint element 2,040 ms
7. Preload Largest Contentful Paint image Potential savings of 130 ms
8. Reduce unused JavaScript Potential savings of 132 KiB
9. Efficiently encode images Potential savings of 48 KiB
10. Page prevented back/forward cache restoration 1 failure reason

# What was done

1. Added `vite`
2. added `ccsnano`
3. added visualization from `rollup-plugin-visualizer `
4. added terser for js minification
5. image: `imagemin` from `vite-plugin-imagemin`
   Converts images to WebP
6. Preload Largest Contentful Paint image
7. added `lazy loading` and `async` decoding
8. added `fetchpriority`for LCP
9. fixed some errors in html such as spacing; added `type=module`
10. moved assets and vendor to `public`
11. `defer` scripts
12. `preconnect` and ```display=swap` to google fonts

# After

![alt text](<Screenshot 2024-03-29 at 12.14.13.png>)
