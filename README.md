# CSP-Processing-Arrays
Find Smallest Number Practice
var array1 = [1,3,4,6,7,6];
var array2 = [6,2,7,2,5,6,1,3,7];
var arrayRandom = [];
for (var i = 0; i < 10; i++) {
  appendItem(arrayRandom, randomNumber(0,100));
}

findMinVal(array1);
findMinVal(array2);
findMinVal(arrayRandom);

function findMinVal(list){
  
  console.log("Original:" + list);
  
  //What value should minVal start off as? Set its value before your loop.
  var minVal=101;
  
  for (var I = 0; I < list.length; I++) {
  
    //Update your minimum value on each iteration of the loop
    
  if (list[I]<minVal) {
    minVal = list[I];
  }
  }
  
  console.log("The smallest value in the array is: " + minVal);
}
