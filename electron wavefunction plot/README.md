We will explore 3D graphics capabilities in the context of waves. A wave in one dimension is a function of position  𝑥  and time  𝑡  that is solution of the wave equation,
$\frac{\partial^2 𝜓}{\partial x^2}=\frac{1}/{𝑐^2}\frac{\partial^2 𝜓}{\partial t^2}$,
being  𝑐  the wave velocity (e.g. for sound waves in air  𝑐=340  m/s). General solutions of this equations are functions  𝜓=𝑓(𝑥−𝑐𝑡)  and 𝜓=𝑓(𝑥+𝑐𝑡) , and linear combinations thereof. The former represents waves travelling to the right, the latter to the left.

Let us consider here a wave of the form
𝜓𝑏(𝑥,𝑡)=𝐴2(sin[𝑘(𝑥−𝑐𝑡)]𝑘(𝑥−𝑐𝑡)+sin[𝑘(𝑥+𝑐𝑡)]𝑘(𝑥+𝑐𝑡)) 
where  𝐴  is the amplitude of the wave and  𝑘  a constant of wave-number dimensions. It represents a oscillating pulse that spreads and separates into two pulses, travelling in opposite directions. We will compare it with the same initial pulse (at  𝑡=0 ) but travelling only to the right, as
𝜓𝑟(𝑥,𝑡)=𝐴sin[𝑘(𝑥−𝑐𝑡)]𝑘(𝑥−𝑐𝑡). 
At  𝑡=0  they both have the same shape.
𝜓𝑏(𝑥,0)=𝜓𝑟(𝑥,0)=𝐴sin(𝑘𝑥)𝑘𝑥. 

We will consider here  𝑐=1 ,  𝐴=1  and  𝑘=2𝜋 .

(a) Regular 2D plots (two)

Produce a figure displaying the shape of 𝜓𝑟 as a function of 𝑥, at times 𝑡=0, 𝑡=1, and 𝑡=−1.

Distinguish the curves for different times with different line styles or colours, and with a text label at covenient locations besides the curves.
Do it for 𝑥 in the range 𝑥∈[−3.5,3.5].
Tailor the tick positions and labels, as well as a title, with fonts of adequate size.
Produce second figure as above, now for 𝜓𝑏, for 𝑡=0, 𝑡=0.6, and 𝑡=1.8, but using a legend instead of text labels.

(b) Contour plots (three)

Produce a contour plot figure for 𝜓𝑟(𝑥,𝑡) using contourf (filled).
Use the 𝑡 coordinate as second (as 𝑦, it will appear vertically in the plot)
Use the ranges 𝑥∈[−1.5,1.5], and 𝑡∈[−0.5,2.5].
Use a colourmap that allows perceiving the transmitted information.
Control ticks, labels, title and fonts.
Produce a second figure, repeating the former for 𝜓𝑏(𝑥,𝑡).
Produce a third figure, again for 𝜓𝑏(𝑥,𝑡), with contour instead of contourf.
Save the last figure as vector graph in a pdf file.
(c) Surface plots (two)

Represent 𝜓𝑏(𝑥,𝑡) as a surface in a 3D plot in the same (𝑥,𝑡) domain as the countour plots above.
Choose a viewpoint that allows good perception of the shape of 𝜓𝑏.
Produce a second 3D figure of the same function using now a wireframe representation.
For clarity in this last one, reduce the (𝑥,𝑡) domain to 𝑥∈[−1,1] and 𝑡∈[−0.5,1.5].
Also for clarity, redefine the view point (you may need to see it from higher up).
