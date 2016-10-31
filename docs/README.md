
> hexlet-points@0.0.6 documentation /Users/mokevnin/projects/js-points
> documentation "build" "src/index.js" "-f" "md"

# makePoint

Make a point

**Parameters**

-   `x` **Any** 
-   `y` **Any** 

**Examples**

```javascript
const point = makePoint(4, 5);
```

# getX

Get X

**Parameters**

-   `point` **Point** 

**Examples**

```javascript
const point = makePoint(4, 5);
getX(point); // 4
```

# getY

Get Y

**Parameters**

-   `point` **Point** 

**Examples**

```javascript
const point = makePoint(8, -2);
getY(point); // -2
```

# toString

Convert point to string

**Parameters**

-   `point` **Point** 

**Examples**

```javascript
const point = makePoint(0, 10);
toString(point); // (0, 10)
```

# quadrant

Determine quadrant for given point

**Parameters**

-   `point` **Point** 

**Examples**

```javascript
quadrant(makePoint(5, 0)); // undefined
quadrant(makePoint(1, 5)); // 1
quadrant(makePoint(-3, 10)); // 2
```
