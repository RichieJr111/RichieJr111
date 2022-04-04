int[][] twoD_arr = new int[5][10];

for(int b = 0; b < twoD_arr.Length(); b++)
{
  for(int c = 0; c < twoD_arr[0].Length(); c++)
  {
    switch(b)
    {
      case 0:
        twoD_arr[0][0]++;
        twoD_arr[0][3]++;
        twoD_arr[0][5]++;
        twoD_arr[0][6]++;
        twoD_arr[0][7]++;
        twoD_arr[0][9]++;
        break;
      case 1:
        twoD_arr[1][0]++;
        twoD_arr[1][3]++;
        twoD_arr[1][6]++;
        twoD_arr[1][9]++;
        break;
      case 2:
        twoD_arr[2][0]++;
        twoD_arr[2][1]++;
        twoD_arr[2][2]++;
        twoD_arr[2][3]++;
        twoD_arr[2][6]++;
        twoD_arr[2][9]++;
        break;
      case 3:
        twoD_arr[3][0]++;
        twoD_arr[3][3]++;        
        twoD_arr[3][6]++;        
        break;
      case 4:
        twoD_arr[4][0]++;
        twoD_arr[4][3]++;
        twoD_arr[4][5]++;
        twoD_arr[4][6]++;
        twoD_arr[4][7]++;
        twoD_arr[4][9]++;
        break;
    }
  }
}

for(int i = 0; i < twoD_arr.Length(); i++)
{
  System.out.println();
  for(int a = 0; a < twoD_arr[0].Length(); a++)
  {
    if(twoD_arr[i][a] == 1)
    {
      System.out.print("O");
    }
    else if(twoD_arr[i][a] == 0)
    {
      System.out.print(" ");
    }
  }
}
