/**
 ** Imran Siddique
 */

// write any needed import statements for system libraries
import java.awt.Color;

// Note the name of the class in the following line MUST
// match the name of the file. 
public class Proj2isiddi5
{
  
  public static void main (String[] args) 
  {
    System.out.println("Begin Java Exection");
    System.out.println("");


    // put your Java Program here
    // create a PICTURE on which the turtle is to live
    String filename;
    filename = FileChooser.pickAFile();
    Picture p1;
    p1 = new Picture ( filename );   // use the picture selected by pickAFile()
    
    // access/get my second picture
    filename = FileChooser.pickAFile();
    Picture p2;
    p2 = new Picture ( filename );   // use the picture selected by pickAFile()
    
    // verify the two images have the same width
    int w1 = p1.getWidth();
    int w2 = p2.getWidth();
    
    if ( w1 != w2 )
    {
      // one way for an error message
      System.out.println ("Error: the pictures have different widths.");
      
      // a better (i.e. preferred) way for an error message
      SimpleOutput.showError("Error: the pictures have different widths.");
      
      // forcing the program to quit/exit
      System.exit(1);
    }
    
    // call a method to perform the picture modification
    Picture resultPicture;
    resultPicture = superImpose ( p1, p2 );
    
    // display the PICTURE
    resultPicture.explore();
    
    // save the picture onto the file system
    //String filename2;
    //filename2 = FileChooser.pickAFile();
    //p.write ( filename2 );

    System.out.println("");
    System.out.println("End Java Exection");
  }   // end of main method
  
public static Picture superImpose ( Picture p1, Picture p2 )
{
    Pixel pix1;
  Pixel pix2;
  Pixel pix3;
  int x;
  int y;
    
  int width;
  width = p1.getWidth();
  System.out.println ( "The width of the picture is: " + width);
    
  int height = p1.getHeight ();
  System.out.println ( "The height of the picture is: " + height);
  
  // create my third image to store the superimposed result
  Picture p3 = new Picture ( width, height );
    
  for ( x = 0 ; x < width ; x = x + 1 )
  {
    for ( y = 0 ; y < height ; y = y + 1 )
    {
     // access the pixel at a specified corredinate location
      pix1 = p1.getPixel ( x, y );
      pix2 = p2.getPixel ( x, y );
      pix3 = p3.getPixel ( x, y );
       
      

                // modify the pixel 

               int redAmount;
      int greenAmount;
      int blueAmount;
      int redAmount1;
      int greenAmount1;
      int blueAmount1;

      // access the amount of red, green and blue at that pixel
      redAmount = pix1.getRed();
      greenAmount = pix1.getGreen();
      blueAmount = pix1.getBlue();
  
      int r2 = pix2.getRed();
      int g2 = pix2.getGreen();
      int b2 = pix2.getBlue();
        
      // manipulate the red, green and blue amounts
      redAmount = (redAmount )/1;
      greenAmount = (greenAmount)*0;
      blueAmount = (blueAmount )*0;
      
      
      redAmount1 = (redAmount + r2)*0;
      greenAmount1 = (greenAmount + g2)/1;
      blueAmount1 = (blueAmount + b2)/1;
      
        
      // store these new red, green and blue amounts back into the pixel
      pix3.setRed(redAmount);
      pix3.setGreen(greenAmount1);
      pix3.setBlue(blueAmount1);
    // use the return statement to send p3 back to main()
  
}
}
  return p3;
}
}

    
