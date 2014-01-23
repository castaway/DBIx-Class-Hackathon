Notes/Status
============

Jess' random planning notes go here, they will change, feel free to read/ask about:

* Dates upcomming events
    * 2014-01-25...26 Perl Oasis West
    * 2014-02-01...02 FOSDEM
    * 2014-03-13...16 QA Hackaton
    * 2014-03-26...28 PerlWorkshop Germany
    * 2014-01-00...00 PerlWorkshop DC-Baltimore ???
    * 2014-04-20...21 Easter
    * 2014-04-25...25 PerlWorkshop Netherlands
    * 2014-05-16...18 PerlWorkshop Poland
    * 2014-05-20...21 PerlWorkshop Czhech ???
    * 2014-06-13...14 PerlWorkshop France ???
    * 2014-06-23...25 YAPC::NA::Orlando (FL) ???
    * 2014-07-00...00 YAPC::CN::Beijing/Shanghai ???
    * 2014-08-22...24 YAPC::EU::2014 Sofia ????

    * above list has been exctracted from the Act test-server

* Hall / community hall etc hire:
    * Village halls fairly cheap? (Deposit? see Market Lavington)
    * Distance from travel hub to consider, eg train station/airport?
    * Hall preferable to pub function room

* Network/amenities:
    * Get a server, put CPAN on it, give people accounts and allow them to github pull etc their stuff before we go
    * Attach a wifi access point, that's our network
    * We may or may not find a hall with networking
    * Tables, chairs - included in hall?

* Food etc:
    * Provide breakfast, drinks, snacks/lunch
    * Dinner - local pub or similar?
    * = have it in town with access to shops/pub, not too far from hotels?

* Theme:
    * DBIx::Class usage/tools/docs/tests etc?

* Notes?
    * single day? no accommodation / overnighting needed?
    * BBQ food? (decent time of year)
    * co-working space - Basepoint etc?
    * Wendy/Liz?
    * Swag? stickers or something
    * nearby shopping for forgotten things
```
14:10 < mst> connect said server to the internet
14:10 < mst> QoS the living fuck out of it
14:10 < mst> http? sure. git? sure. ssh? OH I'M SORRY HERE'S 1200 BAUD
14:10 < mst> ... with an exception fot git@github.com
```

* Budget:
    * Venue: 120-150/day
    * Food:
        * Breakfast (Pilgrim centre eg) 2.50/head (bap + contents, coffee/tea extra)
        * Lunch (Pilgrim centre eg) 4.90/head
    * Server/Local wifi - Jess/James to have/build?
    * ??

*  Possible locations:
    * Purton? min £13.50/hr one-off event
    * Bishopstone? http://www.bishopstone.info/Joinin/ClubsSocieties/BishopstoneVillageHall/Charges.aspx - 100/day
    * Stratton community hall, £325/7pm-11:30pm (incl. bar!)
    * Meadowcroft? £10/hr - no other details
    * Wanborough - http://www.wanborough.info/vhall_2.htm
    * SBC - BroadGreen etc: no prices online: http://www.swindon.gov.uk/cm/cm-halls/cm-halls-find/Pages/cm-halls-find-broadgreen.aspx - 10:00am-10:30pm
etcetc
    * wroughton - http://www.ellendunehallwroughton.co.uk/index.php?option=com_content&view=article&id=54&Itemid=59
    * arkells: http://www.arkells.com/contact.php - incl. brewery tour!
    * madison: http://www.madison-hotel.co.uk/
    * pilgrim centre, small rm: 62.50/4 hour session, or £15.625/hr: http://www.pilgrimcentre.co.uk/standard.htm , large rm 22.125/hr (standard) .. community/voluntary: 8.125hr(97.5/day) or 11.5/hr (138/day) - chairs/tables included, other amenities available for fee. 9am-9pm, can be longer if arranged.
    * holiday inn (west): http://www.expressswindon.co.uk/holiday-inn-express-swindon-meetings/meetings.html
    * STR old town: http://swindontrainingrooms.co.uk/roomstohire-swindon-training-and-meeting-rooms.html (front page claims £25/day, page says £95+VAT!) - replied via email, £25 is a 2-hour session thing
    * county ground: http://www.swindoncountyground.com/suites/the-chairmans-suite
    * bible soc westlea: http://www.biblesociety.org.uk/about-bible-society/contact-us/meeting-room-hire/ £85/day..
    * http://www.vas-swindon.org/meetingrooms.html £65/day, but only weekdays 9:30 - 4:30pm

* Hackathon content
  * DBIC core
    * Lazy schema loading
    * Join node options (http://lists.scsys.co.uk/pipermail/dbix-class/2014-January/011582.html)
    * Fold result inflator into the resultset parser (massive speedups)
    * Replace all uses of Moose with Moo (dbicadmin + Replication), write a Moo-compatible shared Type-library to use in the migration
    * 
    * Extra issues/tickets locked in ribasushi's head (will be available in-repo way before hackaton commences)
  * DBIC core docs
    * Agree on direction of docs, good separation of cookbook material, better organization
    * Figure out what to do with multiple conflicting doc-branches
  * DBIC core tests
    * Manual, graphviz diagram, etc on how to start with testwriting
    * Extra test csses in the CI environment  (extra RDBMS, ODBC, JDBC) 
    * Multi-rdbms tests (based on ongoing work on DBI::Tet)
...

* Other hackathons
    * http://www.yapceurope.org/events/hackathons.html
    * http://act.qa-hackathon.org/qa2014/budget.html

* Sponsors
    * sjn?
    * Wendy/Liz?
    * Shadowcat?

* Marketing(!)
    * Lanyrd
