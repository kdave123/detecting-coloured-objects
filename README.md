# detecting-coloured-objects
Detection of objects based on colors using inRange() funtions ( Red, Green, Blue)]

1. Set Color Range for hsv model

hsv model allows us to set exact range of colors to detect (color,lightness,darkness)


2. Detect specifed color inRange and mask it

3. Apply Basic Morphological operations erode, dilate to remove noise and widen mask

4. Detect the contour, Draw minimum Enclosing Circle based on color detected

5. Use deque to track path of object, draw tracer

6. Use moments of contours detected and find center of mass, track it using deque

7. loop activites( tracking, drawing specific colored minimum enclosing circle)  for all detected Red, green, blue objects seperately.
