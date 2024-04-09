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
### 4일차
```#include<stdio.h>
int main(void)
{
  int num1 = 3;
  int num2 = 4;
  double divResult;
  //divResult = (double)num1 / (double)num2;
  divResult = (double)num1 / num2;

  printf("나눗셈 결과 : %f \n", divResult);

  return 0;
}

/*
  char ch1 = 'A', ch2 = 65;
  char ch3 = 'C', ch4 = 90;

  printf("%c %d \n", ch1, ch1);
  printf("%c %d \n", ch2, ch2);
  printf("%c %d \n", ch3, ch3);
  printf("%c %d \n", ch4, ch4);

*/

/*
  double num1 = 245;
  int num2 = 3.14159;
  int num3 = 129;
  char ch = num3;

  printf("정수 245를 실수로 : %lf \n", num1);
  printf("실수 3.1415를 실수로 : %d \n", num2);
  printf("큰 정수 129를 실수로 : %d \n", ch);
*/
```
### 5일차
```
#include<stdio.h>

int main(void)
{

	float num1;
	double num2;
	long double num3;

	printf("실수 입력1(e 표기법으로) : );
		scanf("%f", &num1);
	printf("입력한 실수 %f \n", num1);

	printf("실수 입력2(e 표기법으로) : );
		scanf("%lf", &num2);
	printf("입력한 실수 %lf \n", num2);

	printf("실수 입력3(e 표기법으로) : );
		scanf("%Lf", &num3);
	printf("입력한 실수 %Lf \n", num3);

	return 0;
}

//printf("test \" I am a student\ test\b")

/*
  int myAge = 12;
  printf("my age %d, %d %#d %#x %#X \n", my Age, my Age, my Age, my Age, my Age);
*/

/*
  printf("%f \n", 0.1234);
  printf("%e \n", 0.1234);
  printf("%f \n", 0.123456789);
  printf("%e \n", 0.123456789);
*/

/*
  double d1 = 1.23e-3
  double d2 = 1.23e-4
  double d3 = 1.23e-5
  double d4 = 1.23e-6

  printf("%e \n", d1);
  printf("%e \n", d2);
  printf("%e \n", d3);
  printf("%e \n", d4);
*/

//printf("%s %c \n", "AAAA", 'd');

/*
  printf("%-8s %14s %5s \n", "이름", "기계공학", "학년");
  printf("%-8s %10s %5s \n", "이름", "기계공학", "학년");
*/

/*
  int num1, num2, num3;

  printf("세 개의 정수 입력 : ");
  scanf("%d %o %x", &num1, &num2, &num3);
  printf("입력된 정수 10진 출력 : ");
  printf("%d %d %d \n", num1, num2, num3);
*/
```
