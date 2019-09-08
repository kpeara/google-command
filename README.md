<img src="/google.png" width="150">

# Google from the command line!
Something small I made when I got bored

***Make sure you have selenium webdriver and the proper drivers for your browser.***
which can be found [here](https://www.seleniumhq.org)

Move google to your **/usr/local/bin**  and start using it in your next session!

About:
Busy coding want to see what time is sunset? Or what the grocery shop is closing? Or what the weather is like and will be later? Or what the score is for the game that you're missing because your busy with work? :(

Well you could google it....but that could also mean you might procrastinate on something else like Youtube, Facebook etc.
So why not set a timelimit for how long you want that page open? With google commandline you can do just that!

```
COMMANDS:

google "weather today"		opens chrome browser and google searches "weather today"

google -s "weather today"	opens safari and google searches "weather today"

google -f "weather today"	opens firefox and google searches "weather today"

google "weather today" -t 3	opens chrome and google searches "weather today" with a time limit 3 seconds

google -st 3 "weather today"	opens safari and google searches "Weather today with a time limit of 3 seconds

...

```

What I learned:
- How to use selenium webdriver in python (have used it before in other langauges)
- Automation and the idea of controling a browser via script
- How to use the argparse library in python
- How to create command line utilities

Purpose of project:
- I just wanted to create a commandline utility
- This was actually made to get more familiar with the  **clockify-command** utility that I am developing to make my workflow better
