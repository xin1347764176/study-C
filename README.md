# -c
1！+2！+...+10！


	int a, i, sum, k, sum2;
	sum2 = 1;
	sum = 0;
	k = 1;
	for (i = 1; i <= 10; i++) {
		sum2 *= i;
		sum += sum2;
		printf("%d\n", sum);

	}
	printf("%d", sum);
	return 0;
}
