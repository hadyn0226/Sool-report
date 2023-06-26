c:/server/upload
폴더를 만들어주세요.

server.xml <host>태그안에 
<Context docBase="C:/server/upload/" path="/images"
					reloadable="false" />
을 넣어주세요.