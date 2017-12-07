![alt text](https://github.com/UWSEDS-aut17/uwseds-group-nw-climate-crew/blob/Katie/futurefish/resources/images/logo_3.png?style=centerme) 

<p align="center">
  <img src="https://github.com/UWSEDS-aut17/uwseds-group-nw-climate-crew/blob/Katie/futurefish/resources/images/logo_3.png">
</p>

## Problem:
Climate change will have large affects on water resources all over the world. For this project we want to investigate how these changes will affect salmon in the Pacific Northwest. This question is often complicated by the fact that the Columbia River is highly regulated with dams which can have detrimental impacts on fish habitat. We will envision a world without any human infrastructure impacts to pose the question: __What impact will climate change _alone_ having on viable salmon habitat in the Pacific Northwest?__

To answer this question we worked with two datasets which project well into the 21st century alson with a simple model to estimate salmon viability. The two datasets are:
1. [Projections of streamflow](http://hydro.washington.edu/CRCC/) within the Columbia River Basin
2. [Temperature projections](https://www.fs.fed.us/rm/boise/AWAE/projects/NorWeST.html) for the same area.

### How can this tool be used?
We anticipate this visualization tool being useful for the following applications: 
1. Educational
...This tool can be used in a classroom setting and provide an interactive way for students to engage with where salmon live now and in the future.
2. Recreational
...Recreational users can examine this interacive map to see how their fishing spots may change in the future.
3. Environmental  

Environmental groups can use this tool to show the impacts of climate change on salmon in a visual and interactive way. 


## How to run FutureFish: 
1. In a terminal window, navigate the the location you would like to copy the files. 

2. Clone the git repository in that location by typing the following in a terminal window: 
~~~~
git clone https://github.com/UWSEDS-aut17/uwseds-group-nw-climate-crew.git
~~~~

3. In that directory initiate the setup by typing: 
~~~~
python setup.py develop --user
~~~~

4. Then you can run the visualization from the uwseds-group-nw-climate-crew directory by typing the following in the terminal. 
~~~~
python ./scripts/futurefish_dash.py
~~~~

5. Then copy the following url into a browser to navigate to the site. 
~~~~
http://127.0.0.1:5000/ 
~~~~

### The basic idea of what we did: 
Modelling etc. 



![alt text](http://hydro.washington.edu/CRCC/assets/img/CRBaerial.jpg)
