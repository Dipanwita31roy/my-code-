 #include <iostream>
using namespace std;
int main()
{
  int arr[500];
  int p=0;
  int n;
  cin>>n;
  for(int i=0;i<n;i++)
  {
    cin>>arr[i];
  }
  for(int i=0;i<n;i++)
  {
    for(int j=0;j<n;j++)
    {
      if(arr[i]<arr[j])
      {
        p=arr[i];
        arr[i]=arr[j];
        arr[j]=p;
      }
    }
  }
  for(int i=0;i<n;i++)
  {
    cout<<"  " <<arr[i];
   
  }
  return 0;
} 
