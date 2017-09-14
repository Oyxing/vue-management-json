# vue-management-json

本地json 数据 json-server 启用 3000 端口

## 运行方法 
  
  npm run json:server
  
 
## json-server  自带的方法

  //获取所有用户信息
  http://localhost:3000/users/1
  
  //获取id为的用户信息
  http://localhost:3000/users/1
  
  //获取所有公司的所有信息
  http://loaclhost:3000/companies
  
  //获取所有公司id为1的用户
  http://loaclhost:3000/companies/1/users
  
  //根据公司名字获取信息
  http://loaclhost:3000/companies?name=Microsoft
  
  //根据多个名字 获取公司 信息
  http://loaclhost:3000/companies?name=Microsoft&name=Apple
  
  //获取一页中只有两条信息
  http://loaclhost:3000/companies?_page=1&_limit=2
  
  //升序排序 asc 升序 desc 降序
  http://loaclhost:3000/companies?_sort=name&_order=asc
  
  //获取年龄30 及以上的
  http://loaclhost:3000/users?age_gte=30
