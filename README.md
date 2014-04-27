Random-Number---LAB--3-WEEK-10
==============================

Random Number lab #3 week 10


//  BY REINA OLARTE 
//  RANDOM NUMBER  CMS 112-  LAB  #  3  WEEK 1O


public class RandomNumber 
{
	int computerNumber;
	int LowNumber;
	int HighNumber;
	public RandomNumber(int high)
	{
		HighNumber = high;
	}
	public RandomNumber(int low, int high)
	{
		HighNumber = high;
		LowNumber = low;
	}
	public int getHighNumber()
	{
		return HighNumber;
	}
	public int getLowNumber()
	{
		return LowNumber;
	}
	public int GetANumber()
	{
		computerNumber = (0 + (int)(Math.random() * HighNumber));
		return computerNumber;
	}
	public int GetANumber(int low, int High)
	{
		computerNumber = (low + (int)(Math.random() *(High-low)));
		return computerNumber;
	}
	public int GetANumber(int High)
	{		
		computerNumber = 0 + (int)(Math.random() *High);
		return computerNumber;
	}
	public int setLowNumber(int low)
	{
		LowNumber = low;
		return LowNumber;
	}
	public int setHighNumber(int high)
	{
		HighNumber = high;
		return HighNumber;
	}
}
