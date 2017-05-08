# The Ethics of the Internet of Things

## Emily Gorcenski

<p class="text-calming">@EmilyGorcenski</p>

Note: Introduce talk. Why ethics at a JavaScript conference?


---


### <span class="text-warning">Content Warnings</span>

Frank talk of injury and death

Discussion of sexual assault

Image of raw meat

Note: Cover the content warnings!


---


### <span class="text-wow">Who am I?</span>

<p class="fragment fade-in">Senior Data Scientist</p>
<p class="fragment fade-in">Mathematician &amp; Engineer</p>
<p class="fragment fade-in">Aerospace, Biotechnology, Finance</p>

Note: Current career in data science, mostly writing python. But formal background in engineering and regulated industries gives unique perspective on the applications of ethics and regulation.


---


### The Internet of Things
<span class="text-calming">Putting the internet into ordinary devices and services</span>

Note: What is is the IoT? Putting the internet where it doesn't normally belong. Many things had computers, but connectivity and *consumer access* changes the game. GO DOWN.


vvv


<p><img data-src="images/bread-machine.jpg" style="height: 500px"></p>
<p><a style="font-size: 14pt" href="https://www.amazon.com/Zojirushi-BB-CEC20-Supreme-2-Pound-Loaf-Breadmaker/dp/B002XVUAOU">https://www.amazon.com/Zojirushi-BB-CEC20-Supreme-2-Pound-Loaf-Breadmaker/dp/B002XVUAOU</a></p>

Note: inside JavaScript bread baking joke


---


### Ethics

<p><img data-src="images/trolley-problem.jpg" style="height: 450px"></p>
<p><a style="font-size: 14pt" href="http://nymag.com/selectall/2016/08/trolley-problem-meme-tumblr-philosophy.html">http://nymag.com/selectall/2016/08/trolley-problem-meme-tumblr-philosophy.html</a></p>

Note: introduce ethics via self-driving cars, trolley meme. Highly popular, makes for problem we can conceptualize academically and also dank memes. GO DOWN.


vvv

<blockquote class="twitter-tweet" style="width: 1000px" data-lang="en"><p lang="en" dir="ltr">Why do people think the trolley problem is critical for self-driving cars? The trolley problem wasn&#39;t critical even for trolleys.</p>&mdash; Andrew Ng (@AndrewYNg) <a href="https://twitter.com/AndrewYNg/status/791648421291528197">October 27, 2016</a></blockquote>

Note: Frame previous slide in terms of absurdity. GO DOWN.


vvv

<!--<p class="text-calming">Ethical dilemmas occur when we encounter competing ethical frameworks.</p>
<br>-->
<p class="text-calming">We don't often face true ethical dilemmas in tech.</p>
<br>
<p class="fragment current-only text-warning">We just act without ethics.</p>

Note: Core takeaway here. Ethical dilemmas happen when we have competing ethical frameworks. JS Community had one of the most interesting ethical dilemmas in tech in a long time! Comment about absense of ethics not an indictment, but rather an observation of a praxis without a backing code of professional ethics or regulation.


---


<span class="text-calming">In practice, ethics are about the<br><span class="text-warning">analysis of harm</span> and the <span class="text-warning">mitigation of risk.</span>

Note: So what is ethics about in those fields I talked about? The engineering process by which we evaluate potential harms and the work we do to actively mitigate risk and provide remediation.


---


<p class="text-calming">Harm happens in three ways:</p>
- Malfeasance (e.g. hacking);
- Failure (e.g. bugs);
- Edge Case (e.g. unplanned scenario).

Note: the axes of harm. Talk about Mirai in the context of the first point. First point super important but a lot of it is covered by other two.


---


<img data-src="images/water-spill.png" style="height: 525px"><br>
<a style="font-size: 14px" href="https://twitter.com/AndrewX192/status/846134369584492544">https://twitter.com/AndrewX192/status/846134369584492544</a>

Note: Example of bug and how IoT world differs from webapp space


---


<video style="height: 600px" controls muted>
    <source src="images/chicken-breast.mp4" type="video/mp4" />
</video>

Note: set it up, get ready for the drop


---


<p class="text-calming">In 2015, a woman in Lancaster, PA called police to report a rape. Police found her Fitbit and analyzed the data.</p>
<p class="text-warning">She was charged and convicted with making false statements.</p>

Note: pause. Describe incident. GO DOWN.


vvv


<p class="text-warning">The prosecuting attorney said the Fitbit data "sealed the deal."</p>
<br>
<p><a style="font-size: 14px" href="http://www.pennlive.com/news/2016/04/watch_today_segment_on_how_fit.html">http://www.pennlive.com/news/2016/04/watch_today_segment_on_how_fit.html</a></p>

Note: This was not a spurious triviality. This was central to the case.


---


<span class="text-calming">Our devices can bear witness against us without any assurance of accuracy or quality.</span>

Note: Now we have real concerns about the surveillance potential. What is being done to ensure quality? Nothing. GO DOWN


vvv


- 2017: A man is charged with the murder of his wife based on her Fitbit motion tracking.<br>
<a style="font-size: 14px" href="http://www.cnn.com/2017/04/25/us/fitbit-womans-death-investigation-trnd/">http://www.cnn.com/2017/04/25/us/fitbit-womans-death-investigation-trnd/</a>
- 2016: Police use data from a smart water meter in a murder investigation.<br>
<a style="font-size: 14px" href="http://5newsonline.com/2016/12/28/bentonville-police-use-smart-water-meters-as-evidence-in-murder-investigation/">http://5newsonline.com/2016/12/28/bentonville-police-use-smart-water-meters-as-evidence-in-murder-investigation/</a>
  - Police also filed a warrant for Amazon Echo data in the same investigation.<br>
  <a style="font-size: 14px" href="http://5newsonline.com/2016/12/27/privacy-advocates-raise-concerns-over-bentonville-pds-warrant-for-amazon-echo-recordings/">http://5newsonline.com/2016/12/27/privacy-advocates-raise-concerns-over-bentonville-pds-warrant-for-amazon-echo-recordings/</a>

Note: Rattle off some recent examples


---


<p class="text-calming">Who goes to jail when a device<br>
<span class="text-warning">bears false witness?</span></p>
<br>
<p class="text-calming">Who is liable when a device<br>
<span class="text-warning">causes an accident?</span></p>

Note: bring it home with this point. Set up for Google SDC and Uber fuckups


---


<img data-src="images/google-crash.png" style="height: 525px"><br>
<a style="font-size: 14px" href="https://www.youtube.com/watch?v=I9T6LkNm-5w">https://www.youtube.com/watch?v=I9T6LkNm-5w</a>

Note: Google SDC crash, first time in history (at least US) a SDC was responsible. Don't forget the next slide.


---


<p class="text-calming">Google acknowledged fault:</p>
<p class="text-calming">The car <span class="text-warning">"predicted that [the bus] would yield to us because we were ahead of it."</span></p>

Note: also historical, first time a muni bus would have yielded.


---


<blockquote class="twitter-tweet" style="width: 1000px" data-lang="en"><p class="text-calming">So the actions of autonomous robots devising their own means to attain a task <span class="text-warning">may not be subject to liability</span> under any of theories of tort...</p></blockquote>
<p><a style="font-size: 14pt" href="https://works.bepress.com/curtis_karnow/9/download/">The Hon. Curtis E. A. Karnow, "The application of traditional tort theory to embodied machine intelligence," The Robotics and Law Conference, Stanford, CA, 2013</a></p>

Note: legal challenges. What does this mean for us as developers? Are we OK with living liability free?


---


<span style="font-family: courier; font-size: 60pt">left-pad</span>

Note: bring it home with left-pad. Most interesting ethical dilemma in a decade. Challenges in IoT context.


---


### <span class="text-wow">What do we do?</span>

<p class="fragment fade-in">Set expecations with your boss</p>
<p class="fragment fade-in">Prepare to say no</p>
<p class="fragment fade-in">Hold frank discussions with coworkers</p>
<p class="fragment fade-in text-warning">Know your limit</p>


---


<p class="text-wow">Thank you!</p>
<p class="text-calming">@EmilyGorcenski</p>