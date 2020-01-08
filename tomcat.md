org.apache.tomcat.util.net.NioEndpoint#setSocketOptions  将发生事件注册给poller

org.apache.tomcat.util.net.NioEndpoint.Poller#addEvent 添加到poller监听的事件队列中

org.apache.tomcat.util.net.NioEndpoint.Poller#events  Poller启动之后，会轮询队列中是否有事件

org.apache.tomcat.util.net.NioEndpoint.Poller#processKey 处理对应的事件，将任务扔到执行线程池中









