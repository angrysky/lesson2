# lesson2
test
# include<iostream>
# include<string>
# include<vector>
using namespace std;
int main()
{
  vector<string>str("hello","world","C++");
  for(auto beg=str.begin();beg!=str.end();++beg)
       cout<<*beg<<endl;
  return 0;
}
