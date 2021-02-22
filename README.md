# Infrastructure

This is a collection of cloudformation templates that define our AWS resources

## Setting up a cloudformation stack

1. Create the files for the stack, along with a variables.json file that holds all of the parameters for the deployment
2. Make sure there is a deployment process set up in octopus and that all variables have been set
3. Create a release, this will trigger the octopus deployment
