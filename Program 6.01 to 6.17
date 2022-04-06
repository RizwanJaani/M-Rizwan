void main(){

//Program # 1

  int i = 0;
  while(i<5)
  {
    print("Pakistan");
    i++;
  }
  
//OUTPUT:
// Pakistan
// Pakistan
// Pakistan
// Pakistan
// Pakistan


//Program # 2

  int a = 1;
  while(a<=10)
  {
    print("$a");
    a++;
  }

//OUTPUT:
// 1
// 2
// 3
// 4
// 5
// 6
// 7
// 8
// 9
// 10


//Program # 3

 int c = 1;
  int sum = 0;
  while(c<=5)
  {
    print("$c");
    sum = sum + c;
    c=c+1;
  }
print('Sum is $sum');

//OUTPUT:
// 1
// 2
// 3
// 4
// 5
// Sum is 15


//Program # 4

  int c = 1;
  while(c<=5)
  {
    print("$c ${c*c}");
    c++;
  }
  
//OUTPUT:
// 1 1
// 2 4
// 3 9
// 4 16
// 5 25
  
  
//Program # 5
  
  int c = 1;
  print('Enter Number');
  int? n = int.parse(stdin.readLineSync()!);

  while(c<=10)
  {
    print("$n * $c = ${n*c}");
    c=c+1;
  }
 
  
//OUTPUT:
// Enter Number
// 5
// 5 * 1 = 5
// 5 * 2 = 10
// 5 * 3 = 15
// 5 * 4 = 20
// 5 * 5 = 25
// 5 * 6 = 30
// 5 * 7 = 35
// 5 * 8 = 40
// 5 * 9 = 45
// 5 * 10 = 50
  
  
//Program # 6

  int num3;
  print("Enter an integer:");
  int num1 = int.parse(stdin.readLineSync()!);
  int sum = 0;
  final num2 = num1;

  while(num1 !=0)
  {
    num3 = num1 % 10;

    if(num3 ==0){
      sum = sum + num1;
    }

    else{
      sum = sum + num3;
    }

    num1 = num1 ~/ 10;

  }

  print('The Sum of digits of $num2 = $sum');


/*
OUTPUT:
Enter an integer:
512
The Sum of digits of 512 = 8
*/

  
//Program # 7

  
  int num2 = 1;
  int num3 = 1;

  print("Enter an Number:");
  int num1 = int.parse(stdin.readLineSync()!);

  while(num2 <= num1)
  {
    num3 = num3 * num2;
    num2 = num2 + 1;
   
  }

  print('Factorial of  $num1 is $num3');

/*
OUTPUT:
Enter an Number:
5
Factorial of  5 is 120
*/

  
//Program # 8
  

  double pi = 3.141593;
  int degrees = 0;
  double radians;

  print("Degrees to Radians:");

  while(degrees <= 360)
  {
    radians = degrees *pi/180;
    print('$degrees   $radians');
    degrees += 10;
   
  }

/*
OUTPUT:
Degrees to Radians:
0   0.0
10   0.17453294444444445
20   0.3490658888888889
30   0.5235988333333333
40   0.6981317777777778
50   0.8726647222222221
.
.
340   5.934120111111111
350   6.108653055555555
360   6.283186
*/
  
  
//Program # 9
  
  double c = 2.0;
  double r = 1.0;

  while(c <= 100)
  {
    r = r +1.0/c;
    c = c + 2;
   
  }

  print('Result is $r');

  
/*
OUTPUT:
Result is 3.249602669164711
*/
  
  
//Program # 10
  
  
  num oddSum = 0;
  num evenSum = 0; 

  print('Enter a positive number');
  int num1 = int.parse(stdin.readLineSync()!);

  while(num1 >= 0)
  {
    if(num1% 2==0){
      evenSum = evenSum + num1;
    }

    else{
      oddSum = oddSum + num1;  
    }

    num1--;

  }

  print('The sum of even digits is $evenSum');
  print('The sum of odd digits is $oddSum');
  

/* 
OUTPUT:
Result is 3.249602669164711
*/

  
//Program # 11
  
  
  print('Enter a  number');
  int num1 = int.parse(stdin.readLineSync()!);

  num num2 = num1;
  num num3;
  num sum = 0;

  while(num2 != 0)
  {
    num3 = num2%10;
    sum = sum + (num3 *num3 *num3);
    num2~/=10;
    
  }
    if(sum == num1){
      print('$num1 is an Armstrong Number.');  
    }

    else{
      print('$num1 is not an Armstrong Number.');  
    }


/* 
OUTPUT:
Enter a  number
371
371 is an Armstrong Number.
*/
  
  
//Program # 12
  
  
  var sum;
  var avg;
  dynamic count;

  print('Enter positive number');
  int num = int.parse(stdin.readLineSync()!);

  var min = num;
  var max = num;

  while(num >= 0.0)
  {
    sum += num;
    count++;
  
    if(num > max){
      max = num;  
    }

    else if(num < min){
      min = num;
    }

    print('Enter positive number');
    
  }
  if(count ==0){
    print('No positive number entered.');
  }

  else{
    avg = sum / count;
    print('You entered $count numbers. ');
    print('Average $avg ');
    print('Minimum $min ');
    print('Maximum $max ');
  }



/* 
OUTPUT:
error
*/
  
  
  
}
