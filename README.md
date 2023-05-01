# cssGrid
CSS Grid notes

- Tracks mean columns and rows are collectively referred as tracks.
### Implicit Tracks vs Explicit Tracks in grid
```
 .container{
        display: grid;
        grid-template-columns: 200px auto 500px 50px;
       grid-gap: 20px; 
    }

```
- Explicit Tracks means directly defining  the column gap (denoted by dashed line).
- Implicit Tracks means not declaring by default it the row gap comes with dotted line.
- Our solid line denotes the grid started.

### How to set the size for implicit rows or columns
- for Rows you can set through grid-auto-rows.
- for columns the grid-auto-columns won't work ,However we explicitly declared two columns and it
creates an row ,so there is another method to rectify this (grid auto flow)
