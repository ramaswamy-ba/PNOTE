# PNOTE

Behaviour changes between C++17 and C++20
#include <iostream>
struct S
{
  S() = delete;
  int x;
};
int main()
{
  auto s = S{};
  std::cout << s.x;
}
