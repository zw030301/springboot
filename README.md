# springboot
关于SpringCache 注解的简单介绍
@Cacheable：标记在一个方法上，也可以标记在一个类上。主要是缓存标注对象的返回结果，标注在方法上缓存该方法的返回值，标注在类上，缓存该类所有的方法返回值
@CacheEvict：从缓存中移除相应数据
@CachePut：方法支持缓存功能。与@Cacheable不同的是使用@CachePut标注的方法在执行前不会去检查缓存中是否存在之前执行过的结果，而是每次都会执行该方法，并将执行结果以键值对的形式存入指定的缓存中。
@Caching:多个Cache注解使用,比如新增用户时，删除用户属性等需要删除或者更新多个缓存时，集合以上三个注解。

持续更新中。
