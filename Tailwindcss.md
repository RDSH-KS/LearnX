# Tailwindcss

## Layout

### Container

| Class | Breakpoint | Properties |
|-------|------|-----|
| .container  |  None  |  width:100%  |
|  | sm(640px)|max-width:640px;|
|  |md(768px)|max-width:768px;|
|  |lg(1024px)|max-width:1024px;|
|  |xl(1280px)|max-width:1280px;|
|   |   |

### Box Sizing

|  Class|Properties|
|------|-----|
|.box-border|box-sizing: border-box;|
|.box-content|box-sizing: content-box'|
|   |   |

### Display

|Class|Properties|
|-----|-----|
|.hidden|display: none;|
|.block|display: block;|
|.flow-root|display: flow-root;|
|.inline-block|display: inline-block;|
|.inline|display: inline;|
|.flex|display: flex;|
|.inline-flex|display: inline-flex;|
|.grid|display: grid;|
|.inline-grid|display: inline-grid;|
|.table|display: table;|
|.table-caption|display: table-caption;|
|.table-cell|display: table-cell;|
|.table-column|display: table-column;|
|.table-column-group|display: table-column-group;|
|.table-footer-group|display: table-footer-group;|
|.table-header-group|display: table-header-group;|
|.table-row|display: table-row;|
|   |   |

### Floats

|Class|Properties|
|----|----|
|.float-right|float: right;|
|.float-left|float: left;|
|.float-none|float:none;|
|.clearfix|&::after {content: ""; display: table; clear: both;}|
|   |   |

### Clear

|Class | Properties|
|----|----|
|.clear-left|clear: left;|
|.clear-right|clear: right;|
|.clear-both|clear: both;|
|.clear-none|clear: none;|
|   |   |

### Object Fit

|Class|Properties|
|----|----|
|.object-contain|object-fit: contain;|
|.object-cover|object-fit: cover;|
|.object-fill|object-fit: fill;|
|.object-none|object-fit: none;|
|.object-scale-down|object-fit: scale-down;|
|   |   |

### Overflow

|Class	|Properties|
|---|---|
|.overflow-auto	|overflow: auto;|
|.overflow-hidden	|overflow: hidden;
|.overflow-visible	|overflow: visible;
|.overflow-scroll	|overflow: scroll;
|.overflow-x-auto	|overflow-x: auto;
|.overflow-y-auto	|overflow-y: auto;
|.overflow-x-hidden	|overflow-x: hidden;
|.overflow-y-hidden	|overflow-y: hidden;
|.overflow-x-visible	|overflow-x: visible;
|.overflow-y-visible	|overflow-y: visible;
|.overflow-x-scroll	|overflow-x: scroll;
|.overflow-y-scroll	|overflow-y: scroll;
|.scrolling-touch	|-webkit-overflow-scrolling: touch;
|.scrolling-auto	|-webkit-overflow-scrolling: auto;
|   

### Position

|Class	|Properties|
|---|---|
|.static	|position: static;|
|.fixed	|position: fixed;|
|.absolute	|position: absolute;|
|.relative	|position: relative;|
|.sticky	|position: sticky;|
|

### Top / Right / Bottom / Left

|Class	|Properties|
|---|---|
|.inset-0	|top: 0;|
| |right: 0;|
| |bottom: 0;|
| |left: 0;|
|.inset-y-0	|top: 0;|
| |bottom: 0;|
|.inset-x-0	|right: 0;|
| |left: 0;|
|.top-0	|top: 0;|
|.right-0	|right: 0;|
|.bottom-0	|bottom: 0;|
|.left-0	|left: 0;|
|.inset-auto	|top: auto;|
| |right: auto;|
| |bottom: auto;|
| |left: auto;|
|.inset-y-auto	|top: auto;|
| |bottom: auto;|
|.inset-x-auto	|left: auto;|
| |right: |auto;|
|.top-auto	|top: auto;|
|.bottom-auto	|bottom: auto;|
|.left-auto	|left: auto;|
|.right-auto	|right: auto;|
|

### Visibility

|Class|Properties|
|---|---|
|.visible|visibility: visible;|
|.invisible|visibility: hidden;|
|

### Z-Index

|Class|Properties|
|---|---|
|.z-0|z-index: 0;|
|.z-10|z-index: 10;|
|.z-20|z-index: 20;|
|.z-30|z-index: 30;|
|.z-40|z-index: 40;|
|.z-50|z-index: 50;|
|.z-auto|z-index: auto;|
|

## FLEXBOX

### Flex Direction

|Class|Properties|
|---|---|
|.flex-row|flex-direction: row;|
|.flex-row-reverse|flex-direction: row-reverse;|
|.flex-col|flex-direction: column;|
|.flex-col-reverse|flex-direction: column-reverse;|
|

### Flex Wrap

|Class|Properties|
|---|---|
|.flex-no-wrap|flex-wrap: nowrap;|
|.flex-wrap|flex-wrap: wrap;|
|.flex-wrap-reverse|flex-wrap: wrap-reverse;|
|

### Align Items

|Class|Properties|
|---|---|
|.items-stretch|align-items: stretch;|
|.items-start|align-items: flex-start;|
|.items-center|align-items: center;|
|.items-end|align-items: flex-end;|
|.items-baseline|align-items: baseline;|
|

### Align Content 

|Class	|Properties|
|---|---|
|.content-start	|align-content: flex-start;|
|.content-center	|align-content: center;|
|.content-end	|align-content: flex-end;|
|.content-between	|align-content: space-between;|
|.content-around	|align-content: space-around;|
|

### Align Self

|Class	|Properties|
|---|---|
|.self-auto	|align-self: auto;|
|.self-start	|align-self: flex-start;|
|.self-center	|align-self: center;|
|.self-end	|align-self: flex-end;|
|.self-stretch	|align-self: stretch;|
|

### Justify Content


|Class	|Properties|
|---|---|
|.justify-start	|justify-content: flex-start;|
|.justify-center	|justify-content: center;|
|.justify-end	|justify-content: flex-end;|
|.justify-between	|justify-content: space-between;|
|.justify-around	|justify-content: space-around;|
|

### Flex

|Class	|Properties|
|---|---|
|.flex-initial	|flex: 0 1 auto;|
|.flex-1	|flex: 1 1 0%;|
|.flex-auto	|flex: 1 1 auto;|
|.flex-none	|flex: none;|
|

### Flex Grow

|Class	|Properties|
|---|---|
|.flex-grow	|flex-grow: 1;|
|.flex-grow-0	|flex-grow: 0;|
|

### Flex Shrink

|Class	|Properties|
|---|---|
|.flex-shrink	|flex-shrink: 1;|
|.flex-shrink-0	|flex-shrink: 0;|
|

### Order

|Class	|Properties|
|---|---|
|.order-first	|order: -9999;|
|.order-last	|order: 9999;|
|.order-none	|order: 0;|
|.order-1	|order: 1;|
|.order-2	|order: 2;|
|.order-3	|order: 3;|
|.order-4	|order: 4;|
|.order-5	|order: 5;|
|.order-6	|order: 6;|
|.order-7	|order: 7;|
|.order-8	|order: 8;|
|.order-9	|order: 9;|
|.order-10	|order: 10;|
|.order-11	|order: 11;|
|.order-12	|order: 12;|
|

## GRID

### Grid Template Columns

|Class	|Properties|
|---|---|
|.grid-cols-1	|grid-template-columns: repeat(1, minmax(0, 1fr));|
|.grid-cols-2	|grid-template-columns: repeat(2, minmax(0, 1fr));
|.grid-cols-3	|grid-template-columns: repeat(3, minmax(0, 1fr));|
|.grid-cols-4	|grid-template-columns: repeat(4, minmax(0, 1fr));|
|.grid-cols-5	|grid-template-columns: repeat(5, minmax(0, 1fr));|
|.grid-cols-6	|grid-template-columns: repeat(6, minmax(0, 1fr));|
|.grid-cols-7	|grid-template-columns: repeat(7, minmax(0, 1fr));|
|.grid-cols-8	|grid-template-columns: repeat(8, minmax(0, 1fr));|
|.grid-cols-9	|grid-template-columns: repeat(9, minmax(0, 1fr));|
|.grid-cols-10	|grid-template-columns: repeat(10, minmax(0, 1fr));|
|.grid-cols-11	|grid-template-columns: repeat(11, minmax(0, 1fr));|
|.grid-cols-12	|grid-template-columns: repeat(12, minmax(0, 1fr));|
|.grid-cols-none	|grid-template-columns: none;|
|

### Grid Column Start / End

|Class	|Properties|
|---|---|
|.col-auto	|grid-column: auto;|
|.col-span-1	|grid-column: span 1 / span 1;|
|.col-span-2	|grid-column: span 2 / span 2;|
|.col-span-3	|grid-column: span 3 / span 3;|
|.col-span-4	|grid-column: span 4 / span 4;|
|.col-span-5	|grid-column: span 5 / span 5;|
|.col-span-6	|grid-column: span 6 / span 6;|
|.col-span-7	|grid-column: span 7 / span 7;|
|.col-span-8	|grid-column: span 8 / span 8;|
|.col-span-9	|grid-column: span 9 / span 9;|
|.col-span-10	|grid-column: span 10 / span 10;|
|.col-span-11	|grid-column: span 11 / span 11;|
|.col-span-12	|grid-column: span 12 / span 12;|
|.col-start-1	|grid-column-start: 1;|
|.col-start-2	|grid-column-start: 2;|
|.col-start-3	|grid-column-start: 3;|
|.col-start-4	|grid-column-start: 4;|
|.col-start-5	|grid-column-start: 5;|
|.col-start-6	|grid-column-start: 6;|
|.col-start-7	|grid-column-start: 7;|
|.col-start-8	|grid-column-start: 8;|
|.col-start-9	|grid-column-start: 9;|
|.col-start-10	|grid-column-start: 10;|
|.col-start-11	|grid-column-start: 11;|
|.col-start-12	|grid-column-start: 12;|
|.col-start-13	|grid-column-start: 13;|
|.col-start-auto	|grid-column-start: auto;|
|.col-end-1	|grid-column-end: 1;|
|.col-end-2	|grid-column-end: 2;|
|.col-end-3	|grid-column-end: 3;|
|.col-end-4	|grid-column-end: 4;|
|.col-end-5	|grid-column-end: 5;|
|.col-end-6	|grid-column-end: 6;|
|.col-end-7	|grid-column-end: 7;|
|.col-end-8	|grid-column-end: 8;|
|.col-end-9	|grid-column-end: 9;|
|.col-end-10	|grid-column-end: 10;|
|.col-end-11	|grid-column-end: 11;|
|.col-end-12	|grid-column-end: 12;|
|.col-end-13	|grid-column-end: 13;|
|.col-end-auto	grid-column-end: auto;|
|

### Grid Template Rows

|Class	|Properties|
|---|---|
|.grid-rows-1	|grid-template-rows: repeat(1, minmax(0, 1fr));|
|.grid-rows-2	|grid-template-rows: repeat(2, minmax(0, 1fr));|
|.grid-rows-3	|grid-template-rows: repeat(3, minmax(0, 1fr));|
|.grid-rows-4	|grid-template-rows: repeat(4, minmax(0, 1fr));|
|.grid-rows-5	|grid-template-rows: repeat(5, minmax(0, 1fr));|
|.grid-rows-6	|grid-template-rows: repeat(6, minmax(0, 1fr));|
|.grid-rows-none	|grid-template-rows: none;|
|

### Grid Row Start / End

|Class	|Properties|
|---|---|
|.row-auto	|grid-row: auto;|
|.row-span-1	|grid-row: span 1 / span 1;|
|.row-span-2	|grid-row: span 2 / span 2;|
|.row-span-3	|grid-row: span 3 / span 3;|
|.row-span-4	|grid-row: span 4 / span 4;|
|.row-span-5	|grid-row: span 5 / span 5;|
|.row-span-6	|grid-row: span 6 / span 6;|
|.row-start-1	|grid-row-start: 1;|
|.row-start-2	|grid-row-start: 2;|
|.row-start-3	|grid-row-start: 3;|
|.row-start-4	|grid-row-start: 4;|
|.row-start-5	|grid-row-start: 5;|
|.row-start-6	|grid-row-start: 6;|
|.row-start-7	|grid-row-start: 7;|
|.row-start-auto	|grid-row-start: auto;|
|.row-end-1	|grid-row-end: 1;|
|.row-end-2	|grid-row-end: 2;|
|.row-end-3	|grid-row-end: 3;|
|.row-end-4	|grid-row-end: 4;|
|.row-end-5	|grid-row-end: 5;|
|.row-end-6	|grid-row-end: 6;|
|.row-end-7	|grid-row-end: 7;|
|.row-end-auto	|grid-row-end: auto;|
|

### Gap

|Class	|Properties|
|---|---|
|.gap-0	|gap: 0;|
|.gap-1	|gap: 0.25rem;|
|.gap-2	|gap: 0.5rem;|
|.gap-3	|gap: 0.75rem;|
|.gap-4	|gap: 1rem;|
|.gap-5	|gap: 1.25rem;|
|.gap-6	|gap: 1.5rem;|
|.gap-8	|gap: 2rem;|
|.gap-10	|gap: 2.5rem;|
|.gap-12	|gap: 3rem;|
|.gap-16	|gap: 4rem;|
|.gap-20	|gap: 5rem;|
|.gap-24	|gap: 6rem;|
|.gap-32	|gap: 8rem;|
|.gap-40	|gap: 10rem;|
|.gap-48	|gap: 12rem;|
|.gap-56	|gap: 14rem;|
|.gap-64	|gap: 16rem;|
|.gap-px	|gap: 1px;|
|.row-gap-0	|row-gap: 0;|
|.row-gap-1	|row-gap: 0.25rem;|
|.row-gap-2	|row-gap: 0.5rem;|
|.row-gap-3	|row-gap: 0.75rem;|
|.row-gap-4	|row-gap: 1rem;|
|.row-gap-5	|row-gap: 1.25rem;|
|.row-gap-6	|row-gap: 1.5rem;|
|.row-gap-8	|row-gap: 2rem;|
|.row-gap-10	|row-gap: 2.5rem;|
|.row-gap-12	|row-gap: 3rem;|
|.row-gap-16	|row-gap: 4rem;|
|.row-gap-20	|row-gap: 5rem;|
|.row-gap-24	|row-gap: 6rem;|
|.row-gap-32	|row-gap: 8rem;|
|.row-gap-40	|row-gap: 10rem;|
|.row-gap-48	|row-gap: 12rem;|
|.row-gap-56	|row-gap: 14rem;|
|.row-gap-64	|row-gap: 16rem;|
|.row-gap-px	|row-gap: 1px;|
|.col-gap-0	|column-gap: 0;|
|.col-gap-1	|column-gap: 0.25rem;|
|.col-gap-2	|column-gap: 0.5rem;|
|.col-gap-3	|column-gap: 0.75rem;|
|.col-gap-4	|column-gap: 1rem;|
|.col-gap-5	|column-gap: 1.25rem;|
|.col-gap-6	|column-gap: 1.5rem;|
|.col-gap-8	|column-gap: 2rem;|
|.col-gap-10	|column-gap: 2.5rem;|
|.col-gap-12	|column-gap: 3rem;|
|.col-gap-16	|column-gap: 4rem;|
|.col-gap-20	|column-gap: 5rem;|
|.col-gap-24	|column-gap: 6rem;|
|.col-gap-32	|column-gap: 8rem;|
|.col-gap-40	|column-gap: 10rem;|
|.col-gap-48	|column-gap: 12rem;|
|.col-gap-56	|column-gap: 14rem;|
|.col-gap-64	|column-gap: 16rem;|
|.col-gap-px	|column-gap: 1px;|
|

### Grid Auto Flow

|Class	|Properties|
|---|---|
|.grid-flow-row	|grid-auto-flow: row;|
|.grid-flow-col	|grid-auto-flow: column;|
|.grid-flow-row-dense	|grid-auto-flow: row dense;|
|.grid-flow-col-dense	|grid-auto-flow: column dense;|
|

