//// 1)saitleri hesablayan
//class Program
//{
//    static void Main()
//    {  
//        string text = "Ex Methods";
//        int count = 0;


//        for (int i = 0; i < text.Length; i++)
//        {

//            char c = text[i];
//            if (c == 'a' || c == 'e' || c == 'i' || c == 'o' || c == 'u' ||
//                c == 'A' || c == 'E' || c == 'I' || c == 'O' || c == 'U')
//            {
//                count++; 
//            }
//        }


//        Console.WriteLine("Number of vowels: " + count);
//    }
//}


//2)endirim qiymet
//class Program
//{
//    static void Main()
//    {

//        decimal price = 200.00m;
//        decimal discountPercentage = 40.00m;


//        decimal discountAmount = price * (discountPercentage / 100);


//        decimal discountedPrice = price - discountAmount;


//        Console.WriteLine("Original Price: " + price);
//        Console.WriteLine("Discounted Price: " + discountedPrice);
//    }
//}



//3)student crud
class Program
{
    // Define the Student class
    class Student
    {
        public int ID { get; set; }
        public string Name { get; set; }
        public int Age { get; set; }
    }      
