yarn global add create-react-app
create-react-app demo
cd demo
git add .
git commit -m 'first commit'
# 非必要: 解放各種設定檔包含 webpack
yarn run eject
# run server
yarn run start
# build static file to /build
yarn run build