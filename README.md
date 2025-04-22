# factorial
int a=0;
		int b=1;
		int fab=0;
		while(a<=10)
		{
			fab=a+b;
			a=b;
			b=fab;
			
			System.out.println(b);
		}
