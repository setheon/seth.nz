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

  var text = "<b>Hey there 👋 I'm Seth, a " + yearsSince + "-year-old student based in Wellington, New Zealand.</b> I am currently studying at Massey University doing a Bachelor of Screen Arts with a Major in Film Production, where I am honing my skills and passion for the visual arts/film. <br> <br> <b> Immerse yourself in my creative portfolio </b> and explore the various projects I have undertaken. Whether you are seeking a collaborator for your next creative endeavor or simply appreciate art in its many forms, I hope that my work resonates with you and inspires you in some way. <br> <br> <b> This website 'seth.nz' serves as a digital sanctuary for my creative work. </b> Here, you will find a carefully curated collection of my graphic design and photography projects, showcasing my ability to blend aesthetics with purpose, while conveying unique narratives. As my journey progresses, I am excited to expand my creative horizons into the realm of videography, where I aim to craft compelling visual stories that resonate with audiences.";

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
      margin-top: 0; /* Reset margin for desktop view */
      max-width: 300px;
    }
  }
</style>

<br>

<div align="center">
    <h3>like my work? donate below.</h3>
</div>


<div class="donate-button-container">
<script 
type="text/javascript" src="https://cdnjs.buymeacoffee.com/1.0.0/button.prod.min.js" data-name="bmc-button" data-slug="setheon" data-color="#ffffff" data-emoji="" data-font="Cookie" data-text="Buy me a coffee" data-outline-color="#000000" data-font-color="#000000" data-coffee-color="#FFDD00" >
</script>
</div>

