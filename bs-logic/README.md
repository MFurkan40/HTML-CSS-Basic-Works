## ASSIGMENT-3 (FLEX-GRID)

- Design a site template using flex-grid as in the specified link:

  https://flex-grid-cw.netlify.app/

## A-) Width

- logo (4 col) and menu (8 col)
- banner ve footer (whole)
- section1,2 and 3 is equal
- section4 (3 col), section5 (6 col), section6(3 col)

## B-)Height

- logo and menu padding: 1rem
- banner's padding: 4rem
- section4,5ve 6 padding: 1rem
- footer's padding: 2rem
- For section 1,2,3 line, the height remaining from the browser's visible area

## HINT

.container {
width: 100%;
}

.row {
display: flex;
flex-wrap: wrap;
}

.col-1 {
width: 8.333333%;
}

.col-2 {
width: 16.666667%;
}

.col-3 {
width: 25%;
}

.col-4 {
width: 33.333333%;
}

.col-5 {
width: 41.666667%;
}

.col-6 {
width: 50%;
}

.col-7 {
width: 58.333333%;
}

.col-8 {
width: 66.666667%;
}

.col-9 {
width: 75%;
}

.col-10 {
width: 83.333333%;
}

.col-11 {
width: 91.666667%;
}

.col-12 {
width: 100%;
}
