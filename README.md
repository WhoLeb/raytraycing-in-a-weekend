# raytraycing-in-a-weekend

<p>This is me literally following the guide from the web-textbook <a href="https://raytracing.github.io/books/RayTracingInOneWeekend.html#thevec3class/colorutilityfunctions"> Ray tracing in one weekend </a>.</p>
<p>It was super easy and fun! I will soon add the resulting picture(i failed to do so:sob::sob::sob:).</p>
<p>It is <a href="https://github.com/WhoLeb/raytraycing-in-a-weekend/blob/main/x64/Release/image.jpg"> here</a>, sorry(((</p>
<p><a href="https://raw.githubusercontent.com/WhoLeb/raytraycing-in-a-weekend/main/x64/Debug/Image_after_multithreading.png">Here</a> is a picture of the balls after I added multithreading. Nothing changed. Wow. </p> 
<p><s>Unfortunately this ray tracer is not even multithreading and is working on the CPU so it takes a shitload of time to render and not even in a window but to a ppm file.</s> </p>
<p>Luckily I was persistent enough to make the code multithreaded! Now it works on 8 threads(I didn't bother to make it take up dynamical amount of threads) and it is significantly faster!<br>Before that the rendering took a long time(around an hour on my laptop) now on my pc it only took 380 seconds, which is only around 6 minutes... Now that I've written it out I realised that it is still way to slow... Anyway, hope to make it computed on the gpu soon so hopefully it will get better.</p>
<p>Hopefully the next two books will show how to render on screen and in realtime))</p>
