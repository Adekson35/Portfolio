<!--Section 1: Introduce your self-->
## ABOUT ME

Hi, i'm Samuel Adekunle! A detail-oriented and analytical Data Analyst with a strong background in collecting, interpreting, and visualizing data to drive strategic business decisions. Skilled in data modeling, and visualization tools to uncover insights, improve processes, and optimize performance. Proficient in Excel, and BI tools like Tableau and Power BI.


<!--Mention your top/relevant skills here - core and soft skills-->
## Skills

*As a data analyst I transform raw data into meaningful insights by utilizing different analytical methods and tools, to assist organizations in making impactful decisions.*

**- ✅ Data Wrangling.**

**- ✅ Data Visualization.** 

**- ✅ Data Modelling .**

<!--Section 2: List 3-4 key projects-->

## MY PROJECTS 

*A glimpse of some of the projects I've been working on.*

### Project 1

**Analyse attrriton in healthcare center and also determine the factor that influence attrition rate .**

![image1]({68300354-8FAA-4885-BA27-2FEAAC6E3888}.png.jpg)

![image2]({B047F575-6B16-4302-921F-9D82EED22CED}.png.jpg)

![image3]({B7C1CEE6-DB4A-4ACD-A405-DB9296ED1D39}.png.jpg)


<p align="center">
  <img src="{68300354-8FAA-4885-BA27-2FEAAC6E3888}.png.jpg" width="300">
  <img src="{B047F575-6B16-4302-921F-9D82EED22CED}.png.jpg" width="200">
  <img src="{B7C1CEE6-DB4A-4ACD-A405-DB9296ED1D39}.png.jpg" width="200">
</p>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Slider</title>
    <style>
        .slider {
            width: 600px;
            height: 400px;
            position: relative;
            overflow: hidden;
        }
        .slides {
            display: flex;
            width: 250%;
            animation: slide 30s infinite;
        }
        .slides img {
            width: 44%;
        }
        @keyframes slide {
            0% { transform: translateX(0); }
            33% { transform: translateX(-100%); }
            66% { transform: translateX(-200%); }
            100% { transform: translateX(0); }
        }
    </style>
</head>
<body>
    <div class="slider">
        <div class="slides">
            <img src="{68300354-8FAA-4885-BA27-2FEAAC6E3888}.png.jpg" alt="Slide 1">
            <img src="{B047F575-6B16-4302-921F-9D82EED22CED}.png.jpg" alt="Slide 2">
            <img src="{B047F575-6B16-4302-921F-9D82EED22CED}.png.jpg" alt="Slide 3">
        </div>
    </div>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Slideshow</title>
    <style>
        body { text-align: center; font-family: Arial, sans-serif; }
        .slideshow-container { position: relative; max-width: 600px; margin: auto; }
        img { width: 100%; height: auto; display: none; }
        .active { display: block; }
        .prev, .next {
            position: absolute;
            top: 50%;
            transform: translateY(-50%);
            font-size: 24px;
            padding: 10px;
            background: rgba(0,0,0,0.5);
            color: white;
            cursor: pointer;
        }
        .prev { left: 0; }
        .next { right: 0; }
    </style>
</head>
<body>

<h2>Simple Image Slideshow</h2>

<div class="slideshow-container">
    <img src="{68300354-8FAA-4885-BA27-2FEAAC6E3888}.png.jpg" class="active">
    <img src="{B047F575-6B16-4302-921F-9D82EED22CED}.png.jpg">
    <img src="{B047F575-6B16-4302-921F-9D82EED22CED}.png.jpg">
    
    <div class="prev" onclick="changeSlide(-1)">&#10094;</div>
    <div class="next" onclick="changeSlide(1)">&#10095;</div>
</div>

<script>
    let slideIndex = 0;
    const slides = document.querySelectorAll(".slideshow-container img");

    function showSlide(index) {
        slides.forEach(slide => slide.classList.remove("active"));
        slides[index].classList.add("active");
    }

    function changeSlide(direction) {
        slideIndex += direction;
        if (slideIndex < 0) slideIndex = slides.length - 1;
        if (slideIndex >= slides.length) slideIndex = 0;
        showSlide(slideIndex);
    }

    setInterval(() => changeSlide(1), 3000); // Auto-slide every 3 seconds
</script>

</body>
</html>



What are the key drivers of employee attrition?
[Read More](project presentation healthcare.pdf)




### Project 2

**Coffee shop sales analysis .**

![image](Annotation 2025-02-16 194716.jpg)

Analyze sales Trends and product revenue
[Read More](coffee shop presentation.pdf)




## CONTACT DETAILS

*Let’s connect and see how we can make a difference together!*
<table>
  <tbody>
    <tr>
      <td>📧</td>
      <td><a href="mailto:adekunlesamuel701@gmail.com">adekunlesamuel701@gmail.com</a></td>
    </tr>
    <tr>
      <td>📞</td>
      <td>(234) 9037074885</td>
    </tr>
    <tr>
      <td>📍</td>
      <td>Lagos, Nigeria</td>
    </tr>
    <tr>
      <td>⬇️</td>
      <td><a href="https:SAMMY DATA RESUME.pdf">Download my CV</a></td>
    </tr>
    <tr>
      <td>🌐</td>
      <td><a href="https://www.linkedin.com/in/samuel">LinkedIn</a></td>
    </tr>
     </tbody>
</table>

   





