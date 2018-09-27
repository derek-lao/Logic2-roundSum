# Logic2-roundSum
Logic2-roundSum to test round10

public int round10(int n) {
  if (((n%10) < 5) && ((n%10) >= 0))
  {
    return n-(n%10);
  }
  if ((n%10 >=5) && ((n&10) <= 9))
  {
    return n+(10-(n%10));
  }
  return n;
}

System.out.println(round10(26))
