# Punto-Q.5.11
Further Analysis
Rearrange the subplots shown in Figure 5.72 in at least two other ways.


>> % plot for parts (e)

>> clf

>> subplot(2,1,1)

>> Y12 = sin(X-pi/2);

>> Y13 = sin(X-pi);

>> Y14 = sin(X-3*pi/2);

>> plot(X,Z,X,Y12,X,Y13,X,Y14)

>> ylabel(‘Y11, Y12, Y13, Y14’)

>> title(‘Sin(X), Sin(X-pi/2), Sin(X-pi), Sin(X-3pi/2)’)

>> subplot(2,1,2)

>> % plots for part (f)

>> Y16 = -Z;

>> Y17 = 2.*Z;

>> Y18 = -Y17;

>> plot(X,Z,X,Y16,X,Y17,X,Y18)

>> title(‘Sin(X), -Sin(X), 2Sin(X), -2Sin(X)’)

>> xlabel( ‘X’ ),

>> ylabel( ‘Y15, Y16, Y17, Y18’ )

>> The plots for parts e and f are shown in Figure 5.73.

>> % plots for part (g)

>> plot (cos(3*X), sin(4*X));

>> axis ([-2 2 –1.5 1.5])

>> title (‘Cos(3X) Vs Sin(4X)’)

>> xlabel (‘X’), ylabel (‘Magnitude Sin(4X)’)
