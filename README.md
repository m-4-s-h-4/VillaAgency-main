# Before

performance 48
![alt text](<Screenshot 2024-03-29 at 10.50.49.png>)

# What was suggested

Avoid large layout shifts 7 elements found
Enable text compression Potential savings of 594 KiB
Eliminate render-blocking resources Potential savings of 510 ms
Reduce unused CSS Potential savings of 399 KiB
Serve images in next-gen formats Potential savings of 771 KiB
Largest Contentful Paint element 2,040 ms
Preload Largest Contentful Paint image Potential savings of 130 ms
Reduce unused JavaScript Potential savings of 132 KiB
Efficiently encode images Potential savings of 48 KiB
Page prevented back/forward cache restoration 1 failure reason

# What was done

1. Added `vite`
2. added `ccsnano`
3. added visualization from `rollup-plugin-visualizer `
4. added terser for js minification
5. image: `imagemin` from `vite-plugin-imagemin`
   Converts images to WebP
6. Preload Largest Contentful Paint image
7. added `lazy loading` and `fetchpriority`
8. fixed some errors in html such as spacing
9. moved assets and vendor to `public`
10. `defer` scripts
11. `preconnect` and ```display=swap` to google fonts

# After

![alt text](<Screenshot 2024-03-29 at 12.14.13.png>)
