# optimize-dom-operations-avoid-layout-thrashing
This example demonstrates the performance impact of 'layout thrashing' in web browsers. It compares two methods of updating multiple DOM elements: one that causes synchronous layout recalculations by interspersing DOM reads and writes, and another that optimizes performance by batching all DOM reads first, then all DOM writes, allowing the browser 
