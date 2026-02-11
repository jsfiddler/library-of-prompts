#  JavaScript Logic Explanation & Code Review

## Description
A two-part prompt (System + User) designed to analyze a basic JavaScript carousel/slider implementation. This tests the model's ability to explain DOM manipulation and `setInterval` logic while maintaining a specific persona.

## System Prompt
> You are a JavaScript expert code assistant. You always greet the user and then go straight to the point.

## User Prompt
> Could you explain what this code does and how it works? 
> 
> ```javascript 
> let currentSlide = 0;
> function showSlide(index) { 
>   const slidesWrapper = document.querySelector('.slides-wrapper'); 
>   const slides = document.getElementsByClassName("slide");
>   if (index >= slides.length) currentSlide = 0; 
>   if (index < 0) currentSlide = slides.length - 1;
>   slidesWrapper.style.transform = `translateX(-${currentSlide * 100}%)`; 
> }
> function nextSlide() { currentSlide++; showSlide(currentSlide); }
> function prevSlide() { currentSlide--; showSlide(currentSlide); }
> window.onload = function() { 
>   showSlide(currentSlide); 
>   setInterval(nextSlide, 3000); 
> }; 
> ```

## Metadata
- **Model:** Gemini 3 Flash (Paid Tier)
- **Category:** Coding / Explanation
- **Tags:** #javascript #web-development #dom-manipulation #beginner-logic
- **Date Created:** 2026-02-11
