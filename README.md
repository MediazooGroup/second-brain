---
title: README
type: readme
tags: [start-here]
created: 2026-08-05
status: living
---

# Start here

**Download it:** click the green **Code** button above, then **Download ZIP**.
Unzip it, and open the folder in Obsidian. That is the whole setup.

Built live on *The Second Brain Blueprint*, part 2. The free series and course
are at `https://second-brain.finervision.app`.

---

You are looking at a second brain. A small one, but a real one.

It is a plain folder of plain text files. There is no app that owns it, no
account behind it and no format you could be locked out of. You could open every
file in here with Notepad or TextEdit and read all of it.

The subject of this one is the thing you are living through: the four week
Second Brain Blueprint. There is a note for each week, a note for the idea
underneath it, and the two notes that were written live on the stream. They are
linked to each other, they each carry a small block of information at the top,
and there is an index at the front that maps the lot.

So it is not an empty template. It is a worked example you can pull apart.

**Open [[INDEX]] and start there.**

## How to open it properly

You can read these files anywhere. To get the links and the search working, open
the folder in Obsidian.

1. Download Obsidian from `https://obsidian.md`. It is free, it works offline,
   and it does not ask you for an account.
2. Open it. Choose **Open folder as vault**.
3. Choose this folder, the one this README is sitting in.
4. Obsidian asks whether you trust the folder. Say yes. It is your folder.
5. Click `INDEX` in the list on the left.

This folder already carries a small `.obsidian` settings folder, so it opens with
backlinks, outgoing links and the graph switched on. That is just where Obsidian
keeps settings. Change anything you like; it is your folder now. Leave it and it will
look after itself.

## The six labs, written out as steps

This is what was done live on the stream, in order, so you can do it yourself or
do it again. Each one is small on purpose. All six take about an hour the first
time and about ten minutes the second.

### Lab 1. Install Obsidian

The tool is free, it is small, and it does not want an account from you.

1. Go to `https://obsidian.md` and press the download button. It picks the right
   version for your machine on its own.
2. Install it the way you install anything else, then open it.
3. If it offers you a sign in, ignore it. That is only for their paid syncing
   service, and you do not need it for any of this.
4. Change one setting before you do anything else. Open **Settings**, then
   **Appearance**, and make the font size bigger than you think you need.

That last step is the one people skip and then regret. Everything after this is
reading text on a screen.

**What good looks like:** Obsidian is open, and you can read it comfortably from
where you normally sit.

### Lab 2. Create your first vault

A vault sounds like a product. It is a folder. That is the entire idea.

1. In Obsidian, choose **Create new vault**.
2. Name it `My second brain`. That is a **different folder from this one**. This
   folder is the worked example you can pull apart. That one is yours, and it
   starts empty.
3. Put it on your **Desktop**, so you can see it. This matters more than it
   sounds like it should: you want to watch a real folder appear in a real place
   on your real computer.
4. Press create.

Now go and look at your Desktop. There is a new folder there. It is empty. That
is your second brain, and nothing about it is special.

**What good looks like:** an empty folder on your Desktop called
`My second brain`, open in Obsidian.

### Lab 3. Your first markdown note

Markdown is ordinary writing plus about five small marks. That is the whole
technical part, and you have now met most of it.

1. Make a new note. Click the new note button, top left, or press **Ctrl+N**
   (**Cmd+N** on a Mac).
2. Name it after a question you actually have. On the stream the question was
   **What actually makes our content land?** and the note was called
   `What actually makes our content land`. Use your own if you have one.
3. Write the note using these five marks:

| Mark | You type | You get |
|---|---|---|
| Hash | `# A heading` at the start of a line | a heading |
| Two stars | `**like this**` | **bold** |
| Dash | `- ` at the start of a line | a bullet in a list |
| Two square brackets | `[[Another note]]` | a link to another note |
| Backticks | `` `like this` `` | code, or anything you want left exactly as typed |

That is it. There is no sixth thing being kept from you.

4. Finish on a link to a note that does not exist yet. On the stream that was
   `[[Things that landed]]`. It will show up in a different colour, because
   there is nothing on the other end of it. Leave it. Lab 4 fixes it.

There is a finished version of this note in this folder, called
[[What actually makes our content land]], if you want to see one that is done.

**What good looks like:** a note with a heading, some bold, a list, and one link
that does not go anywhere yet.

### Lab 4. Link documents together

This is the move that turns a pile of files into something that thinks.

1. Click the unresolved link you left at the end of lab 3.
2. Obsidian creates that note for you and opens it. You did not have to make it,
   name it or file it. You just had to want it.
3. Write a few lines in it. It does not have to be good. On the stream this note
   was a holding pen: one line per idea, sorted out another day.
4. Now open the **backlinks** pane. It is at the bottom of the note, or use the
   panel on the right. If you cannot see it, open the command palette with
   **Ctrl+P** (**Cmd+P**) and search for "backlinks".
5. Look at what it says. Your new note knows that the first note points at it.
   Nobody told it that. Nobody maintains it.

That is the payoff. You write links in one direction and you get them back in
both.

**What good looks like:** two notes, a link from the first to the second, and
the second one showing you the first in its backlinks.

### Lab 5. Front matter, and what it is for

Front matter is the small block at the very top of a note, between two lines of
three dashes. It is how a note tells you, and later tells an AI, what it is.

1. Open your first note and put the cursor at the very top, above everything.
2. Type three dashes, then the fields, then three more dashes. Like this:

```
---
title: What actually makes our content land
type: note
tags: [content, second-brain]
created: 2026-08-05
status: raw
---
```

3. Put a shorter block on your second note, with the same `tags:` line but only
   `content` in it.
4. Now click the word `content` where Obsidian shows it as a tag. Both notes come
   back.

That is the whole point of front matter, done in one click, with no plugin and
no setup. You are not decorating the note. You are giving yourself a way to find
it in two years, when you have four hundred of them and no memory of writing
this one.

**What good looks like:** clicking a tag returns both of your notes.

### Lab 6. Progressive disclosure and the root index

The last move, and the one that keeps the whole thing usable as it grows.

1. Make one more note and call it `INDEX`. In capitals, so it sorts to the top
   of the list and reads as a signpost.
2. Do not put your notes in it. Put **links** to your notes in it, with one line
   each saying what they are.
3. That is it.

The idea has a name: progressive disclosure. The index shows you the shape, and
you open the detail only when you want it. It is why you can walk into a library
you have never visited and find a book in two minutes.

The [[INDEX]] in this folder is a worked example of the same move at a slightly
bigger size.

**What good looks like:** a note called `INDEX` that links to everything else,
and nothing else in it.

## What you have when all six are done

A folder on your Desktop, with a couple of notes in it, that are linked to each
other, labelled at the top, and mapped from an index at the front.

That is a second brain. Everything after this is more of it, not different from
it.

Next: [[CONNECT-AN-AI]] to talk to it, or [[WHAT-NEXT]] for where the rest of
the series goes.
