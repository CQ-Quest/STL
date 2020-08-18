#  输出小数点后精准位数 #  


————————————————————————————————————————————————
#   全排列函数 next_permutation #  

![image](https://github.com/CQ-Quest/STL/blob/master/zdx.png)  
public void main(){  
   int n;  
   cin>>n;  
   string s;  
   while(n--){  
   cin>>s;  
   sort(s.begin(),s.end());  
   do{  
      cout<<s<<endl;  
   }while(next_permutation(s.begin(),s.end()));  
   cout<<endl;  
   }  
}  


——————————————————————————————————————————————————
#  概率随机数  #  

#include<ctime>  
srand((unsigned)time(NULL));     //保证随机分配种子(在循环之外)  
 for(int i=1;i<=10;i++)  
       i=rand() % 2;              //50%的机率  
       
   for(int i=1;i<=100;i++)  
   i=rand()%100+1;             //从0到100随机取数  
   
   
———————————————————————————————————————————————————————
   
