# codigo-solucion

package matricesinv;
public class MatricesInv 
{
    public static void main(String[] args) 
    {
        int cont=0;
        for(int a=0;a<6;a++)
        {
           for(int b=0;b<6;b++)
            {
              for(int c=0;c<6;c++)
                {
                   for(int d=0;d<6;d++)
                        {   
                               if((a*d-c*b)%6!=0)
                               {
                               cont++;
                               }
                        }     
                }     
            }
        }
        System.out.println("La cantidad de matrices invertibles en Z6 es "+cont);
        
        
        cont=0;
        for(int a=0;a<9;a++)
        {
           for(int b=0;b<9;b++)
            {
              for(int c=0;c<9;c++)
                {
                   for(int d=0;d<9;d++)
                        {   
                               if((a*d-c*b)%9!=0)
                               {
                               cont++;
                               }
                        }     
                }     
            }
        }
        System.out.println("La cantidad de matrices invertibles en Z9 es "+cont);
        
        
        cont=0;
        for(int a=0;a<26;a++)
        {
           for(int b=0;b<26;b++)
            {
              for(int c=0;c<26;c++)
                {
                   for(int d=0;d<6;d++)
                        {   
                               if((a*d-c*b)%26!=0)
                               {
                               cont++;
                               }
                        }     
                }     
            }
        }
        System.out.println("La cantidad de matrices invertibles en Z26 es "+cont);
    }
    
}
