# Code  C  

c 语言学习笔记

1- 基础部分
2- 结构语句
3- 函数
4- 阵列
5- 指针

列题（1）：输入者输入10个整数后，输入要查询的上下界，比如10 - 20 之间

# include <stdio.h>
* int main (){
 *   int i   ,   n[10];
 *   for(i=1;i<=10;i++){
   *         scanf("%d",&n[i-1]);   ---------这里的for循环  是为了把输入的十个数 放进来,存到阵列里面
    }
 *   while (1) {
   *     int     l   ,   r   ;
    *    printf("L R:");   ------------查询  上界  和 下界
     *   scanf("%d%d",&l,&r);
     *   printf ("ANS =");
      *  for (i=0 ; i< 10; i++){
       *             if(n[i]>=l&&n[i]<=r){
        *                printf("%d\t",n[i]);
        *            }
     *   }
    *    printf("\n");
 *  }

 *    return 0;
*}
