# Automated System to Track and Identify Players from NBA Broadcast Videos

![Twitter Follow](https://img.shields.io/twitter/follow/DGrubes?style=social)  
![Website](https://img.shields.io/website?down_color=lightgrey&down_message=offline&up_color=blue&up_message=online&url=https%3A%2F%2Fwww.dirksfadeaway.com)

The Big Data boom in basketball began around 2013, when the NBA signed a groundbreaking deal with SportVu to install specialized cameras in all of its stadiums to track every single player as well as the ball at 25 frames per second. This provided unprecedented access to spatiotemporal data that would help inform important decisions for an NBA front office. The public basketball analytics community was just getting their feet wet with this vast amount of data when all this came to an abrupt halt in 2016-2017, and the data disappeared from NBA Stats.com. The NBA had signed a new deal with Second Spectrum which made this data completely proprietary. NBA organizations and top media companies now pay tens of thousands of dollars for this raw tracking data. This has prevented the public basketball analytics community from making progress in pushing the boundaries of interesting and innovative research. 

Our work proposes to build an web application which allows users to upload videos from a NBA broadcast and receive a reasonable approximation of player tracking and identification from each frame of the video which would be processed at 25 frames per second. Our application presents various modules which would form the pipeline - preprocessing video to only contain frames from the game (removing ads, close-ups, replays), player identification and tracking, automated tracking of important points on the court and finally ball tracking in a 3D coordinate plane. 

