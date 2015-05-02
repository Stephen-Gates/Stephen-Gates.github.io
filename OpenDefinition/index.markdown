
<p id=“contribute”><b>This is a draft</b>.<i> We need your help to make it better. Get involved, learn more, and help us improve the Open Definition:</i></p>
- *To get started, [join the conversation](http://lists.okfn.org/mailman/listinfo/od-discuss), ask questions and suggest improvements on the Open Definition discussion list.*
- *Catch up on [past conversations](https://lists.okfn.org/pipermail/od-discuss/) and see what you’ve missed.*
- *Dive in deep, [add an issue](https://github.com/okfn/opendefinition/issues) or a pull request to the Open Definition GitHub repository.*

## Introduction 
The [Open Definition](http://opendefinition.org/od/) has three key requirements for a work to be open: an *open license*, *open access*, and an *open format*. This page focuses on the **open format**: 

1. quoting the <a href=“#openformat”>Open Format</a> section from the Open Definition, 
2. exploring it’s <a href=“#intent”>intent</a>,
3. <a href=“#testing”>testing</a> some real world examples,
4. defining the <a href=“#meaning”>meaning of special words</a>,
5. collecting <a href=“#improve”>ideas for improvement</a>,
6. providing links to <a href=“#resources”>related resources</a>, and 
7. letting you peek at <a href=“#coming”>what’s coming next</a>.



<h2><a id=“openformat”>1. The Open Format defined</a></h2>

Section 1.3 Open Format from the Open Definition version 2.0 states:

>The **work** *must* be provided in a convenient and modifiable form such that there are no unnecessary technological obstacles to the performance of the licensed rights. Specifically, data *should* be machine-readable, available in bulk, and provided in an open format (i.e., a format with a freely available published specification which places no restrictions, monetary or otherwise, upon its use) or, at the very least, can be processed with at least one free/libre/open-source software tool.

<h2><a id=“intent”>2. The Intent</a></h2>

We want to create open knowledge. To help achieve this, the Open Format requires:

#### The work must be provided in a convenient form
The **work** *must* be provided in a convenient format so that it is easy to reuse. This requires the **work** to be published in a format that maximises knowledge sharing and reuse. The format may vary for different media types (e.g. image, text, geographic data).  

#### The work must be provided in a modifiable form
The **work** *must* be provided in a modifiable format so it can be reused in different ways. What is an appropriate modifiable form? 

- If the **work** is data, an appropriate modifiable form is one that is machine-readable and in an open format.
- If the **work** isn’t data, an appropriate modifiable form is one that (<a href=“#contribute”>contribution needed here</a>).

#### No unnecessary technological obstacles to the performance of the licensed rights
(<a href=“#contribute”>contribution needed</a>)

#### Data should be machine-readable 

Data is machine-readable if it is in a format that can be easily  read, written, parsed and displayed by a computer. 

For example:
- Non-digital material, is by its non-digital nature, not machine-readable (e.g. printed or hand-written documents). 
- Digital material may not be machine-readable. For example, consider a PDF document containing tables of data. These are definitely digital but are not machine-readable because a computer would struggle to access the tabular information. 
- A HTML web page containing tables of data may be machine-readable depending on how the data is encoded.
- The equivalent tables in a format such as a spreadsheet would be machine-readable.

As another example: 
- Scans and photographs of text are not machine-readable.
- The equivalent text in a format such as a simple ASCII text file or a text-processing format such as Microsoft Word file is machine-readable.

Appropriate machine-readable format may vary by data type. For example, a machine-readable format for geographic data may be different to a format for tabular data.

This section is based on [<a href=“#machine”>OKFN</a>] and [<a href=“#od-discuss”>OD-Discuss</a>].

See also https://www.data.gov/developers/blog/primer-machine-readability-online-documents-and-data 


#### Data should be available in bulk
The **work** *should* be provided in bulk, means the data can be accessed easily in one request. 

This requirement complements the Access section of the Open Definition and together they require that:

- the data *must* be published as a whole.
- the data *should* be downloadable via the Internet, for free, in bulk.

But your data can still be open if you publish it as many individual files (however it could be argued you’re not publishing it in a convenient form). 

#### Data should be provided in an Open Format
##### An Open Format for data - Definition 1:

An Open Data Format is a format with a freely available published specification which places no restrictions, monetary or otherwise, upon its use. 

A freely available published specification allows:
- conformant software to read and write the data in that format can be implemented by others. 
- a wider choice of software tools for data re-users. 

If an open data format has no restrictions, monetary or otherwise, upon its use, then:
- data re-users do not need to buy specific software to process the data.
- conformance testing of open format implementations should be free.
- there is no need to pay royalties.
- it is not named using a trademark unless that trademark is usably by anyone under appropriately open terms.


##### An Open Format for data - Definition 2:
An Open Format is: 
- a format that can be processed with at least one free/libre/open-source software tool.

<h2><a id=“testing”>3. Testing some real world examples
</a></h2>
### Is a National Budget in a PDF open?
The Open Format for data definitions above enable tabular data (e.g. a Nation Budget) to be published as a PDF (an open format according to the definition). However, this is not a convenient form for this type of data and, “the **work** *must* be provided in a convenient and modifiable form such that there are no unnecessary technological obstacles to the performance of the licensed rights”.

So, is a PDF of a National Budget open?

Tim Berners-Lee’s [5 Star Open Data](http://5stardata.info) scheme says it’s open and gets 1 star. 

Based on the definition of machine readable above, a PDF of a Nation Budget isn’t open. (<a href=“#contribute”>contribution needed - is this the intent?</a>)

### Non-data works 
It could be argued that by prefixing the second sentence of the Open Format with, “Specifically, data *should*…”, this means non-data **works** *may*, but are not required to:

- be machine-readable 
- be provided in bulk 
- be provided in an open format: 
— with a freely available published specification which places no restrictions, monetary or otherwise, upon its use, or  
— that can be processed with at least one free/libre/open-source software tool. 

(<a href=“#contribute”>Contribution needed</a>) Is it OK that these requirements are all optional for non-data works?


<h2><a id=“meaning”>4. Words with special meaning</a></h2> 

Some words in the Open Definition have special meaning and are  shown in **bold** or *italics*. There meaning is defined below:

**Work** - denotes the item or piece of knowledge being transferred [<a href=“#OD”>OD</a>]. Examples of a work include, but are not limited to: data, music, art, images, video, literary compositions, web pages and software. 

**Must**, **Required**, or **Shall** - an absolute requirement  [<a href=“#RFC2119”>RFC2119</a>].

**Must Not** or **Shall Not** - an absolute prohibition [<a href=“#RFC2119”>RFC2119</a>].

**Should** or **Recommended** - there may be valid reasons to ignore this requirement but the full implications must be understood and carefully weighed before choosing a different course [<a href=“#RFC2119”>RFC2119</a>].

**Should Not** or **Not Recommended** - there may be valid reasons when the particular behaviour is acceptable or even useful, but the full implications should be understood and the case carefully weighed before implementing any behaviour described with this label [<a href=“#RFC2119”>RFC2119</a>].

**May** or **Optional** - the item is truly optional [<a href=“#RFC2119”>RFC2119</a>].


<h2><a id=“improve”>5. Improving the Open Format</a></h2>

These improvement ideas mainly come from conversations on the [discussion list](https://lists.okfn.org/pipermail/od-discuss/).

#### Open Format Specification
An open format specification *should* be:
- defined through a fair, transparent and collaborative process.
- freely redistributable (although the document may be under a license that doesn’t allow changes to the specification document).
- Software language independent so software implementors can use the programming language of their choice.

#### Retain all original detail
The **work** *should* be published in a lossless and uncompressed open format so all the original detail is retained.


#### A common resource for tools to reference
Tools like the [Open Data Census](http://census.okfn.org/) and [Open Data Certificates](https://certificates.theodi.org/) test to see if data is published using an open format. This [improvement idea](http://opendefinition.org/licenses/) seeks to harmonise the definition of the Open Format for data so that tools could all point to the Open Definition, in the same way the tools currently point to it for a definition of an open licence and a list of [conformant licenses](http://opendefinition.org/licenses/).

<h2><a id=“resources”>6. Resources</a></h2>

Do you have another resource you’d like added below? <a href=“#contribute”>Make the list better</a>.

### Alternative definitions and views
The links provide alternate perspectives on open formats:
- [Open Format](http://en.wikipedia.org/wiki/Open_format) on Wikipedia.
- [An emerging understanding of Open Standards](http://blogs.fsfe.org/greve/?p=160) on Freedom bits.
- [Open Data Usability Index](http://goo.gl/xGpLIs) - Herb Lainchbury. Interesting perspective of the degree of readability of data - digital, parse-able, open, and structured.

### Lists of Open Formats
These lists of open format have not been assessed as being conformant with the Open Definition:
- AusGOAL [Open Formats](http://www.ausgoal.gov.au/open-formats) -  Examples of open formats by media type. 
- Snowdrift [FLO Formats and Repositories](https://snowdrift.coop/p/snowdrift/w/en/formats-repositories) - Free and open file formats and online repositories for Free/Libre/Open works.
- Australian National Data Service [File Formats](http://www.ands.org.au/guides/file-formats-working.html) - Examples of open formats. Also covers preservation, lossy formats, compression, and the importance of standards. 

<h2><a id=“coming”>7. What’s coming next? </a></h2>

The [Open Definition version 2.1](https://github.com/okfn/opendefinition/blob/master/source/open-definition-2.1-dev.markdown) is being drafted. At the time of writing, it states,

> The **work** *must* be provided in an open format. An open format is one which places no restrictions, monetary or otherwise, upon its use and can be fully processed with at least one free/libre/open-source software tool. Data must be machine-readable and should be provided in bulk where possible.

The changes:
- make the open format more concise.
- require data to be machine-readable (depending on your definition of machine readable a PDF of a Nation Budget is/isn’t open).
- don’t mention the need for a freely available published specification (what do you think about that?).

## References
<p><a id=“okfn”>[OKFN]</a> <a href=“http://webarchive.okfn.org/okfn.org/201404/opendata/glossary/#machine-readable”>Open Data Glossary</a> (Archived Content) by the Open Knowledge Foundation. </p>

<p><a id=“od-discuss”>[OD-Discuss]</a> <a href=“https://lists.okfn.org/pipermail/od-discuss/2015-April/subject.html#1330”>A harmonised Open Format definition</a> a discussion thread on the <a href=“http://lists.okfn.org/mailman/listinfo/od-discuss”>Open Definition Discussion list</a>. </p>

<p><a id=“od”>[OD]</a> <a href=“http://opendefinition.org/od/”>Open Definition</a> by Open Knowledge. </p>

<p><a id=“RFC2119”>[RFC2119]</a> <a href=“http://www.ietf.org/rfc/rfc2119.txt”>Key words for use in RFCs to Indicate Requirement Levels.</a> by S. Bradner, IETF RFC2119.</p>






