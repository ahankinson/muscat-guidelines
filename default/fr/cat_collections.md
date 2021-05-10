This section describes how to catalog special types of sources: collections, composite volumes, contrafacta, compilations, parodies, mixed materials (manuscripts and printed items stored together), music in periodicals, music in non-music publications, treatises, and piano arrangements.

### Cataloging collections

In RISM, a _collection_is both an intentional collective manuscript or anthology of multiple works as well as an item that contains two or more separate pieces. The latter means that if a manuscript for a piano sonata, for example, also has a sketch for a fugue at the very end, RISM would catalog it as a collection with a parent record for the item as a whole and individual entries for the sonata and the fugue.

When cataloging collections, please note that:

1. The collection main entry (parent record) should contain information that applies to the entire collection.
2. Any information that is relevant only for some sections of the collection should be entered in the individual entry.

If the works in the collection have different composers, scoring, source types, etc., then do not enter them in the parent record.

For collections in which the works are very similar, it is a good strategy to create a full first entry and use the "Duplicate" function to copy the record. Then for the following records you only have to change fields such as title and page number.

Collection parent records may not contain collection parent records of manuscripts. Instead, use a flatter hierarchy by means of individual records and explain the structure, makeup, or organization of the item in a note.

###

### Cataloging a composite volume
A **composite volume** consists of items that were created separately but later bound together, typically by an owner or institution. There are other names for such volumes: bound-with, Sammelband, binder's volume, and collector's volume. Composite volumes include volumes in which individual printed items are bound together, as well as volumes in which printed items and manuscripts are bound together.

There are two ways to indicate a composite volume. The first, and simplest, way is to give the items the same shelfmark; a bound-with note is also helpful. The second is to use the template for composite volumes.

The composite volume record serves as means to link all bound items to a single record, thus providing the user with a convenient overview of the entire contents of a bound item.

Records for a composite volume should be kept simple. As with collection parent records, the information given in the composite volume record should be true for all of the components of the volume, and remember that detailed information related to the music belongs in the respective bibliographic records. Do not create separate records for multiple composite volumes that belong together, such as a set of partbooks bound by voice type; these should be described in the same record. In many cases, you will be leaving a lot of fields blank.

You will be linking either a manuscript item or a printed item to a record for a composite volume, and they are linked differently.

1. First, create the record for the composite volume, save, and note the RISM number.
2. For manuscripts: In the editing mode of the record for your manuscript, go to the field **Parent record (773)**. Click the second button to search for the composite volume.
3. For printed music: In the holdings information for the printed edition, find the field **Bound with (973)** and click the magnifying glass. Find the record for the composite volume and select it.

### Cataloging contrafacta

Contrafacta are vocal pieces in which the text is changed without significant change to the music, such as retexting a secular work with sacred text, or the other way around. The derivation is almost mechanical; there is little creativity on the part of the arranger, but there is a significant change in the musical purpose (such as from a theatrical context to a religious one).

Please note that RISM considers contrafacta to be separate from parody and parody masses, which typically involve a more significant transformation of the musical material.

Take note of the following fields when cataloging contrafacta. RISM ID no. 300234487, a sacred contrafactum of an aria from Josef Mysliveček's opera Il Bellerofonte, will be used as an example.&nbsp;

**Composer (100)**    
Enter the composer of the original music.

- Mysliveček, Josef

**Standardized title (240)**  
Use the standardized title of the original piece. **Excerpts** may be added. Do not use **Arr**.

- Il Bellerofonte. Excerpts

**Alternative title (730)**  
If there is a new, distinct standardized title for the piece in hand, you can enter it here. Do not enter text incipits here.

**Subject headings (650)**  
Add at least 3 subject headings (more if appropriate), in this order:  
Contrafacta  
Current genre  
Original genre

- Contrafacta
- Sacred songs
- Operas

**Description summary (520)**  
Add a short description in English that explains the situation as a benefit to other RISM users.

- Sacred contrafactum of an aria from Mysliveček's opera Il Bellerofonte.

**Language of text (041)**  
Fill out both of these fields:  
Language of text (041 $a): The current text of the source in hand  
Language of original text (041 $h): Language of the original piece

- Language of text: Latin
- Language of original text: Italian

**Text incipit (031 $t)**  
You will enter two text incipits (use the + to add a new line).  
The text incipit of the current text  
The text incipit of the original text, if known, in brackets.

- Alma redemptoris mater, quae pervia caeli
- [Giusti dei che ben vedete]

**Other fields**

All other fields, such as liturgical feasts and instrumentation, should refer to the source in hand, that is, the contrafactum itself, and not the original work on which it was based.


### Cataloging compilations

Compilations are new, independent works made from parts of one or more other works and can also include new material. Frequently, the resulting work is of a different genre than the component parts, such as when arias or duets from an opera become a cantata, or excerpts from an opera become an instrumental suite. This also includes pasticcios. While the boundary between a compilation and a pasticcio is not always clear, pasticcios can be generally be characterized by one of these features: (1) arias, duets, or larger parts of dramatic works that are adapted to a new libretto; (2) several independent works combined to create a new work; or (3) collaborative compositions conceived as such from the beginning.

Compilations may be entered on a single record, or they may be entered as collections.

Take note of the following fields when cataloging compilations.

**Composer/Author (100)**  
The composer is always **Compilations**.

**Additional personal name (700)**  
The name of the compiler can be added with the function **Editor**.

If you have a compilation, enter the composer(s) of the original material and select the function **Composer cross-reference**. Enter the composer(s) of the new material and select the function **Co-composer**.

If you have a pasticcio, do not enter composers as a composer cross-references. Instead, enter all composers as **Co-composer** s.

**Standardized title (240)**  
Enter the standardized title of the source in hand. For pasticcios, add **Excerpts** or **Arrangement** as appropriate.

**Language code (041)**  
For the field **Language of text** , enter the language of the source in hand. If appropriate, the language of the original work can be entered in **Language of original text**.

**Subject heading (650)**  
The first subject heading should be **Compilations** and/or **Pasticcios**. The second should be the genre of the source in hand. If you have excerpts, the genre of the excerpt can be added. **Collaborative compositions** is also an option.

**Description summary (520)**  
Use this field to describe in general the nature of the source.  
_Example_ :  
Act 1 by Amadei, act 2 by Bononcini, overture and act 3 by Händel

**Alternate title (730)**  
Enter the standardized title of the original piece(s), adding **Excerpts** or **Arrangement** as appropriate. You can also enter ossia titles.

**Catalog of works (690)**  
You can enter the catalog of works number for both the compilation and the original works.

**Text incipit (031)**  
Enter the text of the source in hand. If known, enter the original text in brackets.

**General note (500)**  
Always use a note for clarification, especially if the works of separate composers are involved. This ensures that the composers are matched to the works used in the compilation.

**Note on performance (518)**  
Performances should be noted only as they relate to the compilation itself.

**Examples of compilations** :

230001408: Cantata made from opera arias with newly composed recitatives

702000623: Suite made from parts of an opera

700007222: Several works by a single composer used to create a new cantata

702000642, 702000643: Several works by several composers used to create a new suite

452505748: An opera pasticcio consisting of 3 acts by 3 different composers

**&nbsp;**

### Cataloging parodies

A parody is a composition based on pre-existing material that results in a new work. In the 19th century, the term gains a satirical flavor.&nbsp;&nbsp;

The record 150205470 will be used as an example.

&nbsp;

**Composer (100)**

Enter the composer of the music for the source in hand.

- Weyse, Christoph Ernst Friedrich

**Additional personal name (700)**

Enter the composer of the pre-existing material and select the function Composer cross-reference.

- Rossini, Gioachino

**Standardized title (240)**

Enter the standardized title of the source in hand.

- Dannemark hellige lyd

**Additional title (730)**

Enter the title of the pre-existing material. Add Excerpts as appropriate. Do not use Arrangement or Variations.

- Tancredi. Excerpts

**Subject heading (650)**  
Enter Parodies as the first subject heading. Enter the genre of the source in hand for the second, and the genre of the pre-existing material as the third.

- Parodies
- National anthems
- Operas

**Language code (041)**

Enter the language for the source in hand in the field Language of text. Enter the language of the pre-existing material in the field Language of original text.

- Danish
- Italian

**Text incipits (031)**

Enter the text incipit of the source in hand. If the original text is known, enter it in brackets.

- Dannemark hellige lyd
- [Di tanti palpiti]

**Other fields**

All other fields, such as performance information, should relate only to the source in hand.

**&nbsp;**

### Cataloging mixed materials (manuscripts and printed items stored together)

It is not uncommon for manuscript and printed items to be found together in the same folder or with the same shelfmark: for example, a printed score with handwritten parts, or a group of printed parts together with some handwritten ones.

Ideally, the printed material should be cataloged in a separate record, because it is possible that other libraries have copies of the same edition. Create one record for the printed item, add your holdings, and create another record for the manuscript materials. Include cross-references to each so that the user understands what the library has.   
Example: 280000006 is a record for 4 handwritten parts to an overture. 990055636 is a record for the printed parts. The library has added its holdings to the parts. A note in each record refers the user to the other material.

It is not always feasible to create two records: perhaps your printed item does not contain enough information to create an adequate record. In such cases, proceed as follows: Catalog your material using a manuscript template. In the material description section, describe materials of one type (such as the manuscript materials). Add an additional material group, and describe the materials of the other type (such as the printed materials).

### Cataloging music in periodicals
There are two ways to catalog periodicals that contain music: as a collection or as a single work. In either case, the title of the periodical, with the issue number and year, is entered in the field **Additional title (730)**.


**Collections** can be appropriate when the periodical consists of all or mostly music and the item was collected and preserved as a whole. Holdings are attached to the collection level. Individual entries are created for each piece in the issue.  
_Example_:  
1001097294: January issue (precise year unknown) of the _Kleine Pianoforte-Bibliothek_, containing 5 pieces. There is one record for the collection parent record, and five individual entries for each piece.

**Single works** can be appropriate when works were included as insertions or additions to periodicals without a notated music focus. Frequently, such items are preserved outside of their original publication context.  
_Examples_:&nbsp;   
991018149: "The Pantheon" published in _The Lady's Magazine_, August 1784  
990042111: "L'amour folâtrant l'autre jour" published in _Nouveau Mercure galant_, May 1679

###
Cataloging music in non-music publications

RISM includes music found in printed publications that are not primarily music documents. The focus of the RISM record is nevertheless the music.

_Example_:   
990026614: 3 songs by John Isaac Hawkins that were published in Charles Willson Peale's _Discourse introductory to a course of lectures on the science of nature_ (1800).  
**Composer/Author (100)**: The composer of the music  
**Additional Personal Name (700)**: The author of the book, with the indicator **other**  
**Title on source (245)**: The title of the book  
**Standardized title (240)**: A standardized title according to RISM rules, such as **3 Songs**  
**Physical description (300)**: A description of the music, such as **1 score: 5 p.&nbsp;**

Individual entries are then created for each piece, following normal RISM rules.

### Cataloging treatises

When cataloging treatises, the field **Format, extent (300 $a)** should generally include "text document" as the format.

Appropriate subject headings for treatises include the following:

- **Treatises**
- **Writings**
- **Music theory**
- **Theory of harmony**
- **Tutors (inst.)**: Includes methods and schools
- **Tutors (voc.)**: Includes methods and schools
- **Contrapuntal studies (inst./voc.)**
- **Solfeggios (voc.)**
- **Solfeggios (inst.)**
- **Scales (inst./voc.)**

Additional subject headings may be added.

### Cataloging piano arrangements

Specify piano arrangements as follows.

-

In the field **Standardized title (240):**

  -

Select **Arrangement** next to **Arrangement statement**.

  -

Under **Scoring summary** , enter the scoring of the arrangement, such as **pf** or **V, pf**. Do not enter the scoring of the original work.

-

In the field **Total scoring (594)**, enter the total scoring of the arrangement. Do not enter the scoring of the original work.

-

In the field **Physical description (300)**, use **keyboard score** if the work has been reduced for piano. Use **vocal** score if the work has been reduced for voice and piano.