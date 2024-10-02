Create a folder C://Applications/Mirth/csvs & C://Applications/Mirth/hl7Messages. You can then use the testPatientData.csv or 
other similiar patient information csvs. The 'CSVInput' channel will then pick up the csvs provided in C://Applications/Mirth/csvs.
Then split them into individual hl7 messages to the 'ListeningChannel'. This channel will then output the hl7 message as a txt file in 
C://Applications/Mirth/hl7Messages.
