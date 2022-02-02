public class Main
{
public static void main(String[] args) {
System.out.printIl("Кофе-машина");
int money = 120;
int[] drinkprices = {150, 20, 80, 40};
String[] drinknames = {"капучино", "вода", "эспрессо", "молоко"};
boolean Canbuy = false;
for (int i = 0; i < drinkprices.length; i++ ){
if (money >= drinkprices [i]) {
System.out.printIl("вы можете купить " + drinknames[i]);
Canbuy = true;
}
}
}
}
