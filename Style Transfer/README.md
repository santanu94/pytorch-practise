<h1>Neural Style Transfer</h1>
An implementation of the paper <strong>A Neural Algorithm of Artistic Style</strong> by Leon A. Gatys, Alexander S. Ecker and Matthias Bethge, demonstrating on of
the many ways neural networks can be used to apply style from one image to another image (a content image). The paper used the frozen VGG-19 model with layers
'conv1_1’, ‘conv2_1’, ‘conv3_1’, ‘conv4_1’ and ‘conv5_1’ as style layers and 'conv4_2' as the content layer.

Style loss is calculated from the style layer(s) of the content image and generated image, while content loss is calculated from the content layer of the 
content image and generated image.

A key finding from this paper is that a network can represent the style information and content information in different layers.

<a href="https://arxiv.org/pdf/1508.06576.pdf">Link</a> to the original paper.
