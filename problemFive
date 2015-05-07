/*
 * To change this template, choose Tools | Templates
 * and open the template in the editor.
 */
package javaapplication47;

/**
 *
 * @author Mike
 */
public class problemFive {

    /**
     * @param args the command line arguments
     */
  public static void main(String[] args) {
        // TODO code application logic here
        System.out.println(problem5());
    }

    public static int problem5() {
        int i = 2520;
        boolean found = false;
        while (!found) {
            i += 2520;
            boolean isDividable = true;
            for (int j = 11; j <= 20; j++) {
                if (i % j != 0) {
                    isDividable = false;
                    break;
                }
            }
            if (isDividable) {
                found = true;
            }
        }
        return i;
    }
}
