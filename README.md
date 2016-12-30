# tomcat_8.x-redis-session-manager
### context.xml
    `<Valve className="com.radiadesign.catalina.session.RedisSessionHandlerValve" />
	<Manager className="com.radiadesign.catalina.session.RedisSessionManager"
         host="localhost" 
         port="6379" 
         database="0" 
         maxInactiveInterval="60"  />`