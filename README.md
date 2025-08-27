# hELLO

[hELLO](https://pronist.tistory.com/5)는 [Tidori Framework](https://github.com/pronist/tidory/wiki) This is a Tistory skin written in . Therefore, a separate development method is required. First, copy the project.

```bash
git clone https://github.com/pronist/hello
```

Go to the project folder `node_modules` You will need to install it. The Tidori framework is based on **Node.js, Webpack**. Therefore, **NPM (Node Package Manager)** is required.

```bash
cd hello && npm install
```

To see the skin with the Tistory placeholders applied, you need to use the **preview server**. Rename **tidory.config.example.js** to **tidory.config.js** and configure `ts_session` and `url` according to the Tidory framework's [environment settings](https://github.com/pronist/tidory/wiki/Configuration). These values ​​are used to directly communicate with the Tistory server and preview the skin with the placeholders interpreted.

Once the configuration is complete, you can run the preview server.

```bash
npm run preview
```

## Distribution

If `ts_session` and `url` are set in **tidory.config.js**, you can proceed with deployment. Please refer to [Build and Deployment](https://github.com/pronist/tidory/wiki/Deployment) of the Tidory framework.

```bash
npm run production && npm run deploy
```

## Copyright

Copyright 2020-2025. [SangWoo Jeong](https://github.com/pronist). All rights reserved.
