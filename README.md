#Project Omega#
###Machine Learning Design Functions for R/C Columns###

*Charalampakis, A.E. and Papanikolaou, V.K. (2021) “Machine learning design of R/C columns”, Engineering Structures, Vol. 226, 111412.*

[https://doi.org/10.1016/j.engstruct.2020.111412](https://doi.org/10.1016/j.engstruct.2020.111412)

##Languages supported##

- C# (MLDF.cs)
- C++ (MLDF.cpp)
- Delphi (MLDF.pas)
- Fortran (MLDF.f90)
- Java (MLDF.java)
- Matlab (MLDF.m)
- Python (MLDF.py)
- VB.NET (MLDF.vb)
- VBA/Excel (MLDF.xlsm)

**VBA/Excel (MLDF.xlsm) file contains a detailed spreadsheet for all functions.**

##Function syntax##

**Circular solid section**

    w_CS(cd,n,m)<br>
    As_CS(d,c,fcd,N,M)

> c/d	cover over diameter (0.01 to 0.15)<br>
> n	normalized axial (-0.6 to +0.1)<br>
> m	normalized moment<br>
> w	mechanical reinforcement ratio<br>
> d	diameter<br>
> c	cover<br>
> fcd concrete strength<br>
> N	axial<br>
> M	moment<br>
> As reinforcement area<br>

**Circular hollow section**

	w_CH(td,n,m)<br>
	As_CH(d,t,fcd,N,M)

> t/d thickness over diameter (0.05 to 0.20)<br>
> n normalized axial (-0.6 to +0.1)<br>
> m normalized moment<br>
> w mechanical reinforcement ratio<br>
> d diameter<br>
> c thickness<br>
> fcd concrete strength<br>
> N axial<br>
> M moment<br>
> As reinforcement area<br>


**Rectangular solid section with equal reinforcement at each side**
	
	w_RSe(bh,cb,n,mx,my)<br>
	As_RSe(b,h,c,fcd,N,Mx,My)

> b/h width over height (1.0 to 2.0)<br>
> c/b cover over width (0.01 to 0.15)<br>
> n normalized axial (-0.6 to +0.1)<br>
> mx normalized moment<br>
> my normalized moment<br>
> w mechanical reinforcement ratio<br>
> b width<br>
> h height<br>
> c cover<br>
> fcd concrete strength<br>
> N axial<br>
> Mx moment<br>
> My moment<br>
> As reinforcement area<br>

**Rectangular solid section with distributed reinforcement at each side**
	
	w_RSd(bh,ch,n,mx,my)<br>
	As_RSd(b,h,c,fcd,N,Mx,My)
  
> b/h width over height (1.0 to 6.0)<br>
> c/h cover over height (0.01 to 0.15)<br>
> n normalized axial (-0.6 to +0.1)<br>
> mx normalized moment<br>
> my normalized moment<br>
> w mechanical reinforcement ratio<br>
> b width<br>
> h height<br>
> c cover<br>
> fcd concrete strength<br>
> N axial<br>
> Mx moment<br>
> My moment<br>
> As reinforcement area<br>

**Rectangular hollow section with equal reinforcement at each side**

	w_RHe(bh,tb,n,mx,my)<br>
	As_RHe(b, h, t, fcd, N, Mx, My)

> b/h width over height (1.0 to 2.0)<br>
> t/b thickness over width (0.05 to 0.20)<br>
> n normalized axial (-0.6 to +0.1)<br>
> mx normalized moment<br>
> my normalized moment<br>
> w mechanical reinforcement ratio<br>
> b width<br>
> h height<br>
> t thickness<br>
> fcd concrete strength<br>
> N axial<br>
> Mx moment<br>
> My moment<br>
> As reinforcement area<br>

**Rectangular hollow section with distributed reinforcement at each side**

	w_RHd(bh,tb,n,mx,my)<br>
	As_RHd(b, h, t, fcd, N, Mx, My)

> b/h width over height (1.0 to 6.0)<br>
> t/h thickness over height (0.05 to 0.20)<br>
> n normalized axial (-0.6 to +0.1)<br>
> mx normalized moment<br>
> my normalized moment<br>
> w mechanical reinforcement ratio<br>
> b width<br>
> h height<br>
> t thickness<br>
> fcd concrete strength<br>
> N axial<br>
> Mx moment<br>
> My moment<br>
> As reinforcement area<br>

**Tee section**

	w_T(beffbw,hfd,m)<br>
	x_T(beffbw,hfd,m)<br>
	As_T(beff,bw,h,hf,c,fcd,M,Optional N)

> beff/bw flange width over web width (1.0 to 10.0)<br>
> hf/d slab thickness over effective height (0.05 to 0.25)<br>
> m normalized moment<br>
> w mechanical reinforcement ratio<br>
> x normalized compression flange height<br>
> beff flange width<br>
> bw web width<br>
> h height<br>
> hf flange height<br>
> c cover<br>
> fcd concrete strength<br>
> M moment<br>
> N axial<br>
> As reinforcement area<br>

**Rectangular section**

	w_R(m)<br>
	x_R(m)<br>
	As_R(b,h,c,fcd,M,Optional N)

> m normalized moment<br>
> w mechanical reinforcement ratio<br>
> x normalized compression flange height<br>
> b flange width<br>
> h web width<br>
> c cover<br>
> fcd concrete strength<br>
> M moment<br>
> N axial<br>
> As reinforcement area<br>

