# Hello--People what wrong with this codes
 public static void plusMinus(List<Integer> arr) {
    // Write your code here
       float plusCount=0;
       float minusCount=0;
       float zeroCount=0;
       String stringValue;
    arr = new ArrayList<>();
   
          int[] array = new int[arr.size()];
   
     int n = arr.size();
    for(int i=0;i<n;i++) {
        arr.add(i);
         array[i] = arr.get(i);
         
         if(array[i]>0){
            
             //plusCount++;
             plusCount=plusCount+1;
         }
         else if(array[i]<0){
             //minusCount++;
             minusCount=minusCount+1;
         }
         else{
             //zeroCount++;
             zeroCount=zeroCount+1;
         }
        System.out.printf("%1.6f",plusCount/n);
        System.out.printf("%1.6f",minusCount/n);
        System.out.printf("%1.6f",zeroCount/n);
        System.out.println(); 
    }
    
    }

}
