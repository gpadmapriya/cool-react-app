## Infrastructure as Code

  - Authors: Trevor Dobson, Jack Daniel Kinne, Brandon Hurrington, Padmapriya Ganapathi, Steven Grant

### Feature Tasks
  - Debug series of cloudformation templates

### Setup 
  - Create a basic React app in your own directory.
  - Ensure that you can run your React app locally.
  - Connect your local repo to a new GitHub repo, and push your master branch.
  - Install the @code-fellows/aws-tools from NPM
  - Create a .env file with GitHub access keys
  - Run aws-react-yaml in the folder where your react app is to generate aws.yml 

### Feature task
  - On the AWS console, create a new CloudFormation stack named coolReactApp
  - Upload the cloud formation template created during setup
  - Deploy that CloudFormation stack.
  - Visit cloudfront, and view your React App via the public URL given to you.

### Bug fixes
- Stack creation Error - Cannot render the template because of an error.: YAMLException: duplicated mapping key 
   - The s3 bucket name had dashes in it. Removed '-' and the stack was created

- Unique names for all different outpit artifatcs
![Output Artifact Bundle](https://github.com/gpadmapriya/cool-react-app/blob/master/OutputArtifacts.png)

### Credits and Contributions
- Jack Daniel Kinne
- Brandon Hurrington
- Padma Ganapathi
- Trevor Dobson
- Steven Grant

