In Node js, Module is file containing set of resuable code and function that we can reusage in another file.


There are 3 type of module:
> Local
> Global
> 3 party


IIFE: Immediately Invoked function are the function we define that get immediately invoked.

In nodeJS, every local module file we create, NodeJS wrap then in a IIFE function.
that provide us some useful objects like exports, require, module, __dirname, __filename

(
function(exports, require, module, __dirname, __filename){
	//here our code resides
}
)()

because of this, we get require() to import any another module file/data.
also module.exports we get because of it.
