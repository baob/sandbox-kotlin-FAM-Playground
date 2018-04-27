# Functors, Applicatives and Monads Playground

This is a playground repo for the translated article [Kotlin Functors, Applicatives, And Monads in Pictures.](https://medium.com/@aballano/kotlin-functors-applicatives-and-monads-in-pictures-part-1-3-c47a1b1ce251)

Forked from repo [aballano/FAM-Playground](http://github.com/aballano/FAM-Playground)

To compile

    $ kotlinc  src/*.kt -cp lib -d classes
     
To run

    $ cd classes     
    $ kotlin FunctorsPlaygroundKt 

## Part 1 Summary - Functors

Functor is a value with a wrapper or context.
 
map (kotlin) takes a Functor, unwraps the value, applies the method, and re-wraps

w[v].map(f)  (becomes)  w[f(v)]




