## 指针、引用、和对象的区别与联系
对象是一块内存空间。存储了一定的数据，是类的一个实例  
引用是对象的别名，引用在声明的时候必须绑定一个对象。引用和对象一经绑定，一般不作修改  
指针的一种对象，里面存放的是地址，代表一个对象或一个数组的起始地址。
指针在声明时不一定要初始化，但最好要把它初始化成nullptr或者0，以免引发不必要的错误
和引用不同的是指针的内容可以进行修改，可以更换指针所指向的地址，还可以进行++ -- 操作。
一方面可以通过使用指针来进行多元化的操作，但指针的使用也会容易引起一些安全问题。所以尽可能的多使用引用。  

##  智能指针

## select 和 epoll

## C++的多态

## 