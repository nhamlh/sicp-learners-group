### 1.1

```
10
12
8
3
6
<nothing>
<nothing>
19
#f
4
16
6
16
```

### 1.2

`(/ (+ 5 4 (- 2 (- 3 (+ 6 (/ 4 5))))) (* 3 (- 6 2) (- 2 7)))`

### 1.3

```
(define (sum_of_larger a b c)
  (cond ((and (> a b) (> b c)) (+ (* a a) (* b b)))
          ((and (> a b) (< b c)) (+ (* a a) (* c c)))
          (else (+ (* b b) (* c c)))
  )
)
```

### 1.4

we have a compoud procedure, which has been given the name `a-plus-abs-b`.
it decides whether b is positive or nagative then apply the proper operator (plus or minus) to the calculation between a and b.

### 1.5

no solution yet
