Dynamic allocation
So far we have used variables, arrays with fixed size. But what happens if you do 
not know the size of the array you have to declare and / or if this size depends on 
another variable?
Note: remember, you can declare arrays only with a constant.
type variable[constant]; /* works */
int n;
n = 10;
type variable[n]; /* does not work */
