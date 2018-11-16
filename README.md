# louisvilleCommunities

Description

This is a combination of the Kentucky and Louisville Tourism websites with a focus on the neighborhoods West of Ninth Street.

Custom CSS Classes

The class(es) I created are:

1. .card:hover p {
     display: block;
     box-shadow: 0 20px 5px -5px black;
   }
   .. displays neighborhood paragraph on hover

2. .imgCard img:hover {
     transform: scale(1.5);
   }
   .. creates a zoom effect on hover of neighborhood share moments images

3. .form-control:focus {
   border-color: #E31B1E;
   outline: 0;
   box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075), 0 0 8px rgba(227, 27, 30, 0.6);
   } 
   .. changes input field border to red when clicked

Custom JavaScript Functions

The javascript functions I created are:

1. $(window).scroll(function(){
	 $('nav').toggleClass('scrolled', $(this).scrollTop() > 700);
   });
   .. used to change background color of navbar to red when scroll is greater than 700
