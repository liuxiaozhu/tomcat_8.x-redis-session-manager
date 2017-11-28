# tomcat_8.x-redis-session-manager
#### 进行了重新编译以适配 tomcat 8.x
#### context.xml
```xml
<Valve className="com.radiadesign.catalina.session.RedisSessionHandlerValve" />
	<Manager className="com.radiadesign.catalina.session.RedisSessionManager"
         host="localhost" 
         port="6379" 
         database="0" 
         maxInactiveInterval="60"  />
```
