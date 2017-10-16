# AngularMaterialSkeleton
## A skeleton webapp using Angular and Materialize

### Versions
* AngularJS 1.4.2
* Materialize 0.100.2
* jQuery 3.2.1

### Configuration instructions
***
1. Clone repo
2. Run **_npm install_** to install the dependent node modules
3. Replace the name **_skeleton_** with the name of your app in the following places:
   
   | File               | Location      | Line  |
   | ------------------ | ------------- | ----- |
   | index.html         | _root_        | 2     |
   | main.module.js     | js/config     | 5     |
   | main.route.js      | js/config     | 5     |
   | main.controller.js | js/app        | 5     |

4. Run **_npm start_** to have live server serve this app on port 5555
5. Add any new paths created to **_main.route.js_**
6. Add all new controllers to the end of the scripts in the **_index.html_** file