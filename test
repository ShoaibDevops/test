var http=require("http");
var fs=require("fs");
var onCreateServer=function(req,res){
fs.readFile("index.html",function (err, data){	 	
	res.writeHead(200,{"Content-Type":"text/html"});
res.write(data);
	res.end();
});


};
var server =http.createServer(onCreateServer);
server.listen(8000);
console.log("Server is listening on port 8000");
