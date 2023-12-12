---
layout: archive
#title: "Research Group"
permalink: /group/
author_profile: true
redirect_from:
  - /research
---

{% include base_path %}

I am currently recruiting **self-motivated and dedicated** Ph.D/M.S. students with solid background in systems, mathematics, etc.. If you are interested, come and talk to me, or drop me a message.

Current Group Members:
=====

```{r 'xy_images', fig.width = 8,fig.height = 4.5, 
    fig.show='hold',fig.pos='H'fig.cap="X image (A) and Y image (B)"}


library(png);library(raster)

X <-readPNG("/images/mstile-144x144.png")
Y <-readPNG("/images/mstile-144x144.png")

#set up figure
par(mar=c(0,0,0,0), xpd=NA, mgp=c(0,0,0), 
    oma=c(0,0,0,0), ann=F, mfrow = c(1,2))
plot.new()
usr<-par("usr")

#fill plot with images
rasterImage(X, usr[1], usr[3], usr[2], usr[4])
rasterImage(Y, usr[1]+1.1, usr[3], usr[2]+1.1, usr[4])

```


<center>
	<img src="/images/mstile-144x144.png" width="144" height="144"  />
	&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
	<img src="/images/mstile-144x144.png" width="144" height="144"  />
	<br/>
	<font color="AAAAAA">Student 1</font>
	&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
	&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
	&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
	<font color="AAAAAA">Student 2</font>
</center>
<br/>




<div align="center">
	<img src="/images/mstile-144x144.png"/>
    <div align="center">
    	GitHub set up
    </div>
</div>

<div align="center">
	<img src="/images/mstile-144x144.png"/>
    <div align="center">
    	GitHub set up
    </div>
</div>

<div align="center">
	<img src="/images/mstile-144x144.png"/>
    <div align="center">
    	GitHub set up
    </div>
</div>

</p>

    
- PhD students
  - Changshi Li (2023~)
  - Chen Zhao (2022~)
- MSc students
  - Song Jin (2023~)
  - Yang Xiu (2023~)
  - Peichen Xie (2022~)
- BSc students
  - Xirui Shui (2023~)
  - Xianyi Wei (2023~)
  - Xuan Xiao (2023~)
  - Hongyu Lu (2023~)
- Visiting students
  - Yuanhua Yang (2023.6-2024.6)
 
<div style="float:left;border:solid 1px 000;margin:2px;"><img src="/images/mstile-144x144.png"  width="144" height="144" ></div>

<div style="float:left;border:solid 1px 000;margin:2px;"><img src="/images/mstile-144x144.png" width="144" height="144" ></div>
<p class="caption">Student 1 </p>
<p class="caption">Student 2 </p>
</p>
	
<div class="polaroid rotate_left">
	<img src="/images/mstile-144x144.png" alt="郁金香" width="284" height="213" />
	<p class="caption">上海鲜花港的郁金香，花名：Ballade Dream。</p>
</div>
<div class="polaroid rotate_right">
	<img src="/images/mstile-144x144.png" alt="世博中国馆" width="284" height="213" />
	<p class="caption">2010年上海世博会，中国馆。</p>
</div>



Graduated students:
=====
- Yonghong Ye, Thesis Title: Memory access strategies optimization for graph algorithms on GPU, June 2023
- Song Jin, Thesis Title: Memory management technique optimization for dynamic neural networks, June 2023
