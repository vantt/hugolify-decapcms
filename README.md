![Twitter banner](https://user-images.githubusercontent.com/4457294/208064328-5bbf40e4-5520-41f4-8024-30c898c1a0e8.png)

# Hugolify template

Is a Github template for build easily a fast, accessible friendly and low carbon website!

## Installation

### ****1. Installing Hugo

Hugo is a fast and flexible static site generator. Follow the steps below to install it on your operating system.

#### **1.1. macOS**

1. **Using Homebrew:**
   - Open Terminal and run:
     ```bash
     brew install hugo
     ```

2. **Manual Installation:**
   - Download the latest release from the [Hugo Releases page](https://github.com/goharbor/hugo/releases).
   - Extract the downloaded archive and move the binary to `/usr/local/bin`:
     ```bash
     mv hugo /usr/local/bin/
     ```

#### **1.2. Windows**

1. **Using Chocolatey:**
   - Open Command Prompt as Administrator and run:
     ```bash
     choco install hugo -confirm
     ```

2. **Manual Installation:**
   - Download the latest Windows release from the [Hugo Releases page](https://github.com/goharbor/hugo/releases).
   - Extract the files and add the path to the `hugo.exe` to your system's PATH environment variable.

#### **1.3. Linux**

1. **Using Snap:**
   - Open Terminal and run:
     ```bash
     sudo snap install hugo --channel=latest/stable
     ```

2. **Manual Installation:**
   - Download the latest release from the [Hugo Releases page](https://github.com/goharbor/hugo/releases).
   - Extract the file and move it to `/usr/local/bin`:
     ```bash
     sudo mv hugo /usr/local/bin/
     ```

### ****2. Installing Hugolify (with Decap CMS)

#### Clone Repository

```bash
git clone git@github.com:vantt/hugolify-decapcms.git

npm install
```

### Run Hugolify
```bash
npm run cleanall
npm run watch
```
#### Setup Decap CMS

##### Enable Decap CMS
File: /config/_default/module.yaml

``` yaml
imports:
  - path: github.com/hugolify/hugolify-decap-cms
```

##### Setup Decap CMS
https://www.hugolify.io/docs/cms/decap-cms/#documention

###### Interface language
Create a **locale.js** file in your config directory: **/static/admin/app/config**.

```javascript
export const locale = "en"; // or 'fr'
```

###### Multilingual content edition
Create a **available-languages.js** file in your settings directy: **/static/admin/app/settings**.

```javascript
export const availableLanguages = ["fr", "en"];
```


## Live demos

### Base

https://demo.hugolify.io/

[![Netlify Status](https://api.netlify.com/api/v1/badges/5a4fa061-e7a5-4e66-9612-4fae713bda09/deploy-status)](https://app.netlify.com/sites/hugolify-demo/deploys)

### Theme 1

https://theme-1--hugolify-demo.netlify.app/

### Theme 2

https://theme-2--hugolify-demo.netlify.app/

### Theme 3

https://theme-3--hugolify-demo.netlify.app/

### Theme 4

https://theme-4--hugolify-demo.netlify.app/

### Products

https://demo-products--hugolify-demo.netlify.app

## Documentation

https://www.hugolify.io/docs/

## License

Hugolify is free for personal or commercial projects (MIT license)
