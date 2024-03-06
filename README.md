# taex-#include <stdio.h>
#include <conio.h>

void main()
{
	int n, i, j, d;#include <stdio.h>
#include <conio.h>

void main()
{
	int n, i, j, d;
	clrscr();
	printf("Nhap gia tri N : ");
	scanf("%d", &n);
	printf("Cac so nguyen to khong vuot qua %d la :\n", n);

	for (d = 0, i = 2; i <= n; i++)
	{
		for (j = 2; j <= i / 2; j++)
			if (i % j == 0) break;
		if (j == i / 2 + 1)
		{
			d++;
			printf(" %d", i);
		}
	}
	printf("\nTong so co %d so nguyen to", d);
	getch();
}
		for (j = 2; j <= i / 2; j++)
			if (i % j == 0) break;#include <stdio.h>
#include <conio.h>

void main()
{
	int n, i, j, d;
	clrscr();
	printf("Nhap gia tri N : ");
	scanf("%d", &n);
	printf("Cac so nguyen to khong vuot qua %d la :\n", n);

	for (d = 0, i = 2; i <= n; i++)
	{
		for (j = 2; j <= i / 2; j++)
			if (i % j == 0) break;
		if (j == i / 2 + 1)
		{
			d++;
			printf(" %d", i);
		}
	}
	printf("\nTong so co %d so nguyen to", d);
	getch();
}
		if (j == i / 2 + 1)
		{
			d++;
			printf(" %d", i);
		}
	}
	printf("\nTong so co %d so nguyen to", d);
	getch();
}
