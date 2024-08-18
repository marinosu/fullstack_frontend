###### In react-router-dom v6, "Switch" is replaced by routes "Routes"
###### And "useHistory()" is replaced by useNavigate()

## If you use npm 5.1 or earlier, you can't use npx
npm uninstall -g create-react-app\
npm install -g create-react-app\
create-react-app my-app

## React router v4 or v5
> `<Route path="/" component={Home} />`

## React router v5.1
> `<Route exact path="/">`
>    `<Home />`
> `</Route>`

## React router v6
> `<Route path="/" element={<Home />} />`

###### For more: React Router - Upgrading to V6

## Extract to web page name 
https://mfikri.com/en/blog/node-express-react-mysql
