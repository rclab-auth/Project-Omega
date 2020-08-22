# Project Omega
### Machine Learning Design Functions for R/C Columns

*A.E. Charalampakis and V.K. Papanikolaou*


**Languages supported**

- C#
- C++
- Delphi
- Fortran
- Java
- Matlab
- Python
- VB.NET
- VBA (Excel)

**Function syntax**

- Rectangular solid section (As/4 per side)
--  w_RSe(bh,cb,n,mx,my)

- Rectangular solid section (constant As per unit length)
--  w_RSd(bh,cb,n,mx,my)
  
- Rectangular hollow section (As/4 per side)
--  w_RHe(bh,tb,n,mx,my)
  
- Rectangular hollow section (constant As per unit length)
--  w_RHd(bh,tb,n,mx,my)
  
- Circular solid section
--  w_CS(cd,n,m)

- Circular hollow section
--  w_CH(td,n,m)

**Parameter description**

- bh : section aspect ratio (b>h)
- cb : cover width to length b
- tb : section thickness to length b
- cd : cover width to diameter
- td : section thickness to diameter
- n  : normalized axial force
- mx : normalized moment x for rectangular section
- my : normalized moment y for rectangular section
- m  : normalized moment for circular section 

Excel file (functions.xlsm) contains detailed spreadsheet for both
normalized and absolute parameter entry for all six functions.
