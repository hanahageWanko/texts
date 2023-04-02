# texts

``` text
#include <stdio.h>


/************************
*		100_2			*
************************/

//main() {
//
//	int a = 12345;
//	int b = 7;
//
//	printf("%d ÷ %d の余りは %d", a, b, a % b);
//
//}
//]

/************************
*		100_3			*	できない
************************/

//int main(void) {
//
//	int num = 0;
//
//	printf("input number : ");
//	scanf_s("%d", &num);
//	printf("your number is %d\n", num);
//
//	return 0;
//
//}


/************************
*		100_4			*
************************/

//int main(void) {
//
//	int inpNum = 0;
//
//	printf("input number : ");
//	scanf_s("%d", &inpNum);
//	printf("answer = %d", inpNum * 3);
//
//	return 0;
//}


/************************
*		100_6			*
************************/

//int main(void) {
//
//	int num = 0;
//
//	printf("input number:");
//	scanf_s("%d", &num);
//
//	while (num != 0) {
//
//		printf("input number:");
//		scanf_s("%d", &num);
//	
//	}
//	printf("zero");
//
//}


/************************
*		100_7			*
************************/

//int main(void) {
//
//	int num = 0;
//	char flg = 't';
//
//	while (flg = 't') {
//
//		printf("input number:");
//		scanf_s("%d", &num);
//
//		if (num != 0) {
//
//			printf("not zero\n");
//
//		}
//		else {
//			printf("zero\n");
//
//		}
//	}
//
//}

/************************
*		100_8			*
************************/

//int main(void) {
//
//	int num;
//	char flg = 't';
//
//	while (flg = 't')
//	{
//		printf("input number:");
//		scanf_s("%d", &num);
//
//		if ( num <= 0)
//		{
//			printf("\n");
//		}
//		else
//		{
//			printf("positive\n");
//		}
//	}

//}

/************************
*		100_10			*
************************/

//int main(void) {
//
//	int num;
//	char flg = 't';
//
//	while (flg = 't')
//	{
//		printf("input number:");
//		scanf_s("%d", &num);
//
//		if (num >= 1)
//		{
//			printf("absolute value is %d\n", num);
//		}
//		else
//		{
//			printf("absolute value is %d\n", num * -1);
//		}
//	}
//
//}


/************************
*		100_11			*
************************/

//int main(void) {
//	for (int i = 0; i < 10; i++) {
//		printf("Num:%d Hello World!\n", i+1);
//	}
//}

/************************
*		100_12			*
************************/

//int main(void) {
//
//	int count;
//
//	printf("input number : ");
//	scanf_s("%d", &count);
//
//	for (int i = 0; i < count; i++) {
//		printf("Num:%d Hello World!\n", i+1);
//	}
//}

/************************
*		100_14			*	forわからん
************************/
//
//int main(void) {

	//int count;
	//printf("input number : ");

	//scanf_s("%d", &count);

	//for (int i = 0; i <= count; i--) 
	//{
	//	printf("%d", count--);
	//}

	//while (0 <= count) {

	//	printf("%d", count--);

	//}
//}


/************************
*		100_15			*
************************/
//
//int main(void) {
//
//	int count;
//	printf("input number : ");
//
//	scanf_s("%d", &count);
//
//	for (int i = 0; i <= count; i++) 
//	{
//		printf("%d", i);
//
//		i++;
//	}
//	
//}

/************************
*		100_16			*
************************/

//int main(void) 
//{
//
//	int count;
//	printf("input number : ");
//
//	scanf_s("%d", &count);
//
//	while ( count != 0)
//	{
//		printf("input number : ");
//		scanf_s("%d", &count);
//
//	}
//
//}

/************************
*		100_17			*
************************/

//int main(void)
//{
	//int kuku[9];
	//int i;

	//for (i = 1; i <= 9; i++) {
	//	kuku[i - 1] = i * 3;
	//}

	//printf("3の段の九九を出力します\n");

	//for (i = 1; i <= 9; i++) {
	//	printf("3 * %d = %d\n", i, kuku[i - 1]);
	//}

	//return 0;



//	int arr[10];
//	
//	for (int i = 0; i < 10; i++)
//	{
//		//int num = sizeof(arr);
//		arr[i] = i;
//		printf("%d\n", arr[i]);
//	}
//
//}

/************************
*		100_18			*
************************/

//int main(void) 
//{
//	int array[10];
//	int num;
//
//	printf("input number:");
//	scanf_s("%d", &num);
//
//	for (int i = 0; i < 10; i++) 
//	{
//		array[i] = num;
//		printf("%d\n", array[i]);
//
//	}
//}

/************************
*		100_19			*
************************/

//int main(void) 
//{
//	// 要素数5の配列を宣言
//	int arr[5];
//	int num;
//	int i;
//
//	for (i = 0; i < 5; i++) 
//	{
//		printf("input number:");
//		scanf_s("%d", &num);
//		arr[i] = num;
//	}
//
//	for (i = 0; i < 5; i++)
//	{
//		printf("%d\n", arr[i]);
//	}
//}


/************************
*		100_20			*
************************/

//int main(void) 
//{
//	int fir_num;
//	int sec_num;
//
//	printf("input 1st value:");
//	scanf_s("%d", &fir_num);
//
//	printf("input 2nd value:");
//	scanf_s("%d", &sec_num);
//
//
//	printf("result: %d\n", fir_num / sec_num);
//
//	printf("result: %d\n", (fir_num / sec_num) * sec_num);
//
//}


/************************
*		100_21			*
************************/


//int main(void) 
//{
//
//	int num;
//
//	printf("input number:");
//	scanf_s("%d", &num);
//
//	if( (5 < num) && (num < 20))
//	{
//		printf("OK");
//	}
//
//}


/************************
*		100_25			*
************************/

//int main(void)
//{
//	int num;
//
//	printf("input number:");
//	scanf_s("%d", &num);
//
//	if( num < -10 )
//	{
//		printf("range 1");
//	}
//	else if ( (-10 <= num) && (num < 0))
//	{
//		printf("range 2");
//	}
//	else
//	{
//		printf("range 3");
//	}
//
//}


/************************
*		100_26			*
************************/

//int main(void)
//{
//	int num;
//	char flg = 't';
//
//	while ('t')
//	{
//		printf("\ninput number:");
//		scanf_s("%d", &num);
//
//		switch (num)
//		{
//		case 1:
//			printf("one");
//			break;
//		case 2:
//			printf("two");
//			break;
//		case 3:
//			printf("three");
//			break;
//		default:
//			printf("others");
//			break;
//		}
//	}
//}


/************************
*		100_27			*
************************/

//int main(void) 
//{
//	int num;
//	int flg = 1;
//	int i;
//	int sum_num = 0;
//
//	printf("\ninput number:");
//	scanf_s("%d", &num);
//
//	if (num <= 0) {
//		sum_num = 0;
//		printf("\nsum = %d", sum_num);
//		return;
//	}
//
//	for( i = 1; i <= num; i++)
//	{
//		sum_num += i;
//		//int arr[sizeof(num)] = i;
//	}
//	printf("\nsum = %d", sum_num);
//
//}


/************************
*		100_28			*
************************/

//int main(void)
//{
//	int num;
//	int kaijyo = 1;
//	printf("input number:");
//	scanf_s("%d", &num);
//
//
//	if (num <= 0)
//	{
//		printf("factorial = 1");
//	}
//	else
//	{
//		for (int i = 1; i <= num; i++)
//		{
//			kaijyo *= i;
//		}
//
//		printf("factorial = %d", kaijyo);
//
//	}
//
//}


/************************
*		100_30			*
************************/


//int main(void) 
//{
//	int num;
//
//	printf("input number:");
//	scanf_s("%d", &num);
//
//	if (num >= 0)
//	{
//		for (int i = 0; i < num; i++)
//		{
//			printf("*");
//		}
//		
//		printf("\n");
//		
//	}
//}


/************************
*		100_31			*
************************/

//int main(void)
//{
//	int num;
//	printf("input number:");
//	scanf_s("%d", &num);
//
//	if ( 0 <= num )
//	{
//		for (int i = 1; i <= num; i++)
//		{
//			printf("*");
//
//			if (i % 5 == 0)
//			{
//				printf(" ");
//			}
//		}
//
//		printf("\n");
//
//	}
//
//}

/************************
*		100_32			*
************************/

//int main(void)
//{
//	int num;
//	int i;
//
//	printf("input number:");
//	scanf_s("%d", &num);
//
//	if ( 0 <= num )
//	{
//		for (i = 1; i <= num; i++)
//		{			
//			if (i % 5 == 0)
//			{
//				printf("bar\n");
//			}
//			else
//			{
//				printf("%d\n", i);
//			}
//		}
//
//		printf("\n");
//
//	}
//
//}


/************************
*		100_33			*
************************/

//int main(void)
//{
//	int num;
//	int i;
//
//	printf("input number:");
//	scanf_s("%d", &num);
//
//	if ( 0 <= num )
//	{
//		for (i = 1; i <= 9; i++)
//		{			
//			if (i == num)
//			{
//				printf("");
//			}
//			else
//			{
//				printf("%d\n", i);
//			}
//		}
//
//		printf("\n");
//
//	}
//
//}


/************************
*		100_34			*
************************/

//int main(void)
//{
//	int num;
//	int i;
//
//	printf("input number:");
//	scanf_s("%d", &num);
//
//	if ( 0 <= num )
//	{
//		for (i = 1; i <= 9; i++)
//		{			
//			if ((i != num) && (i != (num + 1)))
//			{
//				printf("%d\n", i);
//			}
//		}
//
//		printf("\n");
//
//	}
//
//}


/************************
*		100_35			*
************************/

//int main(void)
//{
//	int num;
//	int i;
//	int arr[10] = { 3, 7, 0, 8, 4, 1, 9, 6, 5, 2 };
//
//	printf("input number:");
//	scanf_s("%d", &num);
//
//	printf("array[%d] = %d", num, arr[num]);
//
//}


/************************
*		100_36			*
************************/

//int main(void)
//{
//	int index1;
//	int index2;
//	int i;
//	int arr[10] = { 3, 7, 0, 8, 4, 1, 9, 6, 5, 2 };
//
//	printf("input index1:");
//	scanf_s("%d", &index1);
//	printf("input index2:");
//	scanf_s("%d", &index2);
//
//	printf("%d * %d = %d", arr[index1], arr[index2], arr[index1] * arr[index2]);
//
//}


/************************
*		100_37			*
************************/


//int main(void)
//{
//	int num;
//	int arr[10] = { 3, 7, 0, 8, 4, 1, 9, 6, 5, 2 };
//	int value;
//
//	printf("input index:");
//	scanf_s("%d", &num);
//
//	// 要素番号が入力値の配列要素の値
//	value = arr[num];
//
//	// 参照した値を要素番号とする配列要素の値
//	printf("value = %d", arr[value]);
//
//}

```
