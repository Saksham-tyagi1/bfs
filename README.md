# dfs
#include<conio.h>
#include<stdio.h.
int delete()
void bfs(int,int)
int add(int)
int q[20],front=-1,rear=1,vis[20],a[20][20];
int main()
{ int n,i,source,ch,j;
   char c,temp;
   printf("enter the number of vertices");
   scanf("%d",&n);
   printf("Enter the graph in matrix form. ");
   for(i=0;i<n;i++)
   { for(j=0;j<n;j++)
     printf("\n TIP(if %d has a node with %d enter 1,else 0);
     scanf("%d",&a[i][j]);}
     }
     printf("enter the source vertex");
     scanf("%d",&source);
     bfs(source,n);
     return 0;}
     void bfs(int source,n);
     
     { int p,i;
       add(source);
       vis[s] =1;
       p=delete();
       if(p!=0)
       printf("%d",p);
       while(p!=0)
       { for(i=0;i<n;i++)
         if(a[p][i]!=0&&vis[i]=0)
         add(i);
         vis[i]=1;}
         p=delete();
         if(p!=0);
         printf("%d",p);
         }
         for(i=0;i<n;i++)
         bfs(i,n);
         }
         
         
         
         
         
         
         
         
         
         
         void add(int item)
         { if(rear==19);
         printf("queue full");
         return ;
         else
         if(rear==-1)
         q(++rear)=item;
         front++
         else
         q(++rear)=item;
         }
         }
         int delete()
         { if((front<queue)||(front==-1))
         return ;
         }
         else
         { k =q[front++];
           return (k);}
           }
         
         
         
         
         
         
         
         
         
         
         \
    
         
         
         
         
         
         
         
     
