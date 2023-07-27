# Resume :page_with_curl:

![img](https://github.com/pravinKumar91/react-resume/blob/main/public/images/img.jpg?raw=true)

# Description
This project is realted to my bio in resume format.

![img](https://github.com/pravinKumar91/react-resume/blob/main/public/images/img2.jpg?raw=true)

# Run Project
### 1. Clone the project

### 2. Intall the node modules
```shell
npm install
```

### 3. Run the project
```shell
npm start
```

### 4. Build
```shell
npm run build
```



# To make project live on Github pages:

### Step 1: 
Add homepage url in package.json. Mentioned the project name copied from the github only.
E.g.   
"homepage": "https://pravinKumar91.github.io/resume",

### Step 2:
Add below statements in package.json
  "scripts": {
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build"
}

### Step 3:
```shell
npm install --save gh-pages --legacy-peer-deps
npm run deploy
```

### Step 4: 
Push the changes on github

### Step 5:
Select branch gh-pages so that deployment will be done from that branch.
Your Repository -> Settings -> Pages -> Build and deployment -> Branch

### Step 6: 
Access the URL
https://username.github.io/repository_name

