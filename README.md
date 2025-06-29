# CHROM-EXTENSION-FOR-PERSONAL-PRODUCTIVTY-TRACKER

COMPANY: CODTECH IT SOLUTION

NAME: JAYSHRI PATIL

INTERN NO: CT06DF1906

DOMAIN: REACT.JS WEB DEVELOPMENT

DURATION: 6 WEEKS

MENTOR: NEELA SANTOSH

# INSTALLATION
Make sure you have NodeJs(>18) version installed

Clone repo

git clone https://github.com/satendra02/react-chrome-extension.git
Go to the react-chrome-extension directory and run

yarn install
Now build the extension using

yarn build
You will see a build folder generated inside [PROJECT_HOME]

To avoid running yarn build after updating any file, you can run

yarn watch
which listens to any local file changes, and rebuilds automatically.

OUTPUT

Adding React app extension to Chrome
In the Chrome browser, go to chrome://extensions page and switch on developer mode. This enables the ability to locally install a Chrome extension.

![Image](https://github.com/user-attachments/assets/fc8aeda3-463a-400c-9b87-ef28a60b1ffa)


Now click on the LOAD UNPACKED and browse to [PROJECT_HOME]\build, This will install the React app as a Chrome extension.

When you go to any website and click on the extension icon, the injected page will toggle.

![Image](https://github.com/user-attachments/assets/ec9c193d-67c9-4976-a8c0-3d9c3d320ee3)
