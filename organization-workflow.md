# Organization workflow

The general workflow to organize a reading club session is as follows:

## For special sessions

Add an event to the [Conferences & Events](https://calendar.google.com/calendar/embed?src=sourced.tech_vnootou25lkv75a70l2qac65og%40group.calendar.google.com) public calendar as soon as the date is decided.

## 2 weeks before

- Create the next paper candidates issue.

    The corresponding issue template is almost good to go: it just requires setting the date of the next session in the title.

- Create the thread for the future session on [source{d} forum](https://forum.sourced.tech/) in the _source{d} Reading Club_ category. The following template can be used:

        [date=YYYY-MM-DD time=16:00:00 timezone="Europe/Madrid"] session topic is being determined in [this GitHub issue](Link to the issue)

        :clock4: The session lasts for one hour between [date=YYYY-MM-DD time=16:00:00 timezone="Europe/Paris"] and [date=YYYY-MM-DD time=17:00:00 timezone="Europe/Paris"]

        :world_map: The reading club happens [on-line on zoom](https://zoom.us/j/974346848) or in [source{d} office](https://goo.gl/maps/y6aUoBavAGEDWiaNA) in Madrid 

        :information_source: For more details, see our [repository](https://github.com/src-d/reading-club) on GitHub

- Archive last session and create the new one.

    PR a change to [src-d/reading-club](https://github.com/src-d/reading-club) club to put the previous session in the [Past papers](README.md#past-papers) section with the template

        - __YYYY.MM.DD__ [Title of the paper](url of the paper on GDrive). ([notes](Url of the notes on GDrive))
    
    And create the new session with the template

        - __YYYY.MM.DD__ at __4PM CET__: [TBD](url of the candidates issues)

## 1 week before

- Lock the candidate issue on GitHub

- Create and announce the poll in the discourse thread. You can follow this template:

        :ballot_box: It’s voting time! Feel free to vote for the papers that interest you the most :ballot_box:

        [poll type=multiple results=on_vote min=1 max=4]
        * [Title 1](Link 1)
        * [Title 2](Link 2)
        * [Title 3](Link 3)
        * [Title 4](Link 4)
        [/poll]

## 5 days before

- Pick the winner (most votes).

- Add the PDF of the paper to the [GDrive directory](https://drive.google.com/drive/u/1/folders/1cAzkDW_sXb49gRZvvhVvXu3Wi_84lQdn).

- Create a new notes document in the [`Notes` dir on GDrive](https://drive.google.com/drive/folders/1IQ7-wOea32lDkd69-NcLw5xYB74oH6rJ).

    When we have time we link the authors to their respective homepages and include relevant links (code, data, etc).

- PR a change with the next session to this repository's [readme](README.md#next-sessions).

    We use the following template:

        - __YYYY.MM.DD__ at __4PM CET__: [Title of the paper](url of the pdf on GDrive). We take notes in a [public GDoc](url of the notes on GDrive), you are very welcome to ask questions or give thoughts in it!

-  Announce it in the discourse thread with a link to the paper, its abstract, and the notes in the original post. In particular, you can use this snippet for the notes:

        :writing_hand: We take notes and prepare the discussion in a [public GDoc](https://docs.google.com/document/d/1djU2TvnuKx-lPmFGSye1gkMGtDVDBNW9gDbE811DELk/edit), you are very welcome to ask questions or share your thoughts in it


## A few hours before

Announce the session on discourse, optionally with an [It's almost](https://itsalmo.st/) link and with a reminder of the zoom ID.

## Ten minutes before

- Launch the [zoom meeting](https://github.com/src-d/reading-club#where).
