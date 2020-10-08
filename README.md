# Java-6
Java课程作业项目仓库

# 阅读程序

## 实验目的
用类描述计算机中CPU的速度和硬盘容量。要求Java应用程序中有4个类，名字分别是PC、CPU、HardDisk和Test,其中Test是主类。


## 实验过程
（1）main方法中创建一个CPU对象cpu，cpu将自己的speed设置为2200.
 (2)main方法中创建一个HardDisk对象disk,disk将自己的amount设置为200.
（3）main方法中创建一个PC对象pc.
（4）pc调用setCPU(CPU c)方法，调用时实参是cpu.
（5）pc调用setHardDisk(HardDisk h)方法，调用时实参是disk.
（6）pc调用show()方法



## 核心方法
1. 方法1：main方法中创建一个CPU对象cpu，创建一个HardDisk对象disk.
package Neirong;
public class CPU {
	int speed;
	int getSpeed(){
		return speed;
	}
	public void setSpeed(int speed){
		this.speed=speed;
	}
	
}
2. 方法2:cpu将自己的speed设置为2200,disk将自己的amoount设置为200
CPU cpu=new CPU();
		HardDisk HD=new HardDisk();
		cpu.setSpeed(2200);
    HD.setAmount(200);
3. 方法3：pc调用show（）方法
void show(){
	 System.out.println("CPU速度:"+cpu.getSpeed());
	 System.out.println("硬盘容量"+HD.getAmount());
4.方法4：pc调用setCPU(CPU c)地方法，调用时实参是cpu.
        pc调用setHardDisk(HardDisk h)方法，调用时实参是disk.
CPU cpu=new CPU();
		HardDisk HD=new HardDisk();


## 实验结果
实验截图与运行结果：https://github.com/wangchen2019311152/Java-6/tree/main/%E5%AE%9E%E9%AA%8C%E6%88%AA%E5%9B%BE



## 实验感想
通过本次实验，使我收获很大、受益匪浅，它不但极大地加深了我对一些理论知识的理解，不仅使我在理论上对Java有了全新的认识，在实践能力上也得到了提高，真正地做到了学以致用，更学到了很多的做人道理。
除此之外，我知道了什么叫做团队，怎样与团队分工合作，同时我还学会了如何更好地与他人沟通，如何更好地陈述自己的观点。
