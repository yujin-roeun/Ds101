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
