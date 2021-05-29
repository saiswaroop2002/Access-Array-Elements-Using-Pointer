# Access-Array-Elements-Using-Pointer
#include &lt;iostream> using namespace std;  int main() {    int data[5];    cout &lt;&lt; "Enter elements: ";     for(int i = 0; i &lt; 5; ++i)       cin >> data[i];     cout &lt;&lt; "You entered: ";    for(int i = 0; i &lt; 5; ++i)       cout &lt;&lt; endl &lt;&lt; *(data + i);     return 0; }
