var express=require('express');
var app=express();
app.set('port', (process.env.PORT || 5000));
app.get('/',function(req,res){
  res.sendFile(__dirname+'/index.htm')
})
app.get('/list',function(req,res){
res.send('kkkkkk----jjj kist list')
})
var server=app.listen(app.get('port'),function(){
var host=server.address().address;
var port=server.address().port;
console.log(host+'-----'+port);
})
