# Create React App
Untuk membuat project react js, dapat dilakukan dengan banyak cara. cara yang paling mudah adalah “create react app”.

Untuk dapat menjalankan perintah “create-react-app”,perlu menginstall node.js di komputer.

mendownload node.js pada link berikut dan install di komputer:

https://nodejs.org/en/

Setelah node.js terinstall di komputer , buka Command Promt atau terminal kemudian ketikkan perintah berikut untuk memastikan node.js terinstall dengan baik di komputer :

node -v Kemudian ketikan perintah berikut untuk memastikan NPM (Node Package Manager) juga terinstall dengan baik:

npm -v

Setelah node.js dan npm terinstall dengan baik di komputer , buat project react baru dengan mengetikan perintah berikut pada command promt atau terminal git bash:

npx create-react-app create-react-app

Perintah diatas akan membuat project react baru bernama “create-react-app”.

kemudian ketikan perintah berikut pada terminal untuk menjalankan project:

1 npm start

Kemudian buka browser dan kunjungi URL berikut:

1 http://localhost:3000

 dalam project terdapat 3 folder yaitu: folder node_modules, public, dan src.

Folder node_modules berisi semua modul yang dibutuhkan dalam pembuatan project.

Folder public berisi file index.html, favicon.ico, dan beberapa file lainnya.

File index.html merepresentasikan Single Page Application (SPA).

Folder src berisi file App.css, App.js, App.test.js, index.css, index.js, logo.svg, reportWebVitals.js, dan setupTests.js.

Yang penting untuk Anda ketahui adalah file App.js dan index.js.

File App.js adalah file root component dari react app, sedangkan file index.js adalah entry point dari aplikasi kita.

Selanjutnya lakukan sedikit clean up. Hapus file App.css, App.test.js, index.css, logo.svg, reportWebVitals.js, dan setupTests.js.

Sehingga yang tersisa hanya file App.js dan index.js. di folder src

untuk menjalankan project kita bisa tulis sintax di file App.js dan index.js
apabila di port 3000 muncul "Hello World" berarti berhasil

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
