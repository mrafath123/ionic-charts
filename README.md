# 📊 Ionic Charts App

This is a **standalone Ionic Angular app** that demonstrates various types of charts using the powerful `ngx-charts` library.

## 🚀 Features

- ✅ Pie Chart  
- ✅ Line Chart  
- ✅ Grouped Bar Chart  
- ✅ Vertical Bar Chart  
- ✅ Horizontal Bar Chart  

## 🧰 Technologies Used

- [Ionic Framework](https://ionicframework.com/) (Angular Standalone Architecture)
- [ngx-charts](https://swimlane.gitbook.io/ngx-charts/)
- [D3.js](https://d3js.org/) (required by ngx-charts)
- SCSS / CSS for styling

---

## 📦 Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/your-username/ionic-charts-app.git
cd ionic-charts-app
npm i @swimlane/ngx-charts --save
```

## to build from scratch
```
ionic start chart blank --type=angular
npm i @swimlane/ngx-charts --save
ionic generate component components/pie-chart
ionic generate component components/grouped-vertical-bar-chart
ionic generate component components/horizontal-bar-chart
ionic generate component components/vertical-bar-chart
ionic generate component components/line-chart
```
**write the code in the followings components and home page and then**
```
ionic serve #two run the app
ionic cap add android #to add android
ionic cap build android #to sync and build android
```





