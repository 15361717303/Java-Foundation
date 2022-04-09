# 集合简介



## 1、什么是集合

java集合框架有很多，如list,set,map

所有的集合类都在java.util包下面

主要是有两个接口Collection和Map



## 2、Collection和Map的主要区别

collection下的都是一次存储一个值

Map是每次存储一个<k,v>键值对



## 3、集合和数组的区别，以及使用结合的好处

区别：

1. 从可以使用长度来说：集合可以自增长，不需要提前知道所要存储数据的长度，数组是固定长度，所以需要提前知道要存储数据的长度

2. 从存储数据类型角度看：数组可以存储8种基本数据类型，同时也可以存储引用数据类型，然而集合只能存储引用数据类型，如：不能存储int,double,boolean，只能通过存储Integer,Double,Boolean类型的数据，在存储的时候，通过编译时有类型的擦除，最后都会变成Object类型 

   ```java
   (Object)1 ->(Object)Integer.valueOf(1)
   ```

3. 数组存储的元素必须是要同一个数据类，集合存储的对象可以是不同数据类型的

好处：

1. 容量自增长；
2. 提供了高性能的数据结构和算法，使编码更轻松，提高了程序速度和质量；
3. 允许不同 API 之间的互操作，API之间可以来回传递集合；
4. 可以方便地扩展或改写集合，提高代码复用性和可操作性。
5. 通过使用JDK自带的集合类，可以降低代码维护和学习新API成本。

## 4、集合的特点

- 对象封装数据，对象多了也需要存储。集合用于存储对象。
- 对象的个数确定可以使用数组，对象的个数不确定的可以用集合。因为集合是可变长度的。



# 5、集合分类



## 5.1 Collections接口

![](Collection%20introduction.assets/collection.png)



### 5.1.1 list

#### 5.1.1.1 ArrayList

![](Collection%20introduction.assets/ArrayList.png)

#### 5.1.1.2 LinkedList

![](Collection%20introduction.assets/LinkedList.png)

#### 5.1.1.3 Vector

![](Collection%20introduction.assets/Vector.png)

### 5.1.2 set



#### 5.1.2.1 HashSet



#### 5.1.2.2 TreeSet



#### 5.1.2.3 LinkedHashSet





## 5.2 Map接口















