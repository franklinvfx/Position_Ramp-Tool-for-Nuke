# Position Ramp
<strong>To quikly create a ramp using the data contained in the render of "World Position" or "Ref Position".</strong>

This node has several advantages. The position of the ramp is not set by a "color picker" but with a 2D Position knob which executes callbacks. So it is possible to precisely place the ramp regardless of the channel viewed. With the "Overlay" mode, the tool is visually even more convenient.
Visualization in 3D space is also a real advantage in a certain situation, as well as the integration of the "Unpremult" and "Premult" which makes it possible to obtain clean edges.
The tool is fast and easy to use, and if you don't have the position pass, ask your Comp or CG supervisor ;)

<img class="aligncenter wp-image-2249 size-full" src="http://franklinvfx.com/wp-content/uploads/2017/04/11.gif" alt="" />
<img class="aligncenter wp-image-2249 size-full" src="http://franklinvfx.com/wp-content/uploads/2017/04/3.gif" alt="" />
<img class="aligncenter wp-image-2249 size-full" src="http://franklinvfx.com/wp-content/uploads/2017/04/4.gif" alt="" />

<strong>Tool details:</strong>

<strong>P Channel:</strong> To select the Position Pass channel.

<strong>Axe:</strong> To choose the ramp direction (x,y or z).

<strong>Start & End:</strong> To adjust the position of the two extremes of the ramp.

<strong>Offset (Start & End):</strong> To precisely adjust the position between the two extremes with a slider.

<strong>Overlay:</strong> To show the ramp on overlay (looking the rgb) and to change the color (none, red, green, blue or black)

<strong>3D Options:</strong>
- To visualize in 3D the input image and the ramp. This uses a "position to point" node and it gives the possibility to adjust the "Point Detail" and the "Point Size".
- To adjust the size of 3D points representing the position of the two extremes of the ramp.

<strong>(Un)Premult:</strong> To keep nice shapes on edges.

<p style="font-family: 'Open Sans', sans-serif; font-size: 15px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400;">For the creation of this tool, I was strongly inspired by the article written by <a title="Nukepedia Tutorial" href="http://www.nukepedia.com/written-tutorials/expressions-101" target="_blank" rel="noopener">Matt Estela and Pedro Andrade</a> and similar tools, such as those from <a title="Nukepedia Tool" href="http://www.nukepedia.com/toolsets/3d/wptk" target="_blank" rel="noopener">Ivan Kokov</a>.</p>
