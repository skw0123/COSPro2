### 1일차
```
#include <stdio.h>

int main(void)
{
	/*
		첫 번째 작성한 C 프로그램
		2024.04.03
	*/

	printf("Hello !  \n\n");
	printf("I am a Halla Student. \n");
	printf("%d\n", 0123);
	printf("%d     %d\n", 10, 20);

	return 1;
}
```
### 2일차
```
#include <stdio.h>

int main(void)
{
	int num1 = 10;
	int num2 = (num1--) + 2;
	printf("num1 : %d \n", num1);
	printf("num2 : %d \n", num2);
	return 0;
}

/*int num;
	num = 20;
	printf("%d \n", num);
*/

/*
int num1 = 3, num2 = 4;
	int result1 = num1 + num2;
	int result2 = num1 - num2;
	int result3 = num1 * num2;
	int result4 = num1 / num2;
	//num1 = num2 = 0;
	printf("num1: %d, num2: %d \n", num1, num2);
	printf("%d + %d = % d \n", num1, num2, result1);
	printf("%d - %d = % d \n", num1, num2, result2);
	printf("%d * %d = % d \n", num1, num2, result3);
	printf("%d / %d = % d \n", num1, num2, result4);
	return 0;
	*/
```
### 3일차
```
#include<stdio.h>
int main(void)
{
  char ch = 9;
  int num = 0;
  long numl = 0;
  float numf = 0.0;
  doble dnum = 0.0;
  printf("변수 ch의 크기 : %d \n", sizeof(ch));
  printf("변수 num의 크기 : %d \n", sizeof(num));
  printf("변수 numl의 크기 : %d \n", sizeof(numl));
  printf("변수 numf의 크기 : %d \n", sizeof(numf));
  printf("변수 dumd의 크기 : %d \n", sizeof(numd));
  printf("\n\n\n");
  return 0;
}

/*
  int num1 = 0, num2 = 0;
  int result = 0;

  printf("두 개의 정수를 입력해 주세요. ");
  //scanf("%d", &num1);
  //scanf("%d", &num2);
  scanf("%d %d", &num1, &num2);

  printf("입력된 정수는 (%d,%d)입니다. \n", num1, num2);
  result = num1 + num2;
  printf("%d + %d = %d \n", num1, num2, result);

  result = num1 - num2;
  printf("%d - %d = %d \n", num1, num2, result);

  result = num1 * num2;
  printf("%d * %d = %d \n", num1, num2, result);

  result = num1 / num2;
  printf("%d / %d = %d \n", num1, num2, result);

  result = num1 % num2;
  printf("%d %% %d = %d \n", num1, num2, result);
*/

/*
  int num1 = 0xA7, num2 0x43;
  int num3 = 032, num4 = 024;

  printf("0xA7의 10진 정수값 : %d \n", num1);
  printf("0x%X의 10진 정수값 : %d \n", num1, num1);
  printf("0x43의 10진 정수값 : %d \n", num2);
  printf("0x%X의 10진 정수값 : %d \n", num2, num2);

  printf("032의 10진 정수값 : %d \n", num3);
  printf("0%o의 10진 정수값 : %d \n", num3, num3);
  
  printf("024의 10진 정수값 : %d \n", num4);
  printf("0%o의 10진 정수값 : %d \n", num4, num4);
*/

/*
  char ch=9;
  int inum=1052;
  doble dnum=3.1415;
  printf("변수 ch의 크기 : %d \n", sizeof(ch));
  printf("변수 inum의 크기 : %d \n", sizeof(inum));
  printf("변수 double의 크기 : %d \n", sizeof(dnum));

  printf("char의 크기 : %d \n", sizeof(char));
  printf("int의 크기 : %d \n", sizeof(int));
  printf("long의 크기 : %d \n", sizeof(long));
  printf("long long의 크기 : %d \n", sizeof(long long));
  printf("float의 크기 : %d \n", sizeof(float));
  printf("double의 크기 : %d \n", sizeof(double));
*/
```
