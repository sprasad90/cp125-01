# cp125-01package cp120.assignments.assignment001;

import edu.uweo.javaintro.tools.Turtle;

public class Bubbles
{
    public static void main( String[] args )
    {
        Turtle toots   = new Turtle();
        toots.switchTo( Turtle.GREEN );
        toots.move( 0, -128 );
		
        toots.fillCircle( 128 );
        toots.move( 0, 192 );
        toots.fillCircle( 64 );
        toots.move( 0, 96  );
        toots.fillCircle( 32 );
        toots.move( 0, 48 );
        toots.fillCircle( 16 );
        toots.move( 0, 24 );
        toots.fillCircle( 8 );
        toots.move( 0, 12 );
        toots.fillCircle( 4 );
    }

}
