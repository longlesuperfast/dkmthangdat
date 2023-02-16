# dkmthangdat
dkm thang dat
int factorial(int num){

  int i;
  int ans = 1;
  if (num == 0){
  	ans = 1;
  	}
  	for (i=1; i <=num; i++)
  	{
  		ans*= (2*i+1);
	  }
return ans;
}



double fen(double x,double y, int n) { // You should complete this function
  // Write your statements here
 double s = 0;
 int j;
 for (j=0; j <= n; j++)
 {
 s += pow(-1,n)*((pow(x,2*j+2)*pow(y,2*j+1))/factorial(2*j+1));
 }
return s; //This statement must be changed 
 }
