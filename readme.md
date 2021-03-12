#step 1 distribute an stencil package using the output target

outputTargets: [
{
type: 'dist',
esmLoaderPath: '../loader',
},

#step 2 copy the folder named after the project in the dist folder to your electron project

#step 3 add a script of type module to the index.html
