# j01: Layering with Aseprite
## Journal by Austin Kleinecke
I use the tool [Aseprite](https://www.aseprite.org/){:target="_blank"} for drawing and animating pixel art / sprite work. A common feature amongst most drawing programs is to allow the **separation of different layers** of the drawing onto different transparencies. This can be an important feature for artists, as it allows easier tracking and adjusting of different sections of their art.

The Layer interface demonstrates an application of **User Control and Freedom**, a [usability guideline for using concepts in the real world](https://www.nngroup.com/articles/ten-usability-heuristics/){:target="_blank"} to allow users the freedom to ability to stay in control and make mistakes without suffering through an overtly stressful experience.

Originating via the program Fauve Matisse (later known as [Macromedia xRes](https://en.wikipedia.org/wiki/Macromedia_xRes){:target="_blank"}) by [](https://en.wikipedia.org/wiki/Fauve_Software){:target="_blank"} in 1993, the layer tool **allows for images to be drawn on top of one another**, often used to enable image manipulation or even provide a timeline for animation.

For this journal, I set out to create a smiley face that has several **different expressions**, but uses the same basic head shape and color. However, before we can really get started with using the Layer tool, we first need to identify it. 
![AespriteUIOverview](/assets/Aesprite_Overview.png)

If we look at the UI of Aesprite, we can notice several key sections. Starting from left to right, we can identify thses by simple visual indicators.

On the far left, we notice a grouping of colors and a color slider.
In the middle we see what looks to be a canvas. And on the right we see a small section containing some text **"Layer 1"** and some brushes.

For now, we will focus on the text that says "Layer 1".
![AespriteUILayer0](/assets/Aesprite_Layer_View_0.png)

On closer inspection, we can assume this tall rectangle contains our layers. We can assume that, because it already contains an object with a title "Layer 1". But I also notice some other buttons here; a **Green Eyeball** symbol, **Green Lock** symbol, **White Dots** symbol, what looks to be a **White Options** sign, and some kind of **White Layers** button.

Unfortunately, hovering my mouse over these green buttons does not seem to yield any immediate **feedback**; what I mean is that it seems to lacks any sort of immediate and obvious effect or pop-up information to let me know what something does, so I'm not too sure what these buttons do. 

However, if I look around my screen, I do eventually notice that there is some text in the bottom left that changes as I hover over buttons.

This is what is shown when I hover my mouse over the **Green Eyeball** symbol.

![Aesprite_Layer_Info](/assets/Aesprite_Layer_Info_0.png)

And this is what is shown when I hover my mouse over the **Green Lock** symbol.

![Aesprite_Layer_Info2](/assets/Aesprite_Layer_Info_1.png)

So although the **feedback** for hovering over these buttons isn't obvious, it does seem to still exist and tell me what these buttons do. Using this information, I can assume that for my needs I don't really care about any of the other buttons, and that the the visibility / green eyeball button should work just fine.

Now I need to make a new layer. As someone who has used these types of programs before, my immediate intuition is to right click inside the layer box. Thankfully my intuition is correct, and I can easily create a new layer from this pop-up menu. I also notice that there appears to be a hot-key for creating layers without opening this menu directly, providing some future **ease of use**. Upon clicking the **New Layer** button, a new layer appears just above my current layer.

![Aesprite_New_Layer](/assets/Aesprite_New_Layer.png)
![Aesprite_Layer_2](/assets/Aesprite_Layer_View_1.png)

Now that I have figured out multiple layers, I would like to be able to differentiate between these layers. I think that having non-descriptive layer titles like "Layer 1" and "Layer 2" won't be really helpful in the long run. Thankfully I saw another option that might be helpful when I right clicked the layer. If we check the menu again, we can open a "Properties" window. Here, it looks like I can change the name of my layer.

![Aesprite_Properties_Option](/assets/Aesprite_Properties_Hover.png)
![Aesprite_Properties_Window](/assets/Aesprite_Properties_Window.png)
![Aepsrite_NewLayer_Name](/assets/Aesprite_New_Layer_Name.png)

Sweet! Now that I know how to create a layer and change both its name and visibility, I can actually start to draw on different layers. But how do I know what layer I'm on? If we look closely, we can see that Aesprite provides a bit of visual **feedback** when we click on a new layer, telling us which one is currently selected.

![Aesprite_Select_1](/assets/Aesprite_Layer_Select_1.png)
![Aesprite_Select_1](/assets/Aesprite_Layer_Select_2.png)

As a final note, we gain some more nice visual **feedback** upon changing the visibility status of our layers. Hidden layers display a **closed red eye**, while visible layers show us an **open green eye**. Awesome touch!

I can now use what I've learned to make four different faces by using only five different layers. We have our lowest layer as our base, two layers for the different mouths, and two more layers for the different eyes. By toggling between these different eyes and mouths, we can make four different faces!

![Aesprite_Face_1](/assets/Aesprite_Pensive_1.png)
![Aesprite_Face_2](/assets/Aesprite_Pensive_2.png)
![Aesprite_Face_3](/assets/Aesprite_Happy_1.png)
![Aesprite_Face_4](/assets/Aesprite_Happy_2.png)

As we can see, the visual **feedback** for this program is a bit of a mixed bag. Although it offers some cool indicators for button changing, like the red/green visibility icons, figuring out what these buttons do is not immediately obvious and offers little actual **feedback**. The problem worsens when you hover over some other buttons that may not be as obvious, as the visual description is either not helpful or not even there. I'd suggest a simple pop-up window or notification after hovering over an element for a few seconds that offers a brief title or description of what something does, so that the user can easily identify the tools they need.