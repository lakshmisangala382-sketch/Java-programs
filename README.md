import java.util.ArrayList;

public class StudentNames {
    public static void main(String[] args) {

        ArrayList<String> list = new ArrayList<>();

        list.add("Lakshmi");
        list.add("Anu");
        list.add("Priya");
        list.add("Kiran");

        System.out.println("Student Names:");
        for(String name : list) {
            System.out.println(name);
        }
    }
}# Java-programs