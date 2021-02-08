# biggerTwo
CodingBat Java Array-1 biggerTwo

public int[] biggerTwo(int[] a, int[] b) {
  
    int sumOfA = 0;
    int sumOfB = 0;
  
    sumOfA = a[0] + a[1];
    sumOfB = b[0] + b[1];
  
    if(sumOfA > sumOfB){
      return a;
    }
    else if(sumOfB > sumOfA){
      return b;
    }
    else if(sumOfA == sumOfB){
      return a;
    }
  
    return a;
  
  }
