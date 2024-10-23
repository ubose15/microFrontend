# microFrontend
 The idea is to integrate aap2 into aap1 using run time integration with the help of ModuleFederation Plugin from webpack 5 module bundler.

 # app 1
 Contains a div with heading as Application 1 running on port 3000

 # app 2
 Contains a div with heading as Application 2 running on port 3001

 # upon adding the Module Federation Plugin and adding the App.js of app2 into app1 we get an integrated UI on the runtime

 # Please note without Module Federation this can be acheived by adding the hashed chuck file or the (URL of main.js) inside a script tag ,but any changes further done on the remote app would change the hash and thus need a constate update of URI in host app.
