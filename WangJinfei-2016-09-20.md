# 2016-09-20工作日志
======================

1. 已完成工作
	 
2. 工作成果

 运行结果：

 ![001](images/001.jpg)


3. 未完成工作

无

4. 未完成原因

无

5. 遇到的问题及解决方案

if(pet instanceof Dog ){
			Dog dog1 = new Dog();
			//dog1 = (Dog) pet;
			dog1.catchingFlyDisc();
		}
		else{
			Penguin penguin = (Penguin) pet;
			penguin.swimming();
		}
此时dog1类是一个新的类，与传入的dog类不同，
  
Dog dog1 =(Dog) pet;  即可
