Implementation of divide and conquer algorithm for closest pair problem with O(nlogn) complexity in python. <https://en.wikipedia.org/wiki/Closest_pair_of_points_problem>

Input is a list of tuples. Each tuple consisting of a location name, latitude coordinate and longitude coordinate respectively. Ouputs the two closest coordinates and their distance apart. 

eg.
```
cities_list = [('a',1,45),('b',-2,12),('c',5,-7),('d',65,12),('e',55,43),('f',25,-100),('g',-5,-179),('h',-5,9)];
closest_pair(cities_list)
```
Output:
``` 
Closest locations: h and b, 471.3km apart.
```
