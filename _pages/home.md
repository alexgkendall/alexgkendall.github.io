---
layout: single
read_time: false
comments: false
share: false
permalink: /
gallery:
  - url: https://www.youtube.com/watch?v=Rn9mvSDdSqo
    image_path: /assets/images/cvpr2019.jpg
    alt: "CVPR Conference Workshops"
    caption: "CVPR Conference Workshops in [2019](https://sites.google.com/view/wad2019), [2020](https://youtu.be/rfXQH3CyL4Q?si=WeN-VRR1A51ogxKG), [2021](https://www.youtube.com/watch?v=Va-F4qtTQ6g), [2022](https://www.youtube.com/watch?v=UhDUczF47VI), [2023](https://www.youtube.com/watch?v=Rn9mvSDdSqo)."
  - url: https://blogs.nvidia.com/blog/gtc-2024-auto-sessions/
    image_path: /assets/images/nvidia-gtc.jpg
    alt: "NVIDIA GTC 2024"
    caption: "[NVIDIA GTC 2024: keynote presentation and panel discussion](https://blogs.nvidia.com/blog/gtc-2024-auto-sessions/)."
  - url: https://podcasts.apple.com/gb/podcast/ai-takes-the-wheel-new-advances-in-autonomous-driving/id1172218725?i=1000639823423
    image_path: /assets/images/exponential.jpg
    alt: "2023 Azeem Azhar’s Exponential View"
    caption: "2023 Azeem Azhar’s Exponential View ([Podcast](https://podcasts.apple.com/gb/podcast/ai-takes-the-wheel-new-advances-in-autonomous-driving/id1172218725?i=1000639823423), [Video](https://youtu.be/m1-V-48iodA?si=5zCP7YJ47Lz_hvrO))"
  - url: https://www.gatesnotes.com/Autonomous-Vehicles
    image_path: /assets/images/kendall-gates.jpg
    alt: "2023 My ride with Bill Gates around London"
    caption: "[2023 My ride with Bill Gates around London](https://www.gatesnotes.com/Autonomous-Vehicles)."
  - url: https://www.roadtoautonomy.com/wayve/
    image_path: /assets/images/road-to-autonomy.jpg
    alt: "The Road to Autonomy Podcast, 2024"
    caption: "[The Road to Autonomy Podcast, with Grayson Brulte](https://www.roadtoautonomy.com/wayve/)."
  - url: https://www.youtube.com/watch?v=_oosfExLcBg
    image_path: /assets/images/cogx.jpg
    alt: "CogX 2023"
    caption: "[CogX 2023: panel with Gerard Grech, Dr Doug Gurr, Robyn Scott and Alex Kendall](https://www.youtube.com/watch?v=_oosfExLcBg)"
  - url: https://www.youtube.com/watch?v=AIrcSQMlhyc
    image_path: /assets/images/tech-leaders.jpg
    alt: "2023 Tech Leaders Podcast"
    caption: "[2023 Tech Leaders Podcast with Gareth and Kerensa](https://youtu.be/AIrcSQMlhyc?si=QiUCzGP1lXwTS-7D)."
  - url: https://www.youtube.com/watch?v=36qNyLocakY
    image_path: /assets/images/robot-brains.jpg
    alt: "The Robot Brains Podcast with Pieter Abbeel"
    caption: "[2022 The Robot Brains Podcast with Pieter Abbeel](https://www.youtube.com/watch?v=36qNyLocakY)."
  - url: https://ark-invest.com/podcast/ep-90-autonomous-vehicles-wayve-ai/
    image_path: /assets/images/fyi-ark.png
    alt: "ARK Invest FYI Podcast with Tasha Keeney and Brett Winton"
    caption: "[2021 ARK Invest FYI Podcast with Tasha Keeney and Brett Winton](https://ark-invest.com/podcast/ep-90-autonomous-vehicles-wayve-ai/)."
  - url: https://sifted.eu/articles/wayves-alex-kendall-sifted-podcast
    image_path: /assets/images/sifted.jpg
    alt: "2023 The Sifted Podcast with Eleanor Warnock"
    caption: "[2023 The Sifted Podcast with Eleanor Warnock](https://sifted.eu/articles/wayves-alex-kendall-sifted-podcast)."
  - url: https://blogs.nvidia.com/blog/av-2-0-wayve/
    image_path: /assets/images/nvidia.jpg
    alt: "2023 Nvidia’s The AI Podcast"
    caption: "[2023 Nvidia’s The AI Podcast](https://blogs.nvidia.com/blog/av-2-0-wayve/)."
---

<style>
  .half {
      display: flex; /* Ensures the elements inside are laid out in a row */
      justify-content: space-around; /* Adds space around the items */
      align-items: center; /* Vertically centers the items in the container */
      width: 100%; /* Makes the figure element take the full width of its parent */
  }
  .half video {
      width: 100%; /* Makes the video take the full width of its container */
      height: auto; /* Ensures the height adjusts to maintain the aspect ratio */
  }
  .half img {
      width: 100%; /* Adjusts the image to take the full width of its container */
      height: auto; /* Maintains the aspect ratio of the image */
  }

  .gallery-container {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
  }

  .gallery-container.single figure {
    flex: 0 1 100%;
  }

  .gallery-container.half figure {
    flex: 0 1 calc(47% - 5px);
  }

  .gallery-container.third figure {
    flex: 0 1 calc(31% - 10px);  /* Adjusted to divide the space into thirds precisely */
  }

  .gallery-image, .fixed-height-img {
    height: 200px; /* Fixed height for all images */
    object-fit: cover; /* Ensures the image covers the fixed dimension without distortion */
    width: 100%; /* Adjust width to maintain aspect ratio */
  }

  .gallery-container figure {
    display: inline-block;  /* Makes sure figures are aligned as inline elements */ß
    text-align: center;    /* Center-aligns the caption */
    margin: 5px;          /* Provides some space around each image */
    vertical-align: top;   /* Aligns items to the top, useful for multi-row galleries */
  }

  /* Adjustments for smaller screens */
  @media (max-width: 450px) {
    .gallery-container figure {
      flex: 0 1 100%;
    }
  }
  @media (max-width: 768px) {
  .gallery-container.half figure,
  .gallery-container.third figure {
    flex: 0 1 calc(47% - 5px)!important;  /* Using `!important` to ensure this rule takes precedence */
  }
}
  @media (max-width: 450px) {
  .gallery-container.half figure,
  .gallery-container.third figure {
    flex: 1 0 100%!important;  /* Using `!important` to ensure this rule takes precedence */
  }
}

  .gallery-container figcaption {
    font-size: 1.1em; /* Increases the font size of captions */
  }

</style>

## I’m passionate about building Embodied AI, deep tech startups and generally anything adventurous.

I co-founded and am CEO at [Wayve](https://wayve.ai/) – the leader in developing embodied AI for autonomous driving. I started working on this technology at Cambridge University where my PhD research showed how end-to-end deep learning could enable safe and real-time scene understanding. I founded Wayve in 2017 with the belief that end-to-end AI would unlock generalised autonomy at global scale. Wayve was first to deploy end-to-end AI on public roads and our AV2.0 approach enables safe, generalisable and trustworthy autonomy. We've raised $1.3b in funding and are a team of over 300 across London, Vancouver and Silicon Valley. Interested in joining our mission? We’re hiring [here](https://wayve.ai/careers/join-us/)!

<figure>
	<a href="/assets/images/team.jpg"><img src="/assets/images/team.jpg"></a>
	<figcaption>Wayve team, April 2024.</figcaption>
</figure>

My life began in the South Island of New Zealand where I learned a sense of adventure in the mountains. I spent countless hours hiking, mountain biking and exploring our rivers and beaches, fostering a passion for conservation of our natural world. 

I developed a deep curiosity playing with science and technology, teaching myself how to solder circuits, code computer games and build drones. I was inspired by leading sportsmen/women’s achievements (like sailing and rugby) and the culture of innovation that I was exposed to in New Zealand.

I won a scholarship to study engineering at Auckland University. I then tried to start a few (unsuccessful) companies and built too many robots in my dorm room before graduating first in my engineering class. I learned to surf during this time at Auckland's beaches like O’Neill and Piha which would later provide inspiration for naming Wayve.

<figure>
	<a href="/assets/images/avalanchepeak.jpg"><img src="/assets/images/avalanchepeak.jpg"></a>
	<figcaption>Avalanche Peak, New Zealand. Photo taken by a Skydio2 drone.</figcaption>
</figure>

I was fortunate enough to win a [Woolf Fisher Scholarship](http://www.woolffishertrust.co.nz/) to Cambridge where I completed my PhD in deep learning for computer vision and robotics. I worked with [Roberto Cipolla](https://mi.eng.cam.ac.uk/~cipolla/), [Yarin Gal](https://www.cs.ox.ac.uk/people/yarin.gal/website/), [Vijay Badrinarayanan](https://scholar.google.co.uk/citations?user=WuJckpkAAAAJ&hl=en) and others to develop some of the first end-to-end deep learning methods for semantic segmentation, localisation, stereo and scene understanding, and explored how geometry and uncertainty can be used to better understand these systems. My work was awarded the 2018 [BMVA Prize](https://britishmachinevisionassociation.github.io/bursaries/sullivan-prize.html) and 2019 [ELLIS Prize](https://ellis.eu/en/news/ellis-phd-award).

<figure class="half">
    <a href="/assets/images/trinity.jpg"><img src="/assets/images/trinity.jpg"></a>
    <a href="/assets/images/segnet.mp4"><video controls="controls"><source src="/assets/images/segnet.mp4" type="video/mp4"></video></a>
    <figcaption>Trinity College, Cambridge, where I was a PhD student and Research Fellow. My research on multi-task scene understanding and uncertainty estimation, enabling AVs which can safely drive in dynamic scenes without HD-maps.</figcaption>
</figure>

I was elected as a Fellow of Trinity College, Cambridge. I loved spending time with startups like Skydio and Scape which got me excited about the potential of venture-backed growth. Ultimately I became convinced that end-to-end machine learning would become the future for robotics. This was a very contrarian idea at the time and laughed at by many… but led to the founding of Wayve.

Wayve began in a residential house, just outside Cambridge University. We founded the company in 2017 with the mission to ‘reimagine autonomous mobility with embodied intelligence'. We demonstrated world-firsts of end-to-end deep learning driving on public roads, with model-free and model-based reinforcement learning, imitation learning and sim2real transfer. We then raised our Series A funding and moved to London.

<figure class="half">
    <a href="/assets/images/hoffice.jpg"><img src="/assets/images/hoffice.jpg"></a>
    <a><iframe src="https://www.youtube.com/embed/eRwTbRtnT1I?si=0ss0gspK6C8cV4hR" frameborder="0" allowfullscreen></iframe></a>
    <figcaption>Unveiling our first autonomous vehicle we built in our garage in Cambridge, UK. <a href="https://youtu.be/eRwTbRtnT1I?si=pLGJhA8QcdH3bUH1">An early result, learning to drive with reinforcement learning.</a></figcaption>
</figure>

Today Wayve is the leading developer of Embodied AI technology for automated driving. We've raised $1.3b from top investors like SoftBank, Microsoft, NVIDIA, and Eclipse Ventures and are a team of over 300 people across London, Vancouver and Silicon Valley. We’ve been operating our fleet on public roads since 2018, including AV trials with major grocery delivery fleets like Asda and Ocado Group. Wayve’s innovative AI technology enables greater generalisation to the long-tail of edge cases, improved safety, while eliminating the need for high-definition maps and complex sensors, marking a significant leap in the scalability of autonomous mobility.

<figure class="half">
    <iframe src="https://www.youtube.com/embed/L_O6mQIQ3Eg?si=FkJdUl3t_oh9skgg" frameborder="0" allowfullscreen></iframe>
    <iframe src="https://www.youtube.com/embed/NNqkx8sigRY?si=At37-z6hzIiZOJMA" frameborder="0" allowfullscreen></iframe>
    <figcaption>A video of our AV2.0 technology driving autonomously through central London. A fun video showcasing life at Wayve.</figcaption>
</figure>

<div id='talks'></div>
## Selected Talks and Interviews

{% include gallery id="gallery" class="full" %}

<div id='publications'></div>
## Publications

Also on [Google Scholar](https://scholar.google.co.uk/citations?user=hE2mTp4AAAAJ)

- [LingoQA: Video question answering for autonomous driving.](https://arxiv.org/abs/2312.14115) <span style="color: green;">arXiv 2023</span>. Ana-Maria Marcu, Long Chen, Jan Hünermann, Alice Karnsund, Benoit Hanotte, Prajwal Chidananda, Saurabh Nair, Vijay Badrinarayanan, Alex Kendall, Jamie Shotton, Elahe Arani, Oleg Sinavski
- [GAIA-1: A generative world model for autonomous driving.](https://arxiv.org/abs/2309.17080) <span style="color: green;">arXiv 2023</span>. Anthony Hu, Lloyd Russell, Hudson Yeo, Zak Murez, George Fedoseev, Alex Kendall, Jamie Shotton, Gianluca Corrado
- [Model-based imitation learning for urban driving.](https://arxiv.org/abs/2210.07729) <span style="color: green;">NeurIPS 2022</span>. Anthony Hu, Gianluca Corrado, Nicolas Griffiths, Zak Murez, Corina Gurau, Hudson Yeo, Alex Kendall, Roberto Cipolla, Jamie Shotton
- [Geometry and Uncertainty in Deep Learning for Computer Vision.](https://www.repository.cam.ac.uk/items/1a01f251-1437-46fe-9fde-2a46b4dd6da6) <span style="color: green;">PhD Thesis, University of Cambridge, 2017</span>. Alex Kendall
- [FIERY: Future Instance Prediction in Bird’s-Eye View from Surround Monocular Cameras.](https://arxiv.org/abs/2104.10490) <span style="color: green;">ICCV (Oral), 2021</span>. Anthony Hu, Zak Murez, Nikhil Mohan, Sofía Dudas, Jeffrey Hawke, Vijay Badrinarayanan, Roberto Cipolla, Alex Kendall.
- [Probabilistic Future Prediction for Video Scene Understanding.](https://arxiv.org/abs/2003.06409) <span style="color: green;">ECCV, 2020</span>. Anthony Hu, Fergal Cotter, Nikhil Mohan, Corina Gurau, Alex Kendall.
- [Urban Driving with Conditional Imitation Learning.](https://arxiv.org/abs/1912.00177) <span style="color: green;">ICRA, 2020</span>. Jeffrey Hawke, Richard Shen, Corina Gurau, Siddharth Sharma, Daniele Reda, Nikolay Nikolov, Przemyslaw Mazur, Sean Micklethwaite, Nicolas Griffiths, Amar Shah, Alex Kendall.
- [Orthographic Feature Transform for Monocular 3D Object Detection.](https://arxiv.org/abs/1811.08188) <span style="color: green;">BMVC (Oral, Best Paper Honourable Mention), 2019</span>. Thomas Roddick, Alex Kendall, Roberto Cipolla.
- [Learning to Drive from Simulation without Real World Labels.](https://arxiv.org/abs/1812.03823) <span style="color: green;">ICRA, 2019</span>. Alex Bewley, Jessica Rigley, Yuxuan Liu, Jeffrey Hawke, Richard Shen, Vinh-Dieu Lam, Alex Kendall.
- [Learning to Drive in a Day.](https://arxiv.org/abs/1807.00412) <span style="color: green;">ICRA, 2019</span>. Alex Kendall, Jeffrey Hawke, David Janz, Przemyslaw Mazur, Daniele Reda, John-Mark Allen, Vinh-Dieu Lam, Alex Bewley, Amar Shah.
- [Multi-Task Learning Using Uncertainty to Weigh Losses for Scene Geometry and Semantics.](https://arxiv.org/abs/1705.07115) <span style="color: green;">CVPR (Spotlight Oral), 2018</span>. Alex Kendall, Yarin Gal, Roberto Cipolla.
- [Concrete Problems for Autonomous Vehicle Safety: Advantages of Bayesian Deep Learning.](https://www.ijcai.org/Proceedings/2017/0661.pdf) <span style="color: green;">IJCAI (Special Track - AI & Autonomy), 2017</span>. Rowan McAllister, Yarin Gal, Alex Kendall, Mark van der Wilk, Amar Shah, Roberto Cipolla, Adrian Weller.
- [Concrete Dropout.](https://arxiv.org/abs/1705.07832) <span style="color: green;">NeurIPS, 2017</span>. Yarin Gal, Jiri Hron, Alex Kendall.
- [Geometric loss functions for camera pose regression with deep learning.](https://arxiv.org/abs/1704.00390) <span style="color: green;">CVPR (Spotlight Oral), 2017</span>. Alex Kendall, Roberto Cipolla.
- [What Uncertainties Do We Need in Bayesian Deep Learning for Computer Vision?](https://arxiv.org/abs/1703.04977) <span style="color: green;">NeurIPS (Spotlight Oral), 2017</span>. Alex Kendall, Yarin Gal.
- [Bayesian SegNet: Model Uncertainty in Deep Convolutional Encoder-Decoder Architectures for Scene Understanding.](https://arxiv.org/abs/1511.02680) <span style="color: green;">BMVC, 2017</span>. Alex Kendall, Vijay Badrinarayanan, Roberto Cipolla.
- [End-to-End Learning of Geometry and Context for Deep Stereo Regression.](https://arxiv.org/abs/1703.04309) <span style="color: green;">ICCV (Spotlight Oral), 2017</span>. Alex Kendall, Hayk Martirosyan, Saumitro Dasgupta, Peter Henry, Ryan Kennedy, Abraham Bachrach, Adam Bry.
- [SegNet: A Deep Convolutional Encoder-Decoder Architecture for Image Segmentation.](https://arxiv.org/abs/1511.00561) <span style="color: green;">PAMI, 2017</span>. Vijay Badrinarayanan, Alex Kendall, Roberto Cipolla.
- [Modelling Uncertainty in Deep Learning for Camera Relocalization.](https://arxiv.org/abs/1509.05909) <span style="color: green;">ICRA, 2016</span>. Alex Kendall, Roberto Cipolla.
- [PoseNet: A Convolutional Network for Real-Time 6-DOF Camera Relocalization.](https://arxiv.org/abs/1505.07427) <span style="color: green;">ICCV, 2015</span>. Alex Kendall, Matthew Grimes, Roberto Cipolla.
- [On-board object tracking control of a quadcopter with monocular vision.](https://ieeexplore.ieee.org/document/6842280) <span style="color: green;">ICUAS, 2014</span>. Alex Kendall, Nishaad Salvapantula, Karl Stol.

## Awards and Prizes:

- 2020 [Forbes 30 Under 30](https://www.forbes.com/profile/alex-kendall/?list=30under30-europe-big-money-startups&sh=68147eb7283f) for contributions to technology entrepreneurship and 2024 Alumni award
- 2019 [ELLIS European PhD Prize](https://ellis.eu/news/ellis-phd-award) for outstanding research achievements in artificial intelligence
- 2018 [BMVA Prize](https://www.bmva.org/bursaries/sullivan-prize.html) for best UK PhD Thesis in Computer Vision
- 2018 PITCH Champions at [WebSummit](https://youtu.be/sn-_29bknz8?t=548)
- 2017 Research Fellowship at Trinity College, Cambridge University

<div id='news'></div>
## Selected News and Media:

- 2024 Wayve's $1.3b Series C fundraise from SoftBank, Microsoft and NVIDIA ([Financial Times](https://www.ft.com/content/a5704e29-545c-45e6-b7e3-d0a8cda285c4), [New York Times](https://www.nytimes.com/2024/05/06/technology/wayve-ai-self-driving-vehicles.html), [TechCrunch](https://techcrunch.com/2024/05/06/wayve-raises-1-billion-led-by-softbank-to-take-self-driving-to-cars-and-robots/))
- 2023 My ride with Bill Gates around London ([GatesNotes](https://www.gatesnotes.com/Autonomous-Vehicles))
- 2023 The introduction of the Automated Vehicles Bill ([PA Media](https://www.dailymail.co.uk/wires/pa/article-12720293/Bill-enable-self-driving-cars-used-Britain-s-roads.html), [Bloomberg](https://www.bloomberg.com/news/articles/2023-11-09/uk-sees-fully-self-driving-cars-hitting-its-roads-around-2026), [The Times](https://drive.google.com/file/d/1jWBmVtWRhoPwk1JnkJqLIdi_OyJWxpDj/view?usp=drive_link))
- 2023 Wayve introduces LINGO-1 ([Financial Times](https://www.ft.com/content/a5a5f2ea-e95f-4358-9f80-d10c5ed90453), [MIT Tech Review](https://www.technologyreview.com/2023/09/14/1079458/this-driverless-car-company-is-using-chatbots-to-make-its-vehicles-smarter/), [Fortune](https://fortune.com/2023/09/15/wayve-microsoft-backed-self-driving-car-start-up-alex-kendall-trust-ai/))
- 2021 Wayve’s Partnerships with Ocado ([TechCrunch](https://techcrunch.com/2021/10/06/wayve-the-lidar-free-self-driving-startup-raises-13-6m-from-ocado/)), Asda ([The Grocer](https://www.thegrocer.co.uk/asda/asda-to-trial-driverless-delivery-vans-in-london/659999.article)) and Microsoft ([VentureBeat](https://venturebeat.com/ai/wayve-and-microsoft-partner-to-scale-autonomous-vehicles/))
- 2019 Introducing Wayve’s technology ([TechCrunch](https://techcrunch.com/2019/04/03/wayve-claims-world-first-in-driving-a-car-autonomously-with-only-its-ai-and-a-satnav/), [Washington Post](https://www.washingtonpost.com/technology/2019/04/05/watch-self-driving-car-learn-navigate-narrow-european-streets-like-human-driver/))


---
