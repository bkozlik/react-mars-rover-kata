### react-mars-rover-kata

Toy implementation for the Mars Rover programming challenge adapted to use react.js for input.

### Objectives:

Develop an api that moves a rover around on a grid.
You are given the initial starting point (x,y) of a rover and the direction (N,S,E,W) it is facing.
The rover receives a character array of commands.
Implement commands that move the rover forward/backward (f,b).
Implement commands that turn the rover left/right (l,r).
Implement wrapping from one edge of the grid to another. (planets are spheres after all)
Implement obstacle detection before each move to a new square. If a given sequence of commands encounters an obstacle, the rover moves up to the last possible point and reports the obstacle.
Example: The rover is on a 100×100 grid at location (0, 0) and facing NORTH. The rover is given the commands “ffrff” and should end up at (2, 2)
Tips: use multiple classes and TDD

Source:
https://anirudhbhargava7.wordpress.com/2014/04/01/mars-rover-kata/


### Executing without docker
```
cd /opt/
git clone https://github.com/bkozlik/react-mars-rover-kata
cd /opt/react-mars-rover-kata
npm install
npm start
```

Alternately, generate static files and copy to a web server or S3 bucket for hosting
```
npm run build
copy build/* /path/to/your/webserver/www
```


### Usage
Navigate to the URL where the code is hosted and play around.


