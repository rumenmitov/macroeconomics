# Solow Model
	- ## Assumptions
		- *K* is not fixed
		- *L* is not fixed (population growth)
		- *G* = *T* = 0
		- Constant returns to scale
	- ## Definitions
		- Output per worker $= y = \frac{Y}{L}$
		- Capital per worker $= k = \frac{K}{L}$
		- $zY = F(zK, zL), z = \frac{1}{L} \implies y = F(k, 1) = f(k)$
		- Consumption per worker $= c = \frac{C}{L}$
		- Investment per worker $= i = \frac{I}{L}$
		- National income per worker $= y = c + i$ (no *G* or *T*)
	- {{renderer excalidraw, excalidraw-2024-04-01-19-22-20}}
		- MPK = $\frac{\Delta f(k)}{\Delta k}$ #formula
	- ## Savings Rate, s
		- #+BEGIN_IMPORTANT
		  $s \neq \frac{S}{L}$
		  #+END_IMPORTANT
		- *s* is an ==exogenous== parameter.
	- ## Consumption Function Per Worker
		- $c = y(1-s)$
			- (1 - s) is the
	- ## Saving and Investment Functions Per Worker
		- saving per worker $= y - c = sy$ (substituting consumption function per worker)
		- $y= c + i \implies$ investment per worker, $i = y - c = sy$ (savings = investment)
			- $\implies i = s \cdot f(k)$
	- {{renderer excalidraw, excalidraw-2024-04-01-19-39-21}}
	- **rate of depreciation**, $\delta$ #definition
		- how quickly the machinery breaks down
	- {{renderer excalidraw, excalidraw-2024-04-01-19-47-04}}
	- **Capital Accumulation** #formula
		- $\Delta k = i - \delta k = s \cdot f(k) - \delta k$
- ## Steady State
	- {{renderer excalidraw, excalidraw-2024-04-01-19-52-20}}
	- #+BEGIN_NOTE
	  Since ==in the long-run== both sides convert to ==k*==, there is **no growth** in the long-run.
	  #+END_NOTE
	- {{renderer excalidraw, excalidraw-2024-04-01-20-17-25}}
	- #+BEGIN_NOTE
	  Combining this with the consumption per worker function: $c* = f(k*)(1 - s)$.
	  To then achieve the ==c* gold== one must choose the correct *saving rate, s* so
	  that when k* = δk*,  c* = f(k*) - δk* is biggest.
	  #+END_NOTE
	- #+BEGIN_NOTE
	  The economy does not automatically tend to the ==Golden Rule Steady State==. The *saving rate* must be adjusted for it to be reached.
	  #+END_NOTE
	- ### Transitioning To Golden Rule
		- {{renderer excalidraw, excalidraw-2024-04-01-20-36-59}}
		- **dynamically inefficient** #definition
			- economy is operating at k* > k* gold
		- **dynamically efficient** #definition
			- economy is operating at k* < k* gold