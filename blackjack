import java.util.Scanner;

public class blackjack {
    public static void main(String []args) {
        int P = (int)(Math.random() * 11);
        int PP = (int)(Math.random() * 11);
        int ai = (int)(Math.random() * 11);
        int Ai = (int)(Math.random() * 11);
        int pp = P + PP;
        int aa = ai + Ai;
        System.out.println("Welcome to Black Jack!");
        System.out.println(" ");
        System.out.println("Your starting number is " + pp);
        System.out.println(" ");
        System.out.println("One of the Dealer\'s two cards is " + ai);
        System.out.println(" ");
        Scanner hit1 = new Scanner(System.in);
        System.out.println("Want to hit or fold?");
        String h1 = hit1.nextLine();
        String h = "hit";
        String d = "fold";
        int p1 = (int)(Math.random() * 11);
        int ai1 = (int)(Math.random() * 11);
        int aa1 = aa + ai1;
        int pp1 = pp + p1;
        if (h1.equals(d)) {
          if (pp > aa) {
            System.out.println("You have won at " + pp);
            System.out.println("The dealer had " + aa);
            System.exit(0);
          }
          if (pp < aa) {
            System.out.println("You have lost at " + pp);
            System.out.println("The dealer had " + aa);
            System.exit(0);
          }
          if (pp == aa) {
            System.out.println("You have lost at " + pp);
            System.out.println("The dealer had " + aa);
            System.exit(0);
        }
        if (h1.equals(h))
          if (pp1 > 21) {
            System.out.println("You busted over 21! You had " + pp1);
            System.exit(0);
          }
          if (pp1 == 21) {
            System.out.println("You have gotten a blackjack of 21!");
            System.exit(0);
          }
        }
          if (aa1 > 21) {
            System.out.println("The dealer has busted! They had " + aa1);
            System.out.println("You had " + pp1);
            System.exit(0);
          }
          if (pp <= 21)
            System.out.println("You are at " + pp1);
            Scanner hit2 = new Scanner(System.in);
            System.out.println("Want to hit or fold?");
            String h2 = hit2.nextLine();
            int p2 = (int)(Math.random() * 11);
            int pp2 = pp1 + p2;
            int ai2 = (int)(Math.random() * 11);
            int aa2 = ai2 + aa1;
        if (h2.equals(d)) {
          if (pp1 > aa1) {
            System.out.println("You have won at " + pp1);
            System.out.println("The dealer had " + aa1);
            System.exit(0);
          }
          if (pp1 < aa1) {
            System.out.println("You have lost at " + pp1);
            System.out.println("The dealer had " + aa1);
            System.exit(0);
          }
          if (pp1 == aa1) {
            System.out.println("You have lost at " + pp1);
            System.out.println("The dealer had " + aa1);
            System.exit(0);
        }
        if (h2.equals(h))
          if (pp2 > 21) {
            System.out.println("You busted, you finished at " + pp2);
            System.exit(0);
            }
          if (aa1 > 21) {
            System.out.println("The dealer has busted! They had " + aa1);
            System.exit(0);
          }
          if (pp2 == 21) {
            System.out.println("You have gotten a blackjack of 21!");
            System.exit(0);
            }
        }
          if (aa2 > 21) {
            System.out.println("The dealer has busted! They had " + aa2);
            System.out.println("You had " + pp2);
            System.exit(0);
          }
          if (pp2 <= 21)
            System.out.println("You are at " + pp2);
        Scanner hit3 = new Scanner(System.in);
        System.out.println("Want to hit or fold?");
        int p3 = (int)(Math.random() * 11);
        int pp3 = p3 + pp2;
        int ai3 = (int)(Math.random()* 11);
        int aa3 = ai3 + aa2;
        String h3 = hit3.nextLine();
        if (h3.equals(d)) {
          if (pp2 > aa2) {
            System.out.println("You have won at " + pp2);
            System.out.println("The dealer had " + aa2);
            System.exit(0);
          }
          if (pp2 < aa2) {
            System.out.println("You have lost at " + pp2);
            System.out.println("The dealer had " + aa2);
            System.exit(0);
          }
          if (pp2 == aa2) {
            System.out.println("You have lost at " + pp2);
            System.out.println("The dealer had " + aa2);
            System.exit(0);
        }
      }
        if (h3.equals(h))
          if (pp3 > 21) {
            System.out.println("You busted, you went over 21! Ended with " + pp3);
            System.exit(0);
          }
          if (pp3 == 21) {
            System.out.println("You have gotten a blackjack of 21!");
            System.exit(0);
          }
          if (aa3 > 21) {
            System.out.println("The dealer has busted! They had " + aa3);
            System.out.println("You had " + pp3);
            System.exit(0);
          }
          if (pp3 <= 21)
            System.out.println("You are at " + pp3);
        Scanner hit4 = new Scanner(System.in);
        System.out.println("Want to hit or fold?");
        String h4 = hit4.nextLine();
        int p4 = (int)(Math.random() * 11);
        int pp4 = p4 + pp3;
        int ai4 = (int)(Math.random() * 11);
        int aa4 = ai4 + aa3;
        if (h4.equals(d)) {
          if (pp3 > aa3) {
            System.out.println("You have won at " + pp3);
            System.out.println("The dealer had " + aa3);
            System.exit(0);
          }
          if (pp3 < aa3) {
            System.out.println("You have lost at " + pp3);
            System.out.println("The dealer had " + aa3);
            System.exit(0);
          }
          if (pp3 == aa3) {
            System.out.println("You have lost at " + pp3);
            System.out.println("The dealer had " + aa3);
            System.exit(0);
        }
          if (aa3 > 21) {
            System.out.println("The dealer has busted! They had " + aa3);
            System.out.println("You had " + pp3);
            System.exit(0);
          }
        }
        if (h4.equals(h))
          if (aa4 > 21) {
            System.out.println("The dealer has busted! They had " + aa4);
            System.out.println("You had " + pp4);
            System.exit(0);
          }
          if (pp4 > 21) {
            System.out.println("You busted, you went over 21! Ended with " + pp4);
            System.exit(0);
          }
          if (pp4 == 21) {
            System.out.println("You have gotten a blackjack of 21!");
            System.exit(0);
          }
          if (pp4 <= 21)
            System.out.println("You are at " + pp4);
        Scanner hit5 = new Scanner(System.in);
        System.out.println("Want to hit or fold?");
        String h5 = hit5.nextLine();
        int p5 = (int)(Math.random() * 11);
        int pp5 = p5 + pp4;
        int ai5 = (int)(Math.random() * 11);
        int aa5 = ai5 + aa4;
        if (h5.equals(d)) {
          if (aa4 > 21) {
            System.out.println("The dealer has busted! They had " + aa4);
            System.out.println("You had " + pp4);
            System.exit(0);
          }
          if (pp4 > aa4) {
            System.out.println("You have won at " + pp4);
            System.out.println("The dealer had " + aa4);
            System.exit(0);
          }
          if (pp4 < aa4) {
            System.out.println("You have lost at " + pp4);
            System.out.println("The dealer had " + aa4);
            System.exit(0);
          }
          if (pp4 == aa4) {
            System.out.println("You have lost at " + pp4);
            System.out.println("The dealer had " + aa4);
            System.exit(0);
        }
        }
        if (h5.equals(h))
          if (pp5 > 21) {
            System.out.println("You busted, you went above 21! You finished with " + pp5);
            System.exit(0);
          }
          if (pp5 == 21) {
            System.out.println("You have gotten a blackjack of 21!");
            System.exit(0);
          }
          if (aa5 > 21) {
            System.out.println("The dealer has busted! They had " + aa5);
            System.out.println("You had " + pp5);
            System.exit(0);
          }
          if (pp5 <= 21)
            if (pp5 > aa5)
              System.out.println("You have won! You finished with " + pp5);
              System.out.println("The dealer had " + aa5);
            if (pp5 < aa5)
              System.out.println("You have lost!");
              System.out.println("The dealer had " + aa5);
            if (aa5 == pp5)
              System.out.println("You have lost!");
              System.out.println("Both you and the dealer have " + aa5);
        if (pp5 <= 21)
            System.out.println("You are at " + pp5);
        Scanner hit6 = new Scanner(System.in);
        System.out.println("Want to hit or fold?");
        String h6 = hit6.nextLine();
        int p6 = (int)(Math.random() * 11);
        int pp6 = p6 + pp5;
        int ai6 = (int)(Math.random() * 11);
        int aa6 = ai6 + aa5;
        if (h4.equals(d)) {
          if (pp6 > aa6) {
            System.out.println("You have won at " + pp6);
            System.out.println("The dealer had " + aa6);
            System.exit(0);
          }
          if (pp6 < aa6) {
            System.out.println("You have lost at " + pp6);
            System.out.println("The dealer had " + aa6);
            System.exit(0);
          }
          if (pp6 == aa6) {
            System.out.println("You have lost at " + pp6);
            System.out.println("The dealer had " + aa6);
            System.exit(0);
        }
          if (aa6 > 21) {
            System.out.println("The dealer has busted! They had " + aa6);
            System.out.println("You had " + pp6);
            System.exit(0);
          }
        }
        if (h6.equals(h))
          if (pp6 > 21) {
            System.out.println("You busted, you went over 21! Ended with " + pp6);
            System.exit(0);
          }
          if (aa6 > 21) {
            System.out.println("The dealer has busted! They had " + aa6);
            System.out.println("You had " + pp6);
            System.exit(0);
          }
          if (aa6 < 21) {
            if (pp6 < 21) {
              if (pp6 < aa6) {
                System.out.println("You have lost, you had " + pp6);
                System.out.println("The dealer had " + aa6);
                System.exit(0);
              }
              if (pp6 > aa6) {
                System.out.println("You have won with " + pp6);
                System.out.println("While the dealer had " + aa6);
                System.exit(0);
              }
              if (pp6 == aa6) {
                System.out.println("You lost with " + pp6);
                System.out.println("The dealer had " + aa6);
                System.exit(0);
              }
            }
          }
              
            }
          }
