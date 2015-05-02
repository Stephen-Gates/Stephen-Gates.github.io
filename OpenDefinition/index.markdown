
#### This is a draft 
The [Open Definition](http://opendefinition.org/od/) has three key requirements for a work to be open: an *open license*, *open access*, and an *open format*. This page focuses on the **open format**: 

1. quoting the <a href=“#openformat”>Open Format</a> section from the Open Definition, 
2. exploring it’s <a href=“#intent”>intent</a>,
3. defining the <a href=“#meaning”>meaning of special words</a>,
4. collecting <a href=“#improve”>ideas for improvement</a>,
5. providing links to <a href=“#resources”>related resources</a>, and 
6. letting you peek at <a href=“#coming”>what’s coming next</a>.

<h4 id=“contribute”>Make it better</h4>

*Get involved, learn more, and help us improve the Open Definition:*
- *To get started, [join the conversation](http://lists.okfn.org/mailman/listinfo/od-discuss), ask questions and suggest improvements on the Open Definition discussion list.*
- *Catch up on [past conversations](https://lists.okfn.org/pipermail/od-discuss/) and see what you’ve missed.*
- *Dive in deep, [add an issue](https://github.com/okfn/opendefinition/issues) or a pull request to the Open Definition GitHub repository.*

<h2><a id=“openformat”>1. The Open Format defined</a></h2>

Section 1.3 Open Format from the Open Definition version 2.0,

>The **work** *must* be provided in a convenient and modifiable form such that there are no unnecessary technological obstacles to the performance of the licensed rights. Specifically, data *should* be machine-readable, available in bulk, and provided in an open format (i.e., a format with a freely available published specification which places no restrictions, monetary or otherwise, upon its use) or, at the very least, can be processed with at least one free/libre/open-source software tool.

<h2><a id=“intent”>2. The Intent</a></h2>

We want to create open knowledge. To help achieve this, the Open Format requires:

#### The work must be provided in a convenient form
The **work** *must* be provided in a convenient format so that it is easy to reuse. To maximise knowledge sharing: 
- the **work** *should* be published in a format suitable for its media type.  
- the **work** *should* be published in a  be lossless and uncompressed format so all the original detail is retained.

#### The work must be provided in a modifiable form
The **work** *must* be provided in a modifiable format so it can be reused in different ways. How can the **work** be modified? 

If the **work** is data: 
- it *should* be able to be “processed with at least one free/libre/open-source software tool”.
- or, software can be created to read and write the format because there *should* be a, “freely available published specification which places no restrictions, monetary or otherwise, upon its use”.


If the work isn’t data, (<a href=“#contribute”>contribution needed</a>)

#### no unnecessary technological obstacles to the performance of the licensed rights
(<a href=“#contribute”>contribution needed</a>)

#### Data should be machine-readable
(<a href=“#contribute”>contribution needed</a>)


#### Data should be available in bulk
The **work** *should* be provided in bulk, means the data can be accessed easily in one request. 

This requirement complements the Access section of the Open Definition and together they require that:

- the data *must* be published as a whole.
- the data *should* be downloadable via the Internet, for free, in bulk.

But your data can still be open if you publish it as many individual files (however it could be argued you’re not publishing it in a convenient form). 

#### Data should be provided in an Open Format
##### An Open Format for data - Definition 1:

An Open Data Format is:
- a format with a freely available published specification
- a format that places no restrictions, monetary or otherwise, upon its use. 

If an open data format has a freely available published specification, then software to process the format can be implemented by others. Wider software support means re-users have more choice of tools they can use. Ideally the specification should be defined through a fair, transparent and collaborative process.

If an open data format places no restrictions, monetary or otherwise, upon its use, then:
- data re-users do not need to buy specific software to process the data
- software implementors can use the programming language of their choice 
- there is no need to pay royalties or worry about patents or trademarks


##### An Open Format for data - Definition 2:
An Open Format is: 
- a format that can be processed with at least one free/libre/open-source software tool.

Ideally there is an open source reference implementation for reading and writing 

##### Loophole 1?
The Open Format for data definitions enable tabular data (e.g. a budget) to be published as a PDF (an open format according to the definition). However, this is not a convenient form for this type of data and, “the **work** *must* be provided in a convenient and modifiable form such that there are no unnecessary technological obstacles to the performance of the licensed rights”.

So, is a PDF of a Budget open?

Tim Berners-Lee’s [5 Star Open Data](http://5stardata.info) scheme say’s it is. (<a href=“#contribute”>Contribution needed</a> - does the Open Definition agree?)


##### Loophole 2?
It could be argued that by prefixing the second sentence of the Open Format with, “Specifically, data *should*…”, this means non-data **works** *may* but are not required to:

- be machine-readable 
- be provided in bulk 
- be provided in an open format (i.e.) 
— have a freely available published specification 
— remove restrictions, monetary or otherwise, upon its use. 
— be processed with at least one free/libre/open-source software tool 

(<a href=“#contribute”>Contribution needed</a> - what is the intent?)


<h2><a id=“meaning”>3. Words with special meaning</a></h2> 

Some words in the Open Definition have special meaning and are  shown in **bold** or *italics*. There meaning is defined below:

**Work** - denotes the item or piece of knowledge being transferred [<a href=“#OD”>OD</a>]. Examples of a work include, but are not limited to: data, music, art, images, video, literary compositions, web pages and software. 

**Must**, **Required**, or **Shall** - an absolute requirement  [<a href=“#RFC2119”>RFC2119</a>].

**Must Not** or **Shall Not** - an absolute prohibition [<a href=“#RFC2119”>RFC2119</a>].

**Should** or **Recommended** - there may be valid reasons to ignore this requirement but the full implications must be understood and carefully weighed before choosing a different course [<a href=“#RFC2119”>RFC2119</a>].

**Should Not** or **Not Recommended** - there may be valid reasons when the particular behaviour is acceptable or even useful, but the full implications should be understood and the case carefully weighed before implementing any behaviour described with this label [<a href=“#RFC2119”>RFC2119</a>].

**May** or **Optional** - the item is truly optional [<a href=“#RFC2119”>RFC2119</a>].


<h2><a id=“improve”>4. Improving the Open Format</a></h2>

These improvement ideas mainly come from conversations on the [discussion list](https://lists.okfn.org/pipermail/od-discuss/) and cover:
- Improving the Open Format definition 
- Using the Open Format definition

Got an idea? Help <a href=“#contribute”>make it better</a>.

### Improving the Open Format definition 

The work must be distributed in an open format that is appropriate for its media type to maximise the opportunity for reuse. An open format is one that allows the work to be fully performed or processed with no restriction.

An open format **must**:
- have no restrictions, monetary or otherwise, upon its use.
- be machine-readable and able to be fully processed with at least one free/libre/open-source software tool.

An open format *should*:
- be documented so it can be freely implemented by others.
- be defined through a fair, transparent and collaborative process.
- be widely used and accepted as best practice within your discipline or other user communities.
- be lossless and uncompressed so all the original detail is retained.

#### Machine-readable
- Andrew Stott - what format to use - https://lists.okfn.org/pipermail/od-discuss/2015-April/001332.html
- Rufus Pollock - open format varies by type. We’ve tried to define it previously - http://webarchive.okfn.org/okfn.org/201404/opendata/glossary/#machine-readable
- Peter Murray-Rust - Destroying machine-readable work, destroys value - https://lists.okfn.org/pipermail/od-discuss/2015-April/001336.html
- Herb Lainchbury - Open Data Usability Index - https://lists.okfn.org/pipermail/od-discuss/2015-April/001337.html and http://goo.gl/xGpLIs

#### bulk relates to access
1.2 Access
The work must be available as a whole and at no more than a reasonable one-time reproduction cost, preferably downloadable in bulk via the Internet without charge. Any additional information necessary for license compliance (such as names of contributors required for compliance with attribution requirements) must also accompany the work.



## Using the Open Format definition

### A common resource for tools to reference
Tools like the [Open Data Census](http://census.okfn.org/) and [Open Data Certificates](https://certificates.theodi.org/) test to see if data is published using an open format. This [improvement idea](http://opendefinition.org/licenses/) seeks to harmonise the definition of the Open Format for data so that tools could all point to the Open Definition, in the same way the tools currently point to it for a definition of an open licence and a list of [conformant licenses](http://opendefinition.org/licenses/).

<h1><a id=“resources”>3. Resources</a></h1>

## Lists of Open Formats
This list of resources have not been assessed as being conformant with the Open Definition but we hope you'll find them useful:
- AusGOAL [Open Formats](http://www.ausgoal.gov.au/open-formats) -  Examples of open formats by media type. 
- Snowdrift [FLO Formats and Repositories](https://snowdrift.coop/p/snowdrift/w/en/formats-repositories) - Free and open file formats and online repositories for Free/Libre/Open works.
- Australian National Data Service [File Formats](http://www.ands.org.au/guides/file-formats-working.html) - Examples of open formats. Also covers preservation, lossy formats, compression, and the importance of standards. 


Do you have another resource you’d like added here? <a href=“#contribute”>Make the list better</a>.

<h1><a id=“coming”>4. What’s coming next? </a></h1>

The [Open Definition version 2.1](https://github.com/okfn/opendefinition/blob/master/source/open-definition-2.1-dev.markdown) is being drafted. Can you <a href=“#contribute”>make it better</a>?

# References
<p><a id=“OD>[OD]</a> <a href=“http://opendefinition.org/od/”>Open Definition</a> by Open Knowledge. </p>

<p><a id=“RFC2119”>[RFC2119]</a> <a href=“http://www.ietf.org/rfc/rfc2119.txt”>Key words for use in RFCs to Indicate Requirement Levels.</a> by S. Bradner, IETF RFC2119.</p>



