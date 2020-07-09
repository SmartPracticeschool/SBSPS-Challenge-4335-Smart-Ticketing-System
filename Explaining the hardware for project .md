# SBSPS-Challenge-4335-Smart-Ticketing-System
Milestone Epsilon: Hardware for the project

 The last milestone of this project is making the hardware for the project. The components required for this project are
•	RFID Tag
•	RFID Card Reader
•	Arduino Mega 2560
•	Jumper wires (Male to male and Male to female)
•	LCD Display
The RFID Tag is a card which is used by a passenger to board bus. The RFID card is a transponder and the RFID Card Reader is the receiver. The RFID Card Reader is connected to an Arduino Mega 2560 which will process the data. The method of processing will be described in the upcoming lines. First when a person taps his card onto the RFID Card Reader the card reader’s input is fed into the Arduino mega 2560 which will read the card number and it starts checking for the name of the passenger linked with that card number and gets his balance information. After that using the GPS location at which the card is tapped it gets the location at which the passenger is embarking. After that when the passenger disembarks, he will again tap the card onto the RFID card reader the system gets the card info and it also gets his disembarking point and using the fare chart the money will be deducted from his balance. Another feature of this RFID Card usage is that due to coronavirus many people post covid-19 will prefer to travel by his/her own vehicle because when more passengers get into the bus at the same time they will not follow social distancing and it becomes a easier way to spread the virus. This system uses the IN-OUT method where the number of passengers can be identified inside the bus and can be displayed in the next bus stop so that the passenger in the next bus stop can know the information about the number of passengers currently inside the bus because post covid-19 government will pass a rule that only limited number of passengers should be inside a bus during the travel.
