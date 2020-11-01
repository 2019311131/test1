# test1
java test
#阅读程序

##实验目的
掌握面向对象的类设计方法，类的继承方法：用super实化子类，用obje根类的tostring 方法

##实验过程
首先进行框架设计，运用public class 声明学生选课这一类，第一个是学生信息，运用xm文件扩展信息姓名，年龄，编号，性别 ，最后系统输出，打印出来  
第二个是教师的信息 换一种cdm文件扩展信息具体到名称，年龄，性别，所教授课程，系统输出
第三个，课程信息包括所在教室 时间地点等等 用xxds进行扩展 最后系统输出，打印出来
再用class分别对people  Student extends People Teacher extends People Lesson Lesson_1 extends Lesson这些类名进行再次声明
其中people中再次包括 name age number sex
tudent extends People Teacher extends People其中也包括上面
用public lesson定义用私有变量来重新定义
 最后系统输出 打印出来 
 
 ###核心方法
 public class Xueshengxuanke {
    public static void main(String[] args) {
        System.out.println("******************学生信息*********************");
        Student xm = new Student();
        xm.setName("张一");
        xm.setAge(20);
        xm.setNumber(2019666888);
        xm.setSex("男");
        System.out.println("姓名:" + xm.getName());
        System.out.println(“年龄:" + xm.getAge());
        System.out.println("编号:" + xm.getNumber());
        System.out.println("性别:" + xm.getSex());

        System.out.println("******************教师信息*********************");
        Teacher cdm = new Teacher();
        cdm.setName("李二");
        cdm.setAge(55);
        cdm.setNumber(2001300001);
        cdm.setSex("女");
        cdm.setLesson_1("线性代数");
        System.out.println("授课教师:" + cdm.getName());
        System.out.println("年龄:" + cdm.getAge());
        System.out.println("编号:" + cdm.getNumber());
        System.out.println("性别:" + cdm.getSex());

        System.out.println("******************课程信息*********************");
        Lesson_1 xxds = new Lesson_1();
        xxds.setName("英语");
        xxds.setTime("每周末 晚上7:40-9:50");
        xxds.setNumber(806050);
        xxds.setPlace("教203");
        System.out.println(xxds.toString());

        System.out.println("******************课程详情*********************");
        System.out.println("选课成功");

    }

}


class People{
    public People()

class Student extends People{
    public Student(){

   
    public Student(String name,int age,int number,String sex){
        super(name, age, number, se

class Teacher extends People{
    public Teacher(){

    }
    public Teacher(String name,int age,int number,String sex){
        super(name, age, number, sex);
    


class Lesson{
    public Lesson(){

    }
    public Lesson(String name,String time,int number,String place){
        this.name = name;
        this.time = time;
        this.number = number;
        this.place = place;
  


class Lesson_1 extends Lesson{
    public Lesson_1(){

    }
    public Lesson_1(String name,String time,int number,String place){
        super(name, time, number, place);
    }
    public String toString() {
        return "课程名称：" + getName()+ "\n" + "上课时间：" + getTime() + "\n" + "课程编号：" + getNumber()+ "\n" + "授课地点：" + getPlace()+ "\n";
    }
}
 ####实验结果
 ![image](https://github.com/2019311131/test1/blob/main/%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20201101235813.png)
 ##实验感想
在此次JAVA实验中遇到了许许多多的困难，上次进行的实验测试，有些步骤已经忘记，通过请教同学以及观看b站视频一步一步的摸索了出来，在编写程序上也遇到了很大的阻力，不过在我和同学的共同努力下一起完成了它，接下来就是，编写实验报告其中粘贴照片时我遇到了及其困难的方法，最后在同学帮助下完成。总之JAVA此次实验对我来说是个很大的挑战，通过此次JAVA实验，我又跟进了一步，这就是我的全部感悟
