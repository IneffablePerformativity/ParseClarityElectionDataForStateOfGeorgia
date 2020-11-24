# ParseClarityElectionDataForStateOfGeorgia
Analyzes Clarity Election Systems data for the whole state of Georgia

/*
 * ParseClarityElectionDataForStateOfGeorgia.cs
 *
 * which code and results I will archive at:
 * https://github.com/IneffablePerformativity
 * 
 * "To the extent possible under law, Ineffable Performativity has waived all copyright and related or neighboring rights to
 * The C# program Georgia2020ElectionFraud.cs and resultant outputs.
 * This work is published from: United States."
 * 
 * This work is offered as per license: http://creativecommons.org/publicdomain/zero/1.0/
 *
 * 
 * This application has mined out and presents solid proof of 2020 POTUS ELECTION FRAUD here:
 * LocationBeingStudied = "StateOfGeorgia"
 * 
 * 
 * This work can easily be tweaked for other locations that use CLARITY election system.
 * String constants matching Contest names must change;
 * How to distinguish Party may change.
 * GrainTag may change.
 * XML hierarchy may change
 * 
 * 
 * Goal: Parsing the "Clarity" type of 2020 Election data for State of Georgia.
 * via https://results.enr.clarityelections.com/GA/105369/web.264614/#/summary
 *  
 * Where I manually downloaded detailxml.zip, extracted detail.xml,
 * and renamed it: StateOfGeorgia-detail.xml
 * BTW, refetched it 2020-11-20 9:31 PM CT
 * 
 * to demonstrate any inverse republicanism::trump relationship
 * as was described for Milwaukee County Wisconsin in an article at:
 * https://www.thegatewaypundit.com/2020/11/caught-part-3-impossible-ballot-ratio-found-milwaukee-results-change-wisconsin-election-30000-votes-switched-president-trump-biden/
 * 
 * 
 * This application comes on the heels of my similar successful app,
 * which was also saved there on github.com/IneffablePerformativity:
 * ParseMilwaukeeCountyWiVotes.cs
 * That app showed a very clear 3% skew of POTUS race from lower races.
 * 
 * 
 * I am cloning an app that did the CLARITY data for state of Georgia.
 * But that data did NOT show POTUS race to be skewed from lower races,
 * so I did not proceed to the plotting step therein. Maybe this time.
 * I am now RE-cloning from a 2nd Gen app to re-do state of Georgia.
 * 
