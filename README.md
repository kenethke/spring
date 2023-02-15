# My reference book about Spring

## Bean
Bean == object (spring object)

## Container
* Container consist of beans ( <bean "options"> info </bean> )
* That is container == kit of beans
* TEMPLATE : beans container /beans

## Options
* id - identifier
* class - directory to any class
* scope - patterns (use static variables/methods or not) singleton or prototype
* TEMPLATE bean id = "..." class = "..."
  
## Info
* bean
constructor-arg ref = "other_some_bean" /
constructor-arg ref = "some_bean" / - it looks like extends class (class C = class A + class B)
/bean
  
## Also we can add values to constructor
* Example:
  * Sequential order as in a constructor
  constructor-arg values = "qwerty"
  constructor-arg values = "123"
  * Accessing variables
  constructor-arg name = "var1" values = "qwerty"
  constructor-arg name = "var2" values = "123"
  * Accessing index
  constructor-arg index = "0" values = "qwerty"
  constructor-arg index = "1" values = "123"
    

    
