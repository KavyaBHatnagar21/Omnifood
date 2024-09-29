# Learnings through Omnifood

- create a seperate folder for CSS too as we do for images

- keep font size of html in % as 62.5% to work easily with rems
  here, 1rem = 16px
  if we keep font-size as 10px then 10px/16px = 0.625rem = 62.5%

- generate shades & tints of the main color from maketintsandshades.com

- Trick: If border of a button/anchor tag upon hovering shakes the components around it then we need to use inset property provided by the box-shadow:- box-shadow: inset 0 0 0 3px #fff; this means no vertically, no horizontally, no blur but 3px white border color from inside.
