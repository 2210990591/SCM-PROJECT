# SCM-PROJECT
void main()
{
 while(1)
 {
  switch(Menu())
  {
   case 1:
  Bus();
  break;
   case 2:
  Cycle();
  break;
   case 3:
  Riksha();
  break;
   case 4:
  ShowDetail();
  break;
   case 5:
  Delete();
  break;
   case 6:
  exit(0);
   default :
 printf("\nInvalid choice:");

  }
  
 }
