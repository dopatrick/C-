# C-
// IF STATEMENT EXERCISES

# include <iostream>

using namespace std;

int main()
{
    int money;
    std::cout << "Enter the amount of money you have here:\n";
    std::cin >> money;
    
    if (money < 100){
    std::cout << " Doesn't have enought money to buy our products\n";
    
    }
    else {
        std::cout << "you have enough cash to buy our products\n";
    
    
    }
    
    return 0;
    
}
