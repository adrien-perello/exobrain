---
tags: 📋/🌱/❗
---


- [check this forum post](https://forum.obsidian.md/t/zotero-best-practices/164/57) for more info

---

take my notes in pdf (had been going back and forth) and extract them via zotero to Obsidian’s vault as a literature note. Using the betterbibtex citekey as a title, it also allowed me to then convert a markdown file in Obisidian with the references to the (exported) literature notes to a word docx with active references (via pandoc’s ability to use the better bibtex citeky). This closed the circle for me!  
And if I want to exceptionally use a screenshot from the pdf instead of annoted text I can just copy/paste it quickly in obisidian and copy/paste the link back to the pdf in a note, allowing me to have a full, rich view of the literature that I can just keep on quickly overwriting in Obsidian anytime I annotate the pdf again - while keeping the links in Obsidian to that literature note.

---

see also video from Bryan Jenks on [[Obsidian & Zotero Workflow For Zettelkasten & Evergreen Notes]]

---

I made a working strategy now as follows:

-   make a single md file for each paper I read, use the file name as citekey (usually as lastname and Year)
-   use the md file heading as the formatted citation (eg MLA or other equivalents, to search them later)
-   copy and paste the full abstract of the paper
-   read the PDF and annotate
-   once done with PDF copy and paste the required text into the md file.
-   highlight the selected keywords and enclose them in \[\[ \]\]
-   change the default folder location of the new file created to a new folder named interalLinks

I then have all my keywords in the internalLinks folder and each of my PDF file in a separate md file. This way I can see all the files in the graph view and all the keywords or internal links will appear as connection between the md files I created.

---

**Reference Form**

I use the following style in my .md notes and in the titles of my files in my cloud drive.

Ex. A Book by John Doe, published in 1977: `(j_doe1977)`  
When I want to reference a page: `(j_doe1977p22)`  
If there are multiple authors or editors, I just use the first one named.

This form makes it SUPER easy to search for files and through my .md vault. If i remember the author’s last name only, I can just search `_d` and I almost always find it because few other documents or files have that.

**Notes & Connections**

I make a file for each work, ex, `(j_doe1977).md`. I’ll then take notes in that file while reading, making links to other files as I go along. Later I’ll move those notes from that author file to their proper place in a topics file, for example, `indo_iranian_history.md`. I usually work with particular articles, so I use this kind of focused form, but you could also just make a file called `(j_doe).md` or one called `scholars.md` if you want to be more vauge. I do this is some cases where I want to say something about the scholar as a person. You could also keep tabs on which books your finished taking notes on in the broader files like:

(j\_doe1977) DONE  
(j\_doe1985) IN THE PROCESS  
(j\_doe1994) NEED TO READ

---
Here’s the process I’ve come up with (which continues to evolve):

1.  Initial highlighting: Read journal article via Zotero. Highlight the parts that are relevant to you using the default PDF viewer on your computer. Use Zotfile to extract the highlights (and any notes) in Zotero, then paste them into Obsidian in a new note. I have a template I copy and paste to start each new highlight note with relevant details like the author names, date of publication and so on before the highlights.
    
2.  Refine highlights: Look through your highlights from the article and use the Obsidian highlighting feature (==like this==) to pinpoint what’s valuable in each highlight. This makes it easier to complete the next step, particularly if it’s a long paper or you have to come back to it. Skip if necessary.
    
3.  Process highlights into literature notes: Summarise the highlights into your own words. Add any personal insights. Each literature note should relate to one idea. I do this directly above the highlight notes using bullet points and a L - for literature notes and a H - for highlight notes. Try to write the literature note as if it was part of a journal article.
    
4.  Add a label to each literature note: Above each literature note, I add a label, which should be the briefest possible summary of the literature note. Have this label inside double square brackets. Avoid labels like “Definition of X”. Instead, write “X is y and z”. Try to be specific. I mainly use the bracket links in this way. An example label might be \[\[E - X is y and z\]\]. I use E - because it will soon be an evergreen note.
    
5.  Add each label to an index: The index will be a long list of all your literature note labels. Categorise the labels in a logical manner.
    
6.  Create evergreen notes: Click the label (which is a link to a new note) and copy/paste the literature note text (which will be quite short) into this new evergreen note. Add connections to other notes categorised in the same place in your index plus any other relevant evergreen notes. Add relevant tags. The index may not be overly important in the long run, but it definitely helps at this point with connection making. I also add the reference details at the bottom of each evergreen note. Next it’s time to create your paper.
    

7a. (Top down approach) Create journal article outline: Create an outline for your article, chapter, application, or whatever you’re working on. You can make a quick template with the relevant stages of the genre (e.g. introduction, literature review, and so on). Then, drag relevant evergreen notes into the sections. You’ll need to massage the gaps between notes to make it cohesive. If you use a note, add a tag to say so. You’ll need to reword the note if you use it again in another paper to avoid self-plagiarism.

7b. (Bottom up approach) Add evergreen notes to papers: Instead of starting with a paper outline, you might look at your notes in the index and consider what kind of interesting questions they might help you answer, then build your paper from there.

I hope someone out there finds all this useful. One of the best things I’ve done is create a note called master production line which includes these numbered steps as headings, and then I can add my highlight notes as they’re created and move them down the production line as they’re processed. I also organise them in certain steps (like 2 and 3) as high, medium and low priority. It means you never lose track of notes and there’s always something you could be working on. The bit I’m still figuring out is the last step: how to go from evergreen notes to paper drafts as efficiently as possible. I’m a little old fashioned, so I’ll probably so the final edit in Word once everything else is done in Obsidian. The multiple window support in Obsidian is great, but still a bit janky, and this method requires multiple windows to be open at a time. Hopefully a future update keeps the windows in the one spot.

---

SAME AS ABOVE BUT UPDATED

\[\[E - One-sentence summary of idea # Ahrens, 2018]]
L: The note rewritten in your own words with your own insights.
-   H: The highlight from the original source

Over time, I found that transforming the notes into my own words was taking a long time and creating a backlog of notes to process, so I’m now not transforming notes until later on. When I went to use the transformed notes in my own publications, I invariably reworked them anyway, so now I’m following the same process as above but not bothering with L notes. Also, following some reflection on Nick Milo’s blog post on progressive summarisation, I now think of connections earlier in the process. The current approach is:

1.  Read and highlight sources (in Zotero) then create Highlight notes in Obsidian
2.  Add one-sentence summaries above each idea (keeping the ideas in the original author’s words)
3.  Think of connections for each idea and add tabs and short notes instead of the old L notes
4.  Organise E summaries into the index
5.  Create evergreen notes by clicking the E summary in your index, adding in the surname and date of the author, the note from in the author’s words, connections and reference. (I actually call these Atomic notes now instead of evergreen notes because evergreen notes are defined differently to what I have, which is still the author’s original work but split up into atomic ideas)
6.  Create paper outlines drawing on the E titles and transcluded atomic notes in the index and transform into your own words from there.


One-sentence summary of idea
|  
Original idea in the author’s words (Reference, date, page number).  
T: [# tags](https://forum.obsidian.md/tag/tags) # go # here  
C: Any connections to other notes or ideas - not necessary to include for every idea but it’s useful to think of connections where possible

If you structure all the notes this way, it means you can then add the ideas straight into your index with transclusion without needing to create any additional notes (in the past I created a new evergreen note for each idea).

An example of a transcluded idea to pop into your index would be like this:

!\[\[Smith, 2018#One-sentence summary of idea\]\]

This allows you to see the source and the summary of the note in edit mode and just that idea transcluded from your note page in the preview mode.

The key I think is being able to process ideas into your vault as quickly as possible while still tagging and making connections to help with later retrieval of ideas.

---
check further for
- citekey
- bibtex
- pandoc