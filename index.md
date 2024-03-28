---
title: Welcome to my blog
---
''''#include<stdio.h>


int *FIND_Max(int *max,int n)
{
    int *arr=max;
     for(int i=1;i<n;i++)
     {
        if(*arr<max[i])
        *arr=max[i];
     }
     return arr;
}


int main()
{
    int lood[6]={1,59,35,12,56,74};
    int n=6;
    int *MAX=NULL;
    
    MAX=FIND_Max(lood,n);
    printf("%d\n%d",MAX,*MAX);


    return  0;
}
''''


