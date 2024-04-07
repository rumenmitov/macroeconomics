# Population
	- **rate of population growth, n** #formula
	  collapsed:: true
		- $n = \frac{\Delta L}{L}$
	- **break-even investment** #formula
	  collapsed:: true
		- $i = 0 = (\delta + n) \cdot k$
			- $\delta k$ investment to replace capital as it wears down
			- $nk$ investment to equip new workers
	- **change in capital per worker (with population change)** #formula
	  collapsed:: true
		- $\Delta k = s \cdot f(k) - (\delta + n) \cdot k$
	- {{renderer excalidraw, excalidraw-2024-04-07-15-33-57}}
	- ## Finding Golden Rule c*
		- $c* = y* - i* = f(k*) - (\delta + n)k*$ #formula
		- #+BEGIN_IMPORTANT
		  c* is ==maximized== when: $MPK = \delta + n$.
		  #+END_IMPORTANT
- # Efficiency
	- **change of labor efficiency, g** #formula
		- $g = \frac{\Delta E}{E}$
			- *E* is the labor efficiency
	- **Labor Augmenting Production Function** #formula
		- Y = F(K, L \times E)
			- L \times E is the number of effective workers
	- **output per effective worker** #formula
		- $y = \frac{Y}{L \times E}$
		  id:: 6612a45f-c6f0-4080-8d7f-47230155c7ae
	- **capital per effective worker** #formula
		- $k = \frac{K}{L \times E}$
	- **saving and investment per effective worker** #formula
		- $s \cdot y = s \cdot f(k)$
	- **break-even investment** #formula
		- break-even investment = $(\delta + n + g)k$
			- $gk$ investment required for the new effective workers
	- ## Finding Golden Rule c*
		- $c* = y* - i* = f(k*) - (\delta + n + g)k*$ #formula
		- #+BEGIN_IMPORTANT
		  c* is ==maximized== when: $MPK = \delta + n + g$.
		  #+END_IMPORTANT
- # Two-Sector Model
	- Two sectors: manufacturing firms and universities
	- ## Assumptions
		- MPK is constant
	- **production function** #formula
		- $Y = A \cdot K$
		  id:: 6612abec-699f-4aaf-b301-05c7efe97a0b
			- *A* is amount of output per unit of capital (exogenous and ==constant==)
	- **motion for total capital** #formula
		- $\Delta K = s \cdot Y - \delta K$
			- $s \cdot Y$ is the investment
			- $\delta K$ is the depreciation
			- Dividing by *K* and since $Y = A \cdot K$:
				- $\frac{\Delta K}{K} = s \cdot A - \delta$
				-