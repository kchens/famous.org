##What's new?


###Mixed Mode: 


Famous now unites DOM and WebGL under a single coordinate system. Borrowing concepts from modern game development, Famous structures applications in a scene graph hierarchy that makes manipulating HTML and WebGL together simple and programatic.


###Rebuilt Architecture: 


The new Famous Engine produces basically no garbage at all. It has an improved event based system for updating transforms, which avoids unnecessary matrix multiplications. The result is a powerful new Engine delivering consistent, smooth, 60fps animations with even better performance than before

<iframe src='http://staging.famous.org/examples/index.html?block=layout&detail=false&header=false' scrolling='no' class='code-block' allowtransparency='true'></iframe>


###3D Physics Engine:


Famous introduces a brand new 3D physics engine that brings real life movement to your applications. Living it's own module entirely, you can incorporate as little or as much of it as you want into your applications.


<iframe src='http://staging.famous.org/examples/index.html?block=physics&detail=false&header=false' scrolling='no' class='code-block' allowtransparency='true'></iframe>


###Embedding Made Easy: 


On top of a full redesign of the Famous Engine, we've created a robust cloud platform that makes deploying Famous projects dead simple. Using the Famous CLI, you can now incorporate entire Famous projects into your existing websites with only two lines of code.

<pre><code class="lang-bash">
<span class="blue">$</span> famous deploy

Share: 

<span class="yellow">https://api-te.famo.us/codemanager/v1/containers/1abe61ec-2557-4f45-a2fd-c13d3a47b17f/share</span>

Embed:

<span class="blue">&lt;script src=&quot;https://assets-te.famo.us/embed/embed.js&quot;&gt;&lt;/script&gt;
&lt;div class=&quot;famous-container&quot; data-famous-container-identifier=&quot;1abe61ec-2557-4f45-a2fd-c13d3a47b17f&quot;&gt;&lt;/div&gt;</span>

</code></pre>

###Streamlined Events:


The eventing system has been greatly simplified promoting encapsulation of reusable and sharable components.


###Improved Sizing:


We've redesigned our sizing API to greatly increase flexibility. Developers can now fine-tune sizing independently for X, Y, and Z axes. 


###Modularity: 


We've built Famous with extensibility in mind. In particular, we decoupled our scene graph from rendering by using a draw command buffer. This paves the way for various integrations and allows for frameworks to be built on top of our drawing API. 


###MIT License:


We've moved to a fully open source MIT license that encourages active participation from the community.  Additionally, we've redesigned the website and the learning resources to make Famous more accessible to everyone. 
