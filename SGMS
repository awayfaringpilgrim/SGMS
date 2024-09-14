
import java.util.ArrayList;
import java.util.*;

public class SGMS {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        ArrayList<String> students = new ArrayList<>();
        ArrayList<Double> grades = new ArrayList<>();
        int count = 0;
        double sum = 0;
        
        System.out.println("Welcome to the SGMS (Student Grade Management System!");
        while (true) {
            System.out.println("Enter student name:");
            String name = scanner.nextLine();
            if (name.isEmpty()) {
                break;
            }
            students.add(name);
            System.out.println("Enter grade(s):");
            Double grade = Double.valueOf(scanner.nextLine());
            if (grade >= 0 && grade <= 100) {
                grades.add(grade);
            } else {
                System.out.println("Not a valid grade!");
            }
        }

        for (int i = 0; i < students.size(); i++) {
            System.out.println(students.get(i) + ": " + grades.get(i));
        }

        for (double grade:grades) {
            sum += grade;
            count++;
        }
        
        System.out.println("Class average: " + (sum/count));
    }
}
