Project-C-
==========

#include&lt;iostream> #include&lt;conio.h> using namespace std; int main() { cout &lt;&lt; "Welcome to Z&amp;A Accesories!" &lt;&lt; endl ; cout &lt;&lt; "
" &lt;&lt; "Products: " &lt;&lt; "
" &lt;&lt; "
" ; cout &lt;&lt; "Bracelet 100Php" &lt;&lt; endl; cout &lt;&lt; " product code: 101010" &lt;&lt; endl; cout &lt;&lt; "
" &lt;&lt; "Necklace 200Php" &lt;&lt; endl; cout &lt;&lt; " product code: 202020" &lt;&lt; endl; cout &lt;&lt; "
" &lt;&lt; "Anniversary Ring 300Php" &lt;&lt; endl; cout &lt;&lt; " product code: 303030" &lt;&lt; endl; int productcode; cout &lt;&lt; "
" &lt;&lt; "Enter product code: " ; cin >> productcode; int price; if (productcode==101010) {price = 100 ;} else if (productcode==202020) {price = 200 ;} else if (productcode==303030) {price = 300 ;} else {cout &lt;&lt; "You wrote the wrong product code, please try again" ; getch(); return 0;} int quantity; cout &lt;&lt; "Enter quantity: " ; cin >> quantity;  int total; total = quantity * price; cout &lt;&lt; "
" &lt;&lt; "Total amount to be paid: " &lt;&lt; total &lt;&lt; "Php" &lt;&lt; endl ; double amount; cout &lt;&lt; "Enter Amount: " ; cin >> amount; double change; if(total>amount) {cout &lt;&lt; "Amount entered insufficient, please try again" ;} else {change = amount - total ; cout &lt;&lt; "Your change is: " &lt;&lt; change &lt;&lt; endl; cout &lt;&lt; "Thank you for your purchase!!" ;} getch() ; return 0;  }
