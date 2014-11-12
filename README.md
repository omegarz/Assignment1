Assignment1
===========

Test Repository. Everybody write a change and push it back to the repository.

//Omegar has accessed this.

public class CPSC112 {

		static final int size = 5;
		public static void main(String[] args)
		{
			printHead();
			angleRight();
			angleLeft();
			angleRight();
			angleLeft();
			printTail();
	
		}
			
		
		
		public static void printTopHead()
		{
		
			for (int q = 1; q <= (((size + 1)/ 2) -2); q++) {
				System.out.print(" ");
			}
			
			System.out.println("/||\\");
			
			for (int line = 1; line <= (((size - 1)/2) - 2); line++)  {
				for (int k = (((size + 1)/2)-3); k >= line; k--) {
					System.out.print(" ");
					
				}
					
				
				System.out.print("/");
				
				for (int h = -2; h <= ((line*2)-1); h++)  {
					System.out.print(" ");
					
				}
				
				System.out.println("\\");	
	
			}
			
			System.out.print("/");
			for (int y = 1; y <= (((size - 1)/2)-2) ; y++)  {
				System.out.print(" ");	
		
			}
			
			System.out.print("|  |");
			for (int y = 1; y <= (((size - 1)/2)-2) ; y++)  {
				System.out.print(" ");	
		
			}
			
			System.out.println("\\");	
			
		
		}
				
		public static void printNeck()
		{
			System.out.print("\\");
			for (int i = 1; i <= (size - 1); i++)  {
				System.out.print(" ");
					
			}
				
			System.out.println("/");
			System.out.print(" ");
			System.out.print("\\");
			for (int i = 1; i <= (size - 3); i++)  {
				System.out.print(" ");
				
			}
			
			System.out.println("/");
			System.out.print(" ");
			System.out.print("|");
			
			for (int i = 1; i <= (size - 3); i++)  {
				System.out.print(" ");
				
			}
		
			System.out.println("|");
			System.out.print(" ");
			System.out.print("|");
			
			for (int i = 1; i <= (size - 3); i++)  {
				System.out.print(" ");
				
			}
		
			System.out.println("|");
			
			System.out.print("/");
			for (int i = 1; i <= (size - 1); i++)  {
				System.out.print(" ");
				
			}
			
			System.out.println("\\");
		}		
		
		public static void printHead()
		{
			printTopHead();
			printNeck();
			
		}
		public static void angleRight() 
		{
			for (int line = 1; line <= 5; line++)  {
				for (int i = 1; i <= (line - 1); i++)  {
					System.out.print(" ");
				}	
				
				System.out.print("\\");
				for (int j = 1; j <= size; j++)  {
					System.out.print(" ");
				
				}
					
				System.out.println("\\");

			}
		}	
			
			
		public static void angleLeft()
		{
			
			for (int line = 1; line <= 5; line++)  {
				for (int i = 5; i >= (line + 1); i--)  {
					System.out.print(" ");
				
				}
				
				System.out.print("/");
				for (int j = 1; j <= size; j++)  {
					System.out.print(" ");
				
				}
					
				System.out.println("/");
				
			}			
		}
		
		public static void printTail()
		{
		
			for (int line = 1; line <= ((size + 1) / 2); line++)  {
				for (int i = 1; i <= (line - 1); i++)  {
					System.out.print(" ");
				
				}
				
					System.out.print("\\");
					
				for (int j = size; j >= (2 * (line)); j--)  {
					System.out.print(" ");
				
				}
				
					System.out.println("/");
				
				}
		
		}	
		
	}
