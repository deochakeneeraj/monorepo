Create a monorepo

Step 1 :- npm init in base package
Step 2 :- npm init fo the module in packages folder
Step 3 :- add global dependencies in the external package.json
Step 4 :- npx lerna init :- initialze lerna
Step 5:- npx lerna clean :- moves node-modules folder from all internal packages to external base monorepo package
Step 6 :- npx lerna bootstrap --hoist checks all the dependencies mentioned in internal package.json and add them in external node modules folder (root level)
