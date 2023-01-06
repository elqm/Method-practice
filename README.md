# Method-practice
Method practice

[main 메소드]

public static void main(String[] args) {

		Calculator calc = new Calculator();
		calc.checkMethod();
		System.out.println("1부터 10까지의 합 : " + calc.sum1to10());
		calc.checkMaxNumber(10,20);
		System.out.println("10과 20의 합은 : " + calc.sumTwoNumber(10, 20));
		System.out.println("10과 5의 차는 : " +calc.minusTwoNumber(10, 5));
	}
  
  [non-static 메소드 ver1]  //입력 값에 전달인자와 매개변수만 사용

public void checkMethod() {

			System.out.println("메소드 호출 확인");
			return;
		}

		public int sum1to10() {
			int sum = 0 ;
			for(int i=1; i <= 10; i++) {
				sum += i;
			}
			return sum;

		}
		public void checkMaxNumber(int a, int b) {
//			System.out.print("첫번째 수를 입력받으시오 : ");
//			Scanner sc = new Scanner(System.in);
//			a = sc.nextInt();
//			System.out.print("두번째 수를 입력받으시오 : ");
//			b= sc.nextInt();
			int max = (a > b)? a: b;
			System.out.println("두 수 중 큰 수는 : " + max + "이다.");
		}
		public int sumTwoNumber(int a, int b) {
//			System.out.print("첫번째 수를 입력받으시오 : ");
//			Scanner sc = new Scanner(System.in);
//			a = sc.nextInt( );
//			System.out.print("두번째 수를 입력받으시오 : ");
//			b= sc.nextInt();
			return a + b;

		}
		public int minusTwoNumber(int a, int b) {
//			System.out.print("첫번째 수를 입력받으시오 : ");
//			Scanner sc = new Scanner(System.in);
//			a = sc.nextInt();
//			System.out.print("두번째 수를 입력받으시오 : ");
//			b= sc.nextInt();
			return a - b;
		}
    
    [non-static 메소드 ver1]  //입력 값에 전달인자와 매개변수만 사용

public void checkMethod() {

			System.out.println("메소드 호출 확인");
			return;
		}

		public int sum1to10() {
			int sum = 0 ;
			for(int i=1; i <= 10; i++) {
				sum += i;
			}
			return sum;

		}
		public void checkMaxNumber(int a, int b) {
//			System.out.print("첫번째 수를 입력받으시오 : ");
//			Scanner sc = new Scanner(System.in);
//			a = sc.nextInt();
//			System.out.print("두번째 수를 입력받으시오 : ");
//			b= sc.nextInt();
			int max = (a > b)? a: b;
			System.out.println("두 수 중 큰 수는 : " + max + "이다.");
		}
		public int sumTwoNumber(int a, int b) {
//			System.out.print("첫번째 수를 입력받으시오 : ");
//			Scanner sc = new Scanner(System.in);
//			a = sc.nextInt( );
//			System.out.print("두번째 수를 입력받으시오 : ");
//			b= sc.nextInt();
			return a + b;

		}
		public int minusTwoNumber(int a, int b) {
//			System.out.print("첫번째 수를 입력받으시오 : ");
//			Scanner sc = new Scanner(System.in);
//			a = sc.nextInt();
//			System.out.print("두번째 수를 입력받으시오 : ");
//			b= sc.nextInt();
			return a - b;
		}
