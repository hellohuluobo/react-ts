#### 安装依赖 package.json npm init -y
---
1. cnpm i react react-dom @types/react @types/react-dom react-router-dom @types/react-router-dom react-transition-group @types/react-transition-group react-swipe @types/react-swipe -S
2. cnpm i webpack webpack-cli webpack-dev-server html-webpack-plugin -D
3. cnpm i typescript ts-loader source-map-loader -D
4. cnpm i redux react-redux @types/react-redux redux-thunk redux-logger @types/redux-logger -S
5. cnpm i connected-react-router -S <可以通过向仓库派发动作的方式实现路由跳转。
每次路径发生变化时可以把最新的路径放到仓库里面，以便随时在仓库中获取。>