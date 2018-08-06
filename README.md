# SuffolkChessPGNs
PGN files for the using on the website: www.suffolkchess.org.uk

The PGN files in this repository are for use on the Suffolk Chess Website.
That website plays the PGN files using the ChessBase PGN Player

Details of the player are available here: https://schach.de/howto/embedtools

----------------------------------------------------------------------------------------------

How include whole games
=======================

Where you want the player to appear, add the following tag:

    <div class="cbreplay" data-url="Path/to/PGN/File.pgn">
    </div>

Alternatively, you can omit the data-url property and include the entire PGN text like this:

    <div class="cbreplay">
      [Event "Corus"]
      [Site "Wijk aan Zee"]
      [Date "2003.01.18"]
      [Round "6"]
      [White "Ivanchuk, Vassily"]
      [Black "Anand, Viswanathan"]
      [Result "1/2-1/2"]
      1. c4 Nf6 2. d4 e6 3. Nf3 b6 4. g3 Ba6 5. Nbd2 Bb4
      6. a3 Bxd2+ 7. Nxd2 Bb7 8.Nf3 d5 9. cxd5 Bxd5 10. Bg2 O-O 11. O-O Nbd7
      12. Bf4 c5 13. dxc5 1/2-1/2
    </div>


By the Way
==========

The theme of Suffolk Chess has been edited so that all pages include the following three lines of code:

    <link rel="stylesheet" type="text/css" href="https://pgn.chessbase.com/CBReplay.css"/>
    <script src="https://pgn.chessbase.com/jquery-3.0.0.min.js"></script>
    <script src="https://pgn.chessbase.com/cbreplay.js" type="text/javascript"></script>

So although the guide from ChessBase says you need to add these lines, we've already done that for you.

