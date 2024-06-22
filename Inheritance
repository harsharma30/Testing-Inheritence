class Person  // super class 
{
   private String name;
    public Person(){
        name=null;
        System.out.println("Def constructor of super class invoked");
    }
    public Person(String name){
        this.name=name;
        System.out.println("Para constructor of super class invoked");
    }
    void setName(String name){
        this.name=name;
    }
    String getName(){
        return(name);
    }
    void displayData(){
        System.out.println("The name is :"+ name);
    }
}
class Employee extends Person{  // sub-class
    int empid;
    double salary;
    public Employee(){
        
        empid=0;
        salary=0.0;
        System.out.println("Def constructor of sub class invoked");
    }
    public Employee(int empid, double salary){
       super("ajay");
        this.empid=empid;
        this.salary=salary;
        System.out.println("Para constructor of sub class invoked");
    }
    public void showData()
    {
        System.out.println("The id is :"+ empid);
        System.out.println("The salary is: "+ salary);
    }
}
class TestInheritance{
    public static void main(String ar[])
    {
        Employee obj=new Employee(1001,3000.50);
        obj.displayData();
        obj.showData();
        // System.out.println(obj.name);
    }
}

