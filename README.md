# UcVeDortTamBolmeOrtalama
www.patika.dev
--------------------------


public class SayılarınOrtlaması 
{

	public static void main(String[] args) 
	{
		System.out.println("Bir sayi giriniz");
		Scanner scanner = new Scanner(System.in);
		int sayi = scanner.nextInt();
		int toplam =0;
		double ortalama;
		int sayaç =0;
		for(int i=0; i<sayi; i++)
		{
			if(i%3 ==0 && i%4 ==0)
			{
				toplam = toplam +i;
				sayaç++;
			}
		
		}
		ortalama = toplam / sayaç;
		System.out.println(ortalama);

	}

}
