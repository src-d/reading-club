# Organization workflow

The general workflow to organize a reading club session is as follows:

## For special sessions

Add an event to the [Conferences & Events](https://calendar.google.com/calendar/embed?src=sourced.tech_vnootou25lkv75a70l2qac65og%40group.calendar.google.com) public calendar as soon as the date is decided.

## 2 weeks before

- Create the next paper candidates issue.

    The corresponding issue template is almost good to go: it just
    requires setting the date of the next session in the title.

- Archive last session and create the new one.

    PR a change to
    [src-d/reading-club](https://github.com/src-d/reading-club) club
    to put the previous session in the [Past
    papers](README.md#past-papers) section with the template

        - __YYYY.MM.DD__ [Title of the paper](url of the paper on GDrive). ([notes](Url of the notes on GDrive))
    
    And create the new session with the template

        - __YYYY.MM.DD__ at __4PM CET__: [TBD](url of the candidates issues)

## 1 week before

Create a poll to decide on the next paper.

The poll should be created on the [#reading-club community Slack
channel](https://sourced-community.slack.com/messages/CCLPL1WQH). It
uses the poll widget:

    /poll "What papers would you like to study during next session, on the xxth of xxxxx?" "Title1: url1" "Title2: url2"

## 5 days before

- Pick the winner (most votes) and announce it on [community slack
  #reading-club
  channel](https://sourced-community.slack.com/messages/CCLPL1WQH).

- Add the PDF of the paper to the [GDrive
  directory](https://drive.google.com/drive/u/1/folders/1cAzkDW_sXb49gRZvvhVvXu3Wi_84lQdn).

- Create a new notes document in the [`Notes` dir on
  GDrive](https://drive.google.com/drive/folders/1IQ7-wOea32lDkd69-NcLw5xYB74oH6rJ).

    When we have time we link the authors to their respective
    homepages and include relevant links (code, data, etc).

- PR a change with the next session to this repository's
  [readme](README.md#next-sessions).

    We use the following template:

        - __YYYY.MM.DD__ at __4PM CET__: [Title of the paper](url of the pdf on GDrive). We take notes in a [public GDoc](url of the notes on GDrive), you are very welcome to ask questions or give thoughts in it!

## A few hours before

Announce the session on the community slack.

## One hour before

Announce the session on the community slack again.

## Ten minutes before

- Launch the [zoom
  meeting](https://github.com/src-d/reading-club#where).

- Announce the session on the community slack again with the Zoom
  meeting ID.
