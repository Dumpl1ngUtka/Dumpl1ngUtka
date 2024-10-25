    .sliderbody {
    max-width: 750px;
    max-height: 550px;
    font-family: 'Lato', sans-serif;
  }

  .sliderbody h4{
    text-align: center;
    margin-left: -55px;
  }
  
  
  .carousel {
    position: relative;
    padding-top: 57%;
    filter: drop-shadow(0 0 10px #0003);
    perspective: 100px;
    margin: 0 auto;
    
  }

  li.carousel__slide::marker {
    color: var(--list-marker-color);
    font-size: 15px !important;
}
  
  .carousel__viewport {
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    display: flex;
    overflow-x: scroll;
    counter-reset: item;
    scroll-behavior: smooth;
    scroll-snap-type: x mandatory;
    border-radius: 6px;
  }
  
  .carousel__slide {
    position: relative;
    flex: 0 0 100%;
    width: 100%;
    counter-increment: item;
  }
  
 
  .carousel__snapper section {
    margin: 0 auto;
  }

  .carousel__snapper {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    scroll-snap-align: center;
  }
  
  
  .carousel:hover .carousel__snapper,
  .carousel:focus-within .carousel__snapper {
    animation-name: none;
  }
 
  .carousel::before,
  .carousel::after,
  .carousel__prev,
  .carousel__next {
    position: absolute;
    top: 0;
    margin-top: 37.5%;
    width: 4rem;
    height: 4rem;
    transform: translateY(-50%);
    border-radius: 50%;
    font-size: 0;
    outline: 0;
  }  

<div id="header" align = "center">
  <h1>Hi there, I'm Damir</h1>
  <h3>Unity/C# Developer</h3>
</div>

### Connect with me
<p align="left">
<a href="https://t.me/Dumpling_Utka" target="blank"><img height="50" width="50" src="https://cdn.simpleicons.org/telegram/black/white"/></a>
<a href="https://vk.com/dumpl1ng_utka" target="blank"><img height="50" width="50" src="https://cdn.simpleicons.org/vk/black/white"/></a>
  
### Languages and tools
  <img height="50" width="50" src="https://cdn.simpleicons.org/unity/black/white"/>&nbsp;
  <img height="50" width="50" src="https://cdn.simpleicons.org/csharp/black/white"/>&nbsp;
  <img height="50" width="50" src="https://cdn.simpleicons.org/blender/black/white"/>&nbsp;
  <img height="50" width="50" src="https://cdn.simpleicons.org/adobephotoshop/black/white"/>&nbsp;
  <img height="50" width="50" src="https://cdn.simpleicons.org/visualstudio/black/white"/>&nbsp;
  
### My statistics

| <a href="https://github.com/anuraghazra/github-readme-stats"><img align="center" src="https://github-readme-stats.vercel.app/api?username=Dumpl1ngUtka&show_icons=true&theme=gotham" alt="Anurag's github stats" height="200"/></a> | <a href="https://github.com/anuraghazra/github-readme-stats"><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Dumpl1ngUtka&layout=compact&theme=gotham" height="200"/></a> |
| ------------- | ------------- |

### Most interesting projects

<table id= "Profile" align="center">
    <tr>
      <td align="center" valign="top" width="33%"><a href="https://github.com/Limofeus/Australitet" target="blank"><img src="https://github.com/Dumpl1ngUtka/Dumpl1ngUtka/blob/main/image/Australitet/0.png?raw=true"/></a></td>
      <td align="center" valign="top" width="33%"><a href="https://github.com/Limofeus/Australitet" target="blank"><img href="https://github.com/Limofeus/Australitet" src="https://github.com/Dumpl1ngUtka/Dumpl1ngUtka/blob/main/image/Australitet/1.png?raw=true"/></a></td>
      <td align="center" valign="top" width="33%"><a href="https://github.com/Limofeus/Australitet" target="blank"><img href="https://github.com/Limofeus/Australitet" src="https://github.com/Dumpl1ngUtka/Dumpl1ngUtka/blob/main/image/Australitet/2.png?raw=true"/></a></td>
    </tr>
</table>

### dsaad 

<div class="sliderbody">
<h4> Image-Slider</h4>
<section class="carousel" aria-label="Gallery">
  <ol class="carousel__viewport">
    <li id="carousel__slide1"
        tabindex="0"
        class="carousel__slide">
      <div class="carousel__snapper"> 
	      <section class="internal-embed" src="1.png"></section>
      </div>
        <a href="#carousel__slide4"
           class="carousel__prev">Go to last slide</a>
        <a href="#carousel__slide2"
           class="carousel__next">Go to next slide</a>
    </li>
    <li id="carousel__slide2"
        tabindex="0"
        class="carousel__slide">
      <div class="carousel__snapper">
            <section class="internal-embed" src="2.png"></section> </div>
      <a href="#carousel__slide1"
         class="carousel__prev">Go to previous slide</a>
      <a href="#carousel__slide3"
         class="carousel__next">Go to next slide</a>
    </li>
    <li id="carousel__slide3"
        tabindex="0"
        class="carousel__slide">
      <div class="carousel__snapper">
            <section class="internal-embed" src="3.png"></section></div>
      <a href="#carousel__slide2"
         class="carousel__prev">Go to previous slide</a>
      <a href="#carousel__slide4"
         class="carousel__next">Go to next slide</a>
    </li>
    <li id="carousel__slide4"
        tabindex="0"
        class="carousel__slide">
      <div class="carousel__snapper">
            <section class="internal-embed" src="4.jpeg"></section></div>
      <a href="#carousel__slide3"
         class="carousel__prev">Go to previous slide</a>
      <a href="#carousel__slide5"
         class="carousel__next">Go to first slide</a>
    </li>
    <li id="carousel__slide5"
        tabindex="0"
        class="carousel__slide">
      <div class="carousel__snapper">
            <section class="internal-embed" src="5.jpg"></section></div>
      <a href="#carousel__slide4"
         class="carousel__prev">Go to previous slide</a>
      <a href="#carousel__slide6"
         class="carousel__next">Go to first slide</a>
    </li>
  </ol>
</section>
</div>
