# Optimize DOM Operations Avoid Layout Thrashing

This example demonstrates the performance impact of 'layout thrashing' in web browsers. It compares two methods of updating multiple DOM elements: one that causes synchronous layout recalculations by interspersing DOM reads and writes, and another that optimizes performance by batching all DOM reads first, then all DOM writes, allowing the browser to perform fewer layout calculations.

## Language

`html`

## How to Run

1. Save the code as `index.html`.
2. Open `index.html` in your web browser.
3. Open the browser's developer console (F12) to see the performance timings. Click the 'Run Bad Performance (Thrashing)' and 'Run Good Performance (Optimized)' buttons and observe the significant difference in execution times.

## Original Article

This example accompanies the Turkish article: [Web Performansının "Çılgın" Sırları: Hız Optimizasyonunda Beklenmedik Yollar](https://fatihsoysal.com/blog/web-performansinin-cilgin-sirlari-hiz-optimizasyonunda-beklenmedik-yollar/).

## License

MIT — see [LICENSE](LICENSE).
