# assignment2-gottipati
# sai sriya gottipati #
### domino's ###
domino's pizza is **affordable** and there will also be many **restaurants** around it with various **cuisines**.it has wide varities of **pizzas,sandwiches,shakes and desserts**. even there is a park around the corner which is best for kids and **picnic**.
***
## NEAREST AIRPORT ##
airport that is closest to domino's is **Rajiv gandhi international airport**
from airport u can directly book a cab then go on nehru outer ring 
next take the PV narsimhaRAO FLYOVER
after at the end of flyover take the u-turn
stay towards left lane
go straight to reach tasty **Domino's**

## FOOD ITEMS ##
* pani puri
* burgers
* biryani
* haleem
* dosa
* crispy cream donuts
***
### Link of AboutMe ###
here is the link to know more about me [about me](AboutMe.md)

***

# Sports #

I love playing sports like badminton,tennis and basketball and love watching cricket matches. Playing sports helps in maintaining teamwork, a self-cresponsibility, and self-discipline .

-------------------------------------------
|name of sports | location | cost    |
|---------------|----------|---------|
|batminton      |court     |  10$    |
|golf           |field     |  50$    |
|tennis         |court     |  30$    | 
| football      | ground   |  60$    |
--------------------------------------

------------------------------------------------------------

# QUOTES

>Strength doesnot come from winning.Your struggles develop your strength when you go through hardship and doesnot surrender. that is your strength.
*- Mahatma gandhi*

>Your time is limited so don't waste by living someone elses life. 
*- steve jobs*

------------------------------------------------------------
# Geometry  Elementary/Polygons  

In geometry, a polygon is a plane figure that is described by a finite number of straight line segments connected to form a closed polygonal chain (or polygonal circuit). The bounded plane region, the bounding circuit, or the two together, may be called a polygon.

more information about geometry polygons:Some polygons of different kinds: open (excluding its boundary), boundary only (excluding interior), closed (including both boundary and interior), and self-intersecting.
 
 click the link for more information: <https://en.wikipedia.org/wiki/Polygon>

 ```
# circle-line intersection

 double r, a, b, c; // given as input
double x0 = -a*c/(a*a+b*b), y0 = -b*c/(a*a+b*b);
if (c*c > r*r*(a*a+b*b)+EPS)
    puts ("no points");
else if (abs (c*c - r*r*(a*a+b*b)) < EPS) {
    puts ("1 point");
    cout << x0 << ' ' << y0 << '\n';
}
else {
    double d = r*r - c*c/(a*a+b*b);
    double mult = sqrt (d / (a*a+b*b));
    double ax, ay, bx, by;
    ax = x0 + b * mult;
    bx = x0 - b * mult;
    ay = y0 - a * mult;
    by = y0 + a * mult;
    puts ("2 points");
    cout << ax << ' ' << ay << '\n' << bx << ' ' << by << '\n';
}
```

more details:https://cp-algorithms.com/geometry/circle-line-intersection.html