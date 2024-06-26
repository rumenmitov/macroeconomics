# Keynesian Cross
	- **planned expenditure, PE** #formula
		- $PE = C + I + G = MPC \times ( \Delta Y - \Delta T) + I(const) + G(const)$
			- *I* is the planned investment
	- **actual expenditure, Y** #formula
		- Y = real GDP
	- ## Assumptions
		- G and T are fixed
		- I is exogenous and fixed
	- ==Equilibrium:== PE = Y
	- {{renderer excalidraw, excalidraw-2024-04-08-09-47-57}}
	- #+BEGIN_IMPORTANT
	  When **planned expenditure** is shifted (e.g. higher government spending), then $\Delta Y > \Delta G$ (if we are sticking with the government example). This is because higher government spending creates more jobs, thus increasing the disposable income of households and their respective ==demand==.
	  #+END_IMPORTANT
	- ## Keynesian Multiplier
		- ### Government Spending Increases
			- $\Delta Y = \Delta C + \Delta I + \Delta G, \Delta I = 0$ (I is fixed)
			- $\implies \Delta Y = (MPC \times \Delta Y) + \Delta G$, as T is fixed
			- $\Delta PE = \Delta G$ #formula
			- $\Delta Y = \frac{\Delta G}{1 - MPC}$ #formula
			- Keynesian Multiplier = $\frac{1}{1 - MPC}$ #formula
				- It is ==always greater than 1==, since ==MPC < 1==.
		- ### Decrease in Taxation
			- $\Delta Y = MPC \times (\Delta Y - \Delta T) + \Delta I + \Delta G$
				- only $\Delta T \neq 0 , \Delta Y \neq 0$
			- $\Delta PE = MPC \times \Delta T$ #formula
			- $\Delta Y (1 - MPC) = -MPC \times \Delta T$
			- $\Delta Y =\frac{-MPC}{1-MPC} \times \Delta T$ #formula
			- #+BEGIN_NOTE
			  This multiplier does not have to be greater than one.
			  #+END_NOTE
- # Investment-Savings (IS) Curve
	- $Y = C(Y - T_{const}) + I(r) + G$ #formula
	- {{renderer excalidraw, excalidraw-2024-04-22-12-47-00}}
	- IS curve says that ==the lower the interest rate, the higher the income==.
	- #+BEGIN_NOTE
	  When the ==planned expenditure curve== is shifted, there is a corresponding shift in the ==IS curve==. The shift is in the ==IS curve== is equal to the ==Keynesian Multiplier== of the variable we are changing.
	  #+END_NOTE
	- #+BEGIN_PINNED
	  __Example:__ If we are increasing G, then ==PE increase by the same amount as G==, and horizontal shift of the IS curve is $\Delta Y = \frac{\Delta G}{1 - MPC}$.
	  #+END_PINNED
- # Liquidity-Money (LM) Curve
	- ## Money Supply
		- Like in ((66072573-d389-482b-a595-5f7fc8088e43)):
			- $(\frac{M}{P})^s = \frac{M_{const}}{P_{const}}$
			- We assume that the ==real money balance supply== is fixed.
		- The demand for (liquid) money is ==negatively correlated== to the interest rate.
			- $L(r) = (\frac{M}{P})^d$
		- {{renderer excalidraw, excalidraw-2024-04-22-13-15-55}}
	- #+BEGIN_NOTE
	  \Delta r is ==inversely proportional== to \Delta M.
	  #+END_NOTE
	- ## Deriving the LM curve
		- {{renderer excalidraw, excalidraw-2024-04-27-22-10-27}}
	- ## Shifting the LM Curve
		- {{renderer excalidraw, excalidraw-2024-04-27-22-18-47}}
- # Short-Run IS-LM Curve
	- To find the ==equilibrium==:
	  id:: 662d5fd1-1f3a-4635-99f6-6ba6678470d7
		- $Y = C( Y - T(const) ) + I(r) + G(const)$
		- $\frac{M(const)}{P(const)} = L(r, Y)$
	- {{renderer excalidraw, excalidraw-2024-04-27-22-30-17}}