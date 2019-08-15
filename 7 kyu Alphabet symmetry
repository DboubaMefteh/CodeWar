#include <vector>
#include <string>

std::vector<int> solve(std::vector<std::string> arr){  
  //your code herw
  int sizeArr=arr.size();
  std::vector<int> rslt;
  int count;
  for (int i=0;i<sizeArr;i++)
    {
      count=0;
      std::string chaine=arr[i];
      int sizeElement=chaine.length();
      
      for (int j=0;j<sizeElement;j++)
        if(((chaine[j]-97)==j)||(chaine[j]-65)==j)
          {
            count++;
          }
          
      rslt.push_back(count);
      
      
      }
      return rslt;
      }
