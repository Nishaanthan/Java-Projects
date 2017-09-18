package test;

class baloon {
    private String color ;
    public baloon(){
        color = "red";
    }
    public String getColor(){
        return this.color;
    }
    public void setColor(String color){
        this.color = color ;
    }   
}

public class Test {
    public static void main(String[] args) {
        baloon redBaloon = new baloon();
        baloon blueBaloon = new baloon();
        blueBaloon.setColor("blue");
        System.out.println("Color of Redbaloon is : " + redBaloon.getColor() + "(before swap)");
        System.out.println("Color of Bluebaloon is : " + blueBaloon.getColor()+ "(before swap)\n");
        swap(redBaloon,blueBaloon);
        System.out.println("Color of Redbaloon is : " + redBaloon.getColor() + "(after swap)");
        System.out.println("Color of Bluebaloon is : " + blueBaloon.getColor()+ "(after swap)");      
        
    }
    public static void swap(baloon b1 , baloon b2){
        String temp = b1.getColor(); 
        b1.setColor(b2.getColor()) ;
        b2.setColor(temp) ;
    }
}
