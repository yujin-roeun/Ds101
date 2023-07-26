# Ds101
summer-mini course

# variables
# "boxes" that stores values
engsci_adj <- -12
x <- 97 + engsci_adj
cat(x)
x

# ax^2+bx+c=0
# compute the discriminant b**2-4*a*c, store as a variable
# store True in no_roots if ax^2+bx+c=0 has no roots
a <- 1
b <- -2
c <- 1
disc <- b**2 - 4*a*c
no_roots <- disc < 0
cat(no_roots)

a <- 1
b <- 2
c <- 10
disc <- b**2-4*a*c
no_roots <- disc < 0
cat(no_roots)

#conditional
# want to do different things depending on the value of some prior computation

# want to print the absolute value of n
n <- -25
if(n>=0){
  cat(n)
}else{
  cat(-n)
}

exam_grade <- 96
if(exam_grade>=95){
  cat("horay!!")
}else if(exam_grade>=94){
  cat("ok")
}else{
  cat("Alast!")
}

#functions
square <- function(x){
  x**2
}

#square(x) = x**2
square(-2)

my_abs <- function(x){
  if(x>0)(
    x
  )else(
    -x
  )
}

z <- 53
cat(my_abs(z))
