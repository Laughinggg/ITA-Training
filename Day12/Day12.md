# Day12

## Code Review

1. React has two api: class and function
2. function: hooks, useState, useEffect

## Redux

toolkit:createSlice,configureStore
react-redux:useDispatch(), useSelector()

## Day13

React Router

<BrowserRouter>: recommonded interface for running React Router in a web browser

<Link>: element that lets the user navigate to another page by clicking or tapping on it

<Routes> and <Route> primary ways to render something in React Router based on the current location.



axios

CROS

后端:Access-Control-Allow-Credentials: true
前端:withCredentials = true;
需要注意的是，如果要发送Cookie，Access-Control-Allow-Origin就不能设为星号，必须指定明确的、与请求网页一致的域名。同时，Cookie依然遵循同源政策，只有用服务器域名设置的Cookie才会上传，其他域名的Cookie并不会上传，且（跨源）原网页代码中的document.cookie也无法读取服务器域名下的Cookie。
