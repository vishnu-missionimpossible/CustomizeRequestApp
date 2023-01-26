# CustomizeRequestApp

Customize Request App
1. In the App bascially we are customizing the request before it reaches to the server
2. We have used a filter that if user enter "java" or "jee" or "springboot", It will output INeuron. If user enters any other words then it will output the same word what user has entered.
3. Using CustomzedRequest class we are passing the request from filter to the class and then we are overriding the getParamter() method and applying our if else logic there.
4. That customized request will be sent to the  TargetServlet.
