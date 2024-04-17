- **capital** #definition
	- tools, machines, knowledge, and structures that contribute to production
- **labor** #definition
	- the physical and mental efforts of the workers
- # Supply Side
	- ## Production Function
		- $Y = F(K, L)$
		- *Y* - production (real GDP)
		- *K* - capital supply
		- *L* - labor supply
		- ### Assumptions
			- Closed economy
			  logseq.order-list-type:: number
			- Market-clearing model
			  logseq.order-list-type:: number
			- Labor supply, *L*, is constant
			  logseq.order-list-type:: number
			- Capital supply, *K*, is constant
			  logseq.order-list-type:: number
			- Technology is fixed
			  logseq.order-list-type:: number
			- Constant returns to scale
			  logseq.order-list-type:: number
		- ### Returns to Scale
			- **constants return to scale** #definition
				- $z \cdot Y = F(zK, zL)$
			- **increasing returns to scale** #definition
				- $z \cdot Y > F(zK, zL)$
			- **decreasing returns to scale** #definition
				- $z \cdot Y < F(zK, zL)$
	- ## Factor Markets
		- **factor prices** #definition
			- prices per unit that a firm pays for the factors of production
		- **nominal wage** #definition
			- price of labor
		- **nominal rental rate** #definition
			- price of capital
		- **real wage** #formula
			- real wage = $\frac{\text{nominal wage}}{\text{price of output}}$
		- **real rental rate** #formula
			- real rental rate = $\frac{\text{nominal rental rate}}{\text{price of output}}$
		- Factor prices are determined by *supply and demand* in factor markets.
	- ## Neoclassical Theory of Distribution
		- **Neoclassical Theory of Distribution** #definition
			- each *factor input* is paid by its *marginal product*
		- ### Assumptions
			- Market is competitive (i.e. firm takes *nominal wage*, *nominal rental rate*, and *price of output* as given)
			  logseq.order-list-type:: number
		- Firm hires additional unit of labor if ==cost does not exceed benefit==.
			- cost = *nominal wage*
			- benefit = *marginal product of labor*
		- **Marginal Product of Labor (MPL)** #definition #formula
			- by how many units the output increases by increasing labor by 1
			- MPL = F(K, L + 1) - F(K, L)
		- #+BEGIN_PINNED
		  *Marginal returns* means that as one input increases (and all other inputs are constants) ==MPL decreases==. 
		  
		  To examine if a function is *diminishing* take the derivative with respect to the changing variable.
		  #+END_PINNED
		- {{renderer excalidraw, excalidraw-2024-02-18-16-19-11}}
		- #+BEGIN_PINNED
		  #formula
		  MPL = real wage (==profit is maximized==)
		  
		  MPK = real rental rate (==profit is maximized==)
		  #+END_PINNED
		- #+BEGIN_NOTE
		  The same holds true for **MPK** (marginal product of capital).
		  #+END_NOTE
		- ### Distribution of Income
			- **total labor income** #formula
				- total labor income = real wages \times labor supply = MPL \times labor supply
			- **total capital income** #formula
				- total capital income = real rental rate \times capital supply = MPK \times capital supply
			- **total national income** #formula
				- Y = MPL \times L + MPK \times K
					- *Y* is total national income
					- #+BEGIN_NOTE
					  No profits!
					  #+END_NOTE
			- #### Cobb Douglas Production Function
				- ##### Assumptions
					- Constant returns to scale
					  logseq.order-list-type:: number
					- Competitive market
					  logseq.order-list-type:: number
					- Diminishing returns for capital and labor
					  logseq.order-list-type:: number
				- **Cobb-Douglas Production Function** #formula
					- $Y = AK^{\alpha}L^{1- \alpha}$
						- *A* is the level of technology (productivity parameter)
						- \alpha is the ==capital's share of total income==
							- capital income = MPK \times K = $\alpha Y$
							- labor income = MPL \times L = $(1 - \alpha)Y$
							- $MPL = (1 - \alpha) \times A \times (\frac{K}{L})^\alpha$
							- $MPK = \alpha \times A \times (\frac{L}{K})^{1 - \alpha}$
							- #+BEGIN_IMPORTANT
							  $0 \le \alpha \le 1$
							  #+END_IMPORTANT
							- #+BEGIN_NOTE
							  *Cobb-Douglas* produces ==constant returns to scale==.
							  #+END_NOTE
				- **average production function of labor** #formula
					- average production of labor = $\frac{Y}{L}$
				- **average production function of capital** #formula
					- average production of capital = $\frac{Y}{K}$
				- #+BEGIN_NOTE
				  MPL = $\frac{(1 - \alpha)Y}{L}$
				  
				  MPK = $\frac{\alpha Y}{K}$
				  #+END_NOTE
- # Demand Side
	- **disposable income** #definition #formula
		- total income after taxes
		- $Y - T$
	- **consumption function** #formula
		- $C = C(Y - T) = ( C(const) + MPC ) \times (Y - T)$
			- *C* is both the ==consumption function== and the ==amount of planned consumption==
	- **marginal propensity to consume** #definition
		- the change in *consumption* when *disposable income* increases by \$1
	- {{renderer excalidraw, excalidraw-2024-02-18-17-02-34}}
	- **investment function** #definition
		- $I = I(r)$
		- *r* is the real interest rate
		- NOTE: *I* depends negatively on *r*
	- **real interest rate** #definition
		- cost of borrowing
		- opportunity cost of using one's own funds to finance investment spending
	- {{renderer excalidraw, excalidraw-2024-02-18-17-06-24}}
	- *Assumption:* Government spending and taxes are constant.
- # Market Equilibrium
	- **aggregate demand** #formula
		- Y = C(Y - T) + I(r) + G
	- **aggregate supply** #formula
		- Y = F(K, L)
	- #+BEGIN_NOTE
	  Here the ==real interest rate (r)== is the only non-constant, hence it adjusts to equate to supply and demand. 
	  #+END_NOTE
- # Loanable Funds Market
	- **demand for loanable funds** #definition
		- investment
	- **supply for loanable funds** #definition
		- saving
	- **price of loanable funds** #definition
		- real interest rate
	- {{renderer excalidraw, excalidraw-2024-02-18-17-14-34}}
	- **private savings** #definition #formula
		- savings of households
		- private savings = (Y - T) - C
	- **public savings** #definition #formula
		- savings of government
		- public savings = T - G
	- **national savings** #formula
		- S = private savings + public savings = Y - C - G
			- *S* is the national savings
		- #+BEGIN_NOTE
		  National savings is *fixed*!
		  #+END_NOTE
	- **budget surplus** #formula
		- T > G
	- **budget deficit** #formula
		- T  < G
			- #+BEGIN_NOTE
			  Financed by *government bonds*.
			  #+END_NOTE
	- **budget balanced** #definition
		- T = G
	- #+BEGIN_NOTE
	  The real interest rates balances the supply and demand of the *goods market* and of the *loanable goods market*.
	  
	  TODO equations!!!!!
	  y-c-g = i
	  add c +g
	  y = 
	  #+END_NOTE
- # Mastering the Model
	- ## Shift of the Curve
		- Public Saving (fiscal policy)
			- \Delta T
			- \Delta G
		- Private Saving
			- \Delta C