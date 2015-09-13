## General Steps with CAD packages

everything is very systematic, there is an order of operations generally which are needed except in edge cases.

## Majority of the time:

1. Start from a sketch
2. Do a Part
3. Do an Assembly

## Sketches

a. each sketch starts on a plane (choose top bottom or right plane)
b. depending on the plane chosen, the way the part "faces" is set.
c. draw a sketch, and then manipulate that sketch -- like **extruding**


## Exercise 1:

1. create a new part
2. select a plane
3. draw a sketch
4. control dimensions for the sketch
5. Operations: this time do an extrude

## Extrude details

1. Extrude
2. choose to surface, and extrude subtract (extrude cut in Solidworks)
3. finally do a fillet selecting the edges.

 
## Exercise 2: try different operations in place of step #5

* revolve -- choose an axis and revolve sketch around that axis.
* sweep -- two sketches and a path, and will sweep across that path
* loft -- two different sketches, and will sweep and merge from one to second shape
* shell -- make all walls a certain thickness, great for complex geometries and 3d printing
* fillets -- normally last step

**when possible don't pick faces as new sketch surfaces of parts**


## Exercise 3: Create Assembly

1. add parts to the assembly
2. create mates

## Types of mates:
* coincident -- two faces come togehter
* concentric -- like when a pin goes into a hole
* parallel -- when two things need to be parallel
* tangent -- when a circular thing is tangent to a plane
* width mate -- a block and a box and want them to be perfectly centered
* advanced mate -- can do additional mates like angles
* Mechanical mates
  * rack and pinions
  * screw
  * pins

## Mindset -- Homework

Look around and think about how to make things in this path sketches.
