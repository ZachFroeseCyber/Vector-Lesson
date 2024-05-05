//Vector-Lesson
//quick lesson on the understanding of vectors while also including "for" conditions.


#include <iostream>
#include <vector>

int main(){

int total_even = 0;
int product_odd = 1;

std::vector<int> vector = {2, 4, 8, 9, 1, 3};

for(int i = 0; i < vector.size(); i++) {

  if (vector[i] % 2 == 0) {
    total_even = total_even + vector[i];
  } else {
    product_odd = product_odd * vector[i];
  }
}

std::cout << "Sum of even:" << total_even << "\n";
std::cout << "Product of odd: " << product_odd << "\n";


}
