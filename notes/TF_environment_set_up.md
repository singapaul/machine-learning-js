# Setting up TF in browser and in node js 

- in the browser helps us protect the users privacy by not sending data to the server. 
- Integrate into existing application backends
- Good cultural fit for start ups.
- Not just backend: command line scripts too! 

## In the browser

1. Use a package manager (YARM/NPM)
2. Use a script tag -> access via the script tag

There are two types of back end for the browser. We can run "tf.getBackend()" to find out. It will be either;
1. "webgl"
2. "cpu"

## Running on node JS

1. ensure you have node.js installed 
2. make directory 
3. initialisae directory with node -> npm init, use all defaults.
4. in the terminal within the project run 
```
npm install @tensorflow/tfjs-node
```
5. You should see the tensorflow dependancy in the package.json file.
