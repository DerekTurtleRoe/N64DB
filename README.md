# Turtle's N64DB

### A free and open-source database of Nintendo 64 software information.

### This will include official Nintendo releases, as well as reproduction, homebrew, and other unofficial releases.

#### What is this?
Turtle's N64DB is a free and open-source database of Nintendo 64, Nintendo 64 disk drive, iQue, and Aleck64 software.

#### Why make this?

This is intended to replace the inaccurate, outdated, and conflicting databases that currently exist. This will also serve as a way to correctly identify games using multiple methods for redundancy. The Nintendo 64 (and related systems) has some unique features in the ROM that can make it difficult to determine the difference between 2 ROM files. This is what makes the GoodN64 database somewhat inaccurate. The No-Intro database is much more accurate (and updated fairly frequently), but it only has verified and official releases. It also contains some prototypes/beta/alpha/review samples/etc, but I would like to have everything in one database (EXCLUDING BAD DUMPS). That note is important, because bad dumps are often lumped in with the good dumps depending on certain features.

Bad dumps sometimes do still work, but can have any number of issues, including corrupted text, corrupted graphics, corrupted sound, strange crashes and bugs, performance differences, and many other odd behaviors.

#### What systems does this cover exactly?

- Nintendo 64
- Nintendo 64 disk drive
- iQue
- Aleck64
- Virtual Console extracted Nintendo 64 ROMs

#### How is this database generated?

Using a few free and open-source tools made by the community, and a LOT of hand-written "extra stuff". Some of the work is done by two main applications.

The first is [ROM64 by Mike Roach](https://github.com/mroach/rom64). This is a Nintendo 64 ROM information tool. This provides some of the data used in the database.

The other tool is [romjudge by Jason Benaim](https://github.com/jkbenaim/romjudge). This is also a Nintendo 64 ROM information tool. This provides some of the data, including checking for typical PI (peripheral interface) timings, checking for a correct file size, checking the CRCs, and checking the IPL3/bootcode.

The rest is manually done by me, such as gathering the information about Expansion Pak requirements, number of players, save types, developer and publisher information, and other data.

#### How do I use this?

However you'd like really! This can be used as an emulator game database, or for informational purposes inside something like a frontend or library/cataloging service.

## License

This project is licensed under the N64DB license. This can be found in the project root directory.
