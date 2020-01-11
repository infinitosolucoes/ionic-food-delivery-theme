# ionic-food-delivery-theme

A Documentation for [Ionic Food Theme](https://mythemebox.com/template/ionic-food-delivery-theme/)

### Prerequisites

Before starting the setup make sure, you have correct versions of tools. we shared our development environment for this theme

```
node -v
12.8.1

npm -v
6.11.3

ionic -v
5.4.4

cordova -v
9.0.0

java -version
1.8.0_201
```
### Installation

Once you have the right tools, we can start our setup.

1.  Download your purchased code from your account.
2.  Extract zip file to the decided folder
3.  open your command prompt/terminal & change your working directory to the extracted folder
4.  Then follow these commands

```
cd ionfoodtheme
npm install
ionic serve
```
These commands will automatically install all the required dependencies.  `ionic serve`  execute/run your app in the browser.

```
ionic cordova platform add android
ionic cordova platform add ios
ionic cordova run android
ionic cordova run ios
```

Note: ios build requires mac

### Customization

**How to update content?**

-   Navigate to  `src/assets/data`
-   Update respective JSON files to update the content

**Can I host this .json with the remote server?**

-   Yes, you can copy the entire  `src/assets/`  => data folder to anywhere you want
-   Once you hosted, update the server SERVER_URL =>  `src/environments/environement.prod.ts`

**How to change colors?**

-   Update your variable color:  `src/theme/variable.scss`
-   Update css code  `src/global.scss`

**How to change Images**

-   Navigate to  `src/assets/images/`  folder & replace with same name & extension
