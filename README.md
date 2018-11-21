# Home Poems

## by Daniel W. Hoyt

This repository contains a transcription of the privately published collection
of poetry. Daniel W. Hoyt is [my](https://github.com/aronatkins)
great-great-grandfather. My grandmother, Ruth (Wheeler) Atkins, was the
daughter of Ruth Williams (Hoyt) Wheeler, who was the daughter of Rev. Hoyt.

The biography in Home Poems mostly mirrors the information contained in his
[WikiTree entry](https://www.wikitree.com/wiki/Hoyt-579).

The copy of _Home Poems_ used for this transcription has been handed down
through my family. My copy came from my father.

Transcription by [Aron Chandler Atkins](https://github.com/aronatkins),
November, 2018

## What's here?

The [`text`](text) directory contains the original transcriptions; one file
per poem. The poem titles in these files are all in uppercase, to match the
book.

The [`docs`](docs) directory contains the content hosted by GitHub Pages at
https://aronatkins.github.io/home-poems/.

## Markup conventions

Let's look at one stanza from "My Granddaughters":

    <p>
        Ruthie, dear, you blushing rose,<br/>
        &emsp;  Have pity on a lover's woes,<br/>
        Were I a happy, healthy boy,<br/>
        &emsp;  I know where I would seek my joy.<br/>
        "Piggly, Wiggly, Sir," she said.
    </p>

The `<p>` tag is used to mark the bounds of a stanza. This corresponds to
a blank line between groups of poetry lines. The `<br/>` tag forces a line
break within that "paragraph". The `&emsp;` asks that a "wide" space character
be inserted before the next word and leaves us with the "ragged" style that is
throughout Hoyt's poetry.

Here is that same block of poetry as it would appear in the book:

<blockquote>
    <p>
        Ruthie, dear, you blushing rose,<br/>
        &emsp;  Have pity on a lover's woes,<br/>
        Were I a happy, healthy boy,<br/>
        &emsp;  I know where I would seek my joy.<br/>
        "Piggly, Wiggly, Sir," she said.
    </p>
</blockquote>
