```c++
#include <iostream>
#include <string>

using namespace std;
class Cothi {
  public:
    Cothi() {
      name = "jiung han";
      role = "Software Engineer";
      currentFocus = "I am focusing on backend technologies.";
      portfolio = "https://cothi.github.io/";
      blog = "https://wooong-dev.tistory.com/";
    }
  void sayHi() {
    cout << "Hello";
  }
  private:
    string name;
    string role;
    string portfolio;
    string currentFocus;
    string blog;
};
int main() {
  Cothi me;
  me.sayHi();
}
```

---
| type | badge|
| ---- |----|
| algorithm |[![Solved.ac프로필](http://mazassumnida.wtf/api/mini/generate_badge?boj=codethinking)](https://solved.ac/codethinking) </br>[![Codeforces](https://badges.joonhyung.xyz/codeforces/cothi.svg)](https://codeforces.com/profile/cothi) |
