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
### 6일차
```
#include<stdio.h>

int main(void)
{

	int dan = 1;
	int num = 0;

	for (dan = 1; dan <= 9; dan++)
	{
		for (num = 0; num < 10; num++)
		{
			printf(" %d x %d = %d \\n", dan, num,dan * num);
		}
		printf("\\n\\n");
	}


	return 0;
}

/*
	double total = 0.0;
	double input = 0.0;

	int num = 0;

	for (; input >= 0.0;)
	{
		total += input;
		printf(" 실수를 입력(minus to quit) :");
		scanf_s("%lf", &input);
		printf(" + %lf", input);
		num++;
	}

	printf("\\n");
	printf(" total sum = %lf \\n\\n", total);

	printf("평균 : %lf \\n\\n", total / (num - 1));
*/

/*
int total = 0;
int i = 0, sum = 0;

printf("0부터 num 까지 덧셈 sumd은?");
scanf_s("%d", &sum);
printf("%d", total);

for (i = 1; i <= sum; i++)
{
	total += i;
	printf(" + %d", i);
}

printf(" = %d \\n", total);
*/

/*
	int num = 0;

	for (num = 0; num < 3;num++)
	{
		printf("Hi for \\n");
	}

	num = 0;
	while (num < 3)
	{
		printf("Hi while \\n");
		num++;
	}
*/

/*
	int num = 0;

	do
	{
		printf("%d \\n", num);
		num++;
	} while (num < 0);
*/

/*
	int dan = 1, num = 0;

	while (dan <= 9)
	{
		num = 0;
		while (num <= 9)
		{
			printf(" %d x %d = %d \\n", dan, num, dan * num);
			num++;
		}
		dan++;
		printf("\\n\\n\\n");
	}
*/

/*
	int dan = 0, num = 0;

	printf("구구단의 단수를 입력하세요");
	scanf_s("%d", &dan);

	while (num <= 9)
	{
		printf(" %d x %d = %d \\n", dan , num, dan * num);
		num++;
	}
	return 0;
*/

/*
	int num = 0;

	while (num < 3)
	{
		printf("%d \\n", num);
		num++;
	}

	return 0;
*/
```
### 7일차
```
#include<stdio.h>

int main(void)
{

  char sel;

  printf("M 오전, A 오후, E 저녁 \n");
  printf("입력 : ");
  scanf("%c", &sel);

  switch(sel)
  {
    case'm':
    case'M':
        printf("Morning \n");
          break;
    case'a':
    case'A':
        printf("Afternoon \n");
          break;
    case'e':
    case'E':
        printf("Evening \n");
          break;
    default : 
        print("잘못 입력했습니다. \n");
      
}

  return 0;
}

/*
  int num 0;

  printf("정수 입력: ");
  scanf("%d", &num);

  if(num < 0)
  {
    printf("입력된 수는 음수입니다.\n);
  }
  if(num > 0)
  {
    printf("입력된 수는 양수입니다.\n);
  }
  if(num = 0)
  {
    printf("입력된 수는 0입니다.\n);
  }
*/

/*
  int opt;
  double num1 = 0.0, num2 = 0.0;
  double result = 0.0;

  printf("1, 덧셈 2. 뺄셈 3. 곱셈 4. 나눗셈 \n");
  printf("선택하세요?");
  scanf("%d", &opt);

  if((opt < 1) || (opt > 4))
  {
    printf("잘못 입력하였습니다 \n");
    return -1;
  }

  printf("두 개의 실수 입력");
  scanf("%lf %lf", &num1, &num2);

  if(opt == 1)
  {
    result = num1 + num2;
  }
  if(opt == 2)
  {
    result = num1 - num2;
  }
  if(opt == 3)
  {
    result = num1 * num2;
  }
  if(opt == 4)
  {
    result = num1 / num2;
  }
  printf("결과 : %lf \n", result);

*/

/*

  int num;
  printf("정수 입력 : ");
  scanf("%d", &num);

  if(num < 0)
  {
    printf("입력된 정수를 0보다 작다 \n");
  }
  else
  {
    printf("입력된 정수는 0보다 작지 않다 \n");
  }
  
*/

/*
  int opt;
  double num1 = 0.0, num2 = 0.0;
  double result = 0.0;

  printf("1, 덧셈 2. 뺄셈 3. 곱셈 4. 나눗셈 \n");
  printf("선택하세요?");
  scanf("%d", &opt);

  printf("두 개의 실수 입력");
  scanf("%lf %lf", &num1, &num2);

  if(opt == 1)
  {
    result = num1 + num2;
  }
  else if(opt == 2)
  {
    result = num1 - num2;
  }
  else if(opt == 3)
  {
    result = num1 * num2;
  }
  else if(opt == 4)
  {
    result = num1 / num2;
  }

  else
  {
    printf("잘못 입력하였습니다 \n");
    return -1;
  }
  printf("결과 : %lf \n", result);
*/

/*
  int num, abs;

  printf("정수 입력 : ");
  scanf("%d", &num);

  abs = (num > 0) ? num : num*(-1);

  printf("절대값 : %d \n\n", abs);
*/

/*
   int sum = 0;
  int num = 0;

  while (1)
  {
    sum+= num;
    if(sum > 5000) break;
    num++;
  }
  printf("sum : %d \n", sum);
  printf("num : %d \n", num);
*/

/*
int num = 0;

  printf("start ! : ");

  for(num = 1; num < 20; num++)
  {
    if((num % 2 == 0) || (num % 3 == 0))
    {
        continue;
    }
    printf("%d", num);
  }
  printf("end! \n\n");
*/

/*
  int num;
  printf("1-5 정수 입력 : ");
  scanf("%d", &num);
  switch(num)
  {
    case 1 :
        printf("1은 one \n");
        break;
     case 2 :
        printf("2은 two \n");
        break;
     case 3 :
        printf("3은 three \n");
        break;
     case 4 :
        printf("4은 four \n");
        break;
     case 5 :
        printf("5은 five \n");
        break;
    default :
        printf(" I do not know~~ \n);
  }
*/

/*

*/
```
### 8일차
```
#include<stdio.h>

int main(void)
{
	int num = 0;
	int i = 2;
	int j = 0;
	int cnt = 0;
	int sum = 0;
	printf("1-num까지의 계차 수열의 합을 구하세요 num 을 입력하세요:");
	scanf_s("%d", &num);
	printf("\n\n\nfor문 이용\n\n\n");

	for (i =2; i <= num;i+=j)
	{

		j += 1;
		sum += i;

		printf("cnt = %2d, j= %2d , i= %3d, sum = %d\n", cnt,j , i,sum);

	}

	printf("\n\n\nwhile문 이용 \n\n\n");
	i = 2; //i 초기화
	sum = 0;
	j = 0;
	while (i<=num)
	{

		j += 1;

		sum += i;

		printf("cnt = %2d, j= %2d , i= %3d, sum = %d\n", cnt, j, i, sum);
		i = i + j;
	}

	printf("\n\n\ndo while문 이용 \n\n\n");
	i = 2; //i 초기화
	sum = 0;
	j = 0;
	do
	{

		j += 1;

		sum += i;

		printf("cnt = %2d, j= %2d , i= %3d, sum = %d\n", cnt, j, i, sum);
		i = i + j;
	} while (i <= num);
	return 0;
}
/*
//sum += i ;
//printf("cnt = %2d, j= %2d , i= %3d, sum = %d\\n", cnt, j, i, sum);

for (cnt =1; cnt < num;cnt++)
	{
		if(num>=cnt) break;
		j += 1;
		i += j;
		sum += i;

		printf("cnt = %2d, j= %2d , i= %3d, sum = %d\n", cnt,j , i,sum);

	}

*/

/*
	int num = 0;
	int i = 0;
	int sum = 0;
	printf("1-num까지의 합을 구하세요 num을 입력하세요 :");
	scanf_s("%d", &num);
	printf("\n\n\nfor문 이용\n\n\n");
	for (i = 1; i <= num;i++)
	{
		//sum = sum + 1;
		sum += i;
		//printf("%d %d\n", i, sum);


		printf("%d + ", i);
	}

	printf("\b\b = %d\n\n\n", sum); //backspace를 이용하여 + 지우기


	printf("\n\n\nwhile문 이용 \n\n\n");
	i = 1; //i 초기화
	sum = 0;
	while (i <= num)
	{
		//sum = sum + 1;
		sum += i;
		//printf("%d %d\n", i, sum);
		printf("%d + ", i);
		i++;

	}

	printf("\b\b = %d\n\n\n", sum); //backspace를 이용하여 + 지우기

	printf("\n\n\ndo while문 이용 \n\n\n");
	i = 1; //i 초기화
	sum = 0;
	do
	{
		//sum = sum + 1;
		sum += i;
		//printf("%d %d\n", i, sum);
		printf("%d + ", i);
		i++;


	} while (i <= num);

	printf("\b\b = %d\n\n\n", sum); //backspace를 이용하여 + 지우기


	return 0;
*/
```
### 9일차
```
#include<stdio.h>

void example1(void);
void example2(void);
void example3(void);


int GetAbsoValue(int num)
{
	if (num < 0)
	{
		return num * (-1);
	}
	else
	{
		return num;
	}
}
int AbsoCompare(int num1, int num2)
{
	if (GetAbsoValue(num1) > GetAbsoValue(num2))
	{
		return num1;
	}
	else
	{
		return num2;
	}
}
int add(int num1, int num2)
{
	int result = 0;
	result = num1 + num2;
	return result;
}

int sub(int num1, int num2)
{
	int result = 0;
	result = num1 - num2;
	return result;
}

void ShowAddRessult(int num)
{
	printf("덧셈 결과 출력 %d\n", num);
}
int ReadNum(void)
{
	int num;
	scanf_s("%d", &num);
	return num;
}

void HowToUseThisProg(void)
{
	printf("두개의 정수로 입력하시면 덧셈 결과가 출력됩니다.\n");
	printf("두개의 정수를 입력하세요\n");
}
int main(void)
{
	int num1, num2;
	printf("두개의 정수를 입력하세요\n");
	scanf_s("%d %d", &num1, &num2);
	printf("%d와 %d 중 절대값이 큰 정수 : %d\n", num1 , num2 , AbsoCompare(num1,num2));
	//int test;
	//ReadNum();

	//example1
	//example2();
	return 0;
}

void example1(void)
{
	int num1 = 0, num2 = 0;

	num1 = printf("1234\n");
	printf("    num : %d\n", num1);
}

void example2(void)
{
	int test = 0;

	test = add(1, 2);

	printf("add test = %d \n", test);

	ShowAddRessult(test);

	test = sub(1, 2);


	printf("sub test = %d \n", test);
}

void example3(void)
{
	int num1 = 0, num2 = 0, test = 0;

	HowToUseThisProg();

	num1 = ReadNum();
	num2 = ReadNum();
	test = add(num1, num2);
	ShowAddRessult(test);
}
```
