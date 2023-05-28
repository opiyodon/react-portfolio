This error occurs due to a node_modules folder doesn’t present in your project or package-lock.json file is corrupted.

To fix this error, follow the below steps.


First, delete the node_modules folder in your project (if you have one) using the below command.

=========rm -rf node_modules


Delete the package-lock.json file.

=========rm -rf package-lock.json


Install the project dependencies by running the following command.

=========npm install


Now, try to start the development server again using the npm start command it will work successfully without any errors.
Compiled successfully!