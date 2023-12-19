---
images:
# - /author.jpg
title: about
url: about
hideTitle: true
hideExif: true
hideDate: true
---

<style>

/* Donate */
 .donate-button-container {
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .donate-button  {
    display: flex;
    align-items: center;
    padding: 10px;
    border-radius: 10px;
    background: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);
    background-size: 400% 400%;
    animation: gradient 15s ease infinite;
    width: 250px;
    transition: background-color 0.3s, filter 0.3s, border-color 0.3s;
    border: 2px solid transparent; /* Add transparent border */
    box-sizing: border-box; /* Include border in dimensions */
  }

  .donate-button:hover {
    background: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);
    animation: gradient 15s ease infinite;
    background-size: 400% 400%;
    filter: brightness(140%); /* Increase brightness by 10% */
  }

  .donate-button:hover .text {
    color: yellow;
  }

  .donate-button .icon {
    margin-right: 10px;
  }

  .donate-button .text {
    text-align: center;
    flex-grow: 1;
    transition: color 0.3s;
  }
  @keyframes gradient {
    0% {
      background-position: 0% 50%;
    }
    50% {
      background-position: 100% 50%;
    }
    100% {
      background-position: 0% 50%;
    }
  }

.right {
  float:right;
  max-width: 40%;
  margin-left: 5px
}

.left {
  float:left;
  max-width: 40%;
  margin-right: 20px
}

.imageURL {
  max-width: 100%;
  height: auto;
}


</style>

<div align="center">
    <h1>about me.</h1>
</div>

<script>
  // Calculate the number of years since a particular date
  var startDate = new Date("2002-03-14");
  var currentDate = new Date();
  var yearsSince = currentDate.getFullYear() - startDate.getFullYear();

  var imageUrl = "/images/author.png"; // Replace with the actual path to your image

  var text = "<b>Hey there 👋, I'm Seth, a " + yearsSince + "-year-old student based in Wellington, New Zealand.</b> I am currently studying at Massey University, pursuing a Bachelor of Screen Arts with a major in Film Production, where I am honing my skills and passion for the visual arts and film. <br> <br> <b>✨ I originally hail from Tauranga here in New Zealand,</b> but I now mostly reside in the bustling artistic capital city of New Zealand, <b>Wellington!</b> I initially moved to the city for work but soon found my heart being drawn to heading to University to pursue my creative dreams in the Film Industry. <br><br> 🏔 <b> In my free time, I'm often found going on hikes or small city adventures with my camera. </b> I love to capture the world around me, and I'm typically not found without my camera near. When I'm not taking photos or hiking, I typically spend my time dabbling in various forms of art, from sketching to digital art or creating music.";

  //
  /* b>In late 2023, I started to plan my first major Film,</b> a small sci-fi short called <b>Sol.</b> I quickly gathered a large crew & secured the means to start pre-production. The film will commence shooting in March 2024 & will continute for several months. <b>Sol</b> is a very ambitious project, with a large crew of over 25 people now. A team of 6 VFX artists, 3 actors, 2 stunt actors & a large crew. <br><br>
  [stay tuned for more on Sol] */

  // Create the HTML string with both text and image
  var htmlString = "<div id='content-container'><p>" + text + "</p><img id='author-image' src='" + imageUrl + "' alt=''></div>";

  // Display the HTML string
  document.write(htmlString);
</script>

<style>
  #content-container {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  #author-image {
    max-width: 100%;
    width: 300px;
    margin-top: 20px; /* Add some space between text and image */
  }

  @media (min-width: 768px) {
    /* Desktop styles */
    #content-container {
      flex-direction: row;
      justify-content: space-between;
    }

    #author-image {
      max-width: 100%;
      width: 300px;
      margin-right: 50px; /* Increase the space between text and image */
    }
}
</style>

<div align="center">
    <h2>about my portfolio site.</h2>
</div>

<b>Currently, this website '<i>seth.nz</i>' serves as a digital sanctuary and portfolio for all my best creative work.</b> 

<br>

<b>Here, you will find a carefully curated collection of my photography and my other creative projects.</b> As my creative journey progresses, I am excited to expand my creative horizons into the realm of filmmaking, where I aim to craft compelling visual stories that resonate with audiences.<br>


<br>

<div align="center">
    <h3>like my work? donate below.</h3>
</div>


<div class="donate-button-container">
<script 
type="text/javascript" src="https://cdnjs.buymeacoffee.com/1.0.0/button.prod.min.js" data-name="bmc-button" data-slug="setheon" data-color="#ffffff" data-emoji="" data-font="Cookie" data-text="Buy me a coffee" data-outline-color="#000000" data-font-color="#000000" data-coffee-color="#FFDD00" >
</script>
</div>