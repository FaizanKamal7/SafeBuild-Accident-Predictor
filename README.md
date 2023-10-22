The project "SafeBuild: Accident Predictor" uses a Python program to spot dangerous construction sites before bad things happen. We use a math formula to figure out which sites are risky based on past accidents and other details like:

How many active work permits the site has.
Whether it's a new building or not.
If the site has special permits for things like sheds or fences.
How tall the building is.
If there were any accidents at the site before 2017.
The program looks at these factors and gives each site a risk score from 1 to 8. Here's how we break it down:

Number of permits: Fewer than 5 gets a 1, 5-7 gets a 2, 8-10 gets a 3, and 11 or more gets a 4.
New building: Yes scores 1, No scores 0.
Special permits for sheds, scaffolds, or fences: Yes scores 1, No scores 0.
Building taller than 10 floors: Yes scores 1, No scores 0.
Accidents before 2017: Yes scores 1, No scores 0.
We run the program every day to keep the scores up-to-date. The results are shown on an easy-to-read map.
