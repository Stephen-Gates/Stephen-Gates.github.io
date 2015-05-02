
-------------- next part --------------
An HTML attachment was scrubbed...
URL: <http://lists.okfn.org/pipermail/od-discuss/attachments/20150421/8dab95c2/attachment.html>

From stephen.gates at me.com  Tue Apr 21 13:18:17 2015
From: stephen.gates at me.com (Stephen Gates)
Date: Tue, 21 Apr 2015 23:18:17 +1000
Subject: [od-discuss] A harmonised Open Format definition
Message-ID: <4A596E03-6C18-4C70-AF14-A3C4A80BE903@me.com>

Hello Open Knowledge and Open Data Institute friends,

I would like to explore the possibility of aligning the Open Definition <http://opendefinition.org/od/>, Open Data Census <http://census.okfn.org/> and Open Data Certificates <https://certificates.theodi.org/> definitions for Open Format. This would enable the Census, Certificate and other open data tools to refer to the Open Definition for a definition of Open Format, in the same way they currently do for Open Licences.

To extend this concept further, I would like to mirror the Conformant Licenses <http://opendefinition.org/licenses/> page in the Open Definition with a Conformant Formats page. This would provide a list of file formats that conform with the Open Format definition. New formats could be submitted for assessment. Common formats (e.g. XML, JSON, KML, CSV, etc.) would be seeded on the page. Similar to the non-conformant licences <http://opendefinition.org/licenses/nonconformant/>  partially conforming formats could also be captured (e.g. XLS, SHP). This would cater for the spectrum of open file formats proposed by Tim Burners-Lee in his 5 star scheme <http://5stardata.info/>.


The respective definitions or help text are:

Open Definition draft 2.1
https://github.com/okfn/opendefinition/blob/master/source/open-definition-2.1-dev.markdown <https://github.com/okfn/opendefinition/blob/master/source/open-definition-2.1-dev.markdown> 
The work must be machine-readable and provided in an open format. An open format is one which places no restrictions, monetary or otherwise, upon its use and can be fully processed with at least one free/libre/open-source software tool. Data should be provided in bulk where possible.



Open Data Census 

see format, machine readable and bulk rows in Google Sheet,  https://docs.google.com/spreadsheet/ccc?key=0AqR8dXc6Ji4JdFI0QkpGUEZyS0wxYWtLdG1nTk9zU3c&usp=drive_web#gid=0

Format:
This question describes the form that the data is available in. For example, for tabular data it might be: Excel, CSV, HTML or even PDF. For geodata it might be shapefiles, geojson or something else. If available in multiple formats, the format descriptors are listed separated with commas. Any further information is put in the comments section.

Machine Readable:
Files are digital, yes, but not all can be processed or parsed easily by a computer. In order to answer this question, you would need to look at the datasets file type. 

As a rule of thumb the following file types are machine readable:

- XLS
- CSV
- JSON
- XML

If the files are in the following formats, the are NOT machine readable:

- HTML
- PDF
- DOC
- GIF
- JPEG
- PPT

If you have a different file type and you don?t know if it?s machine readable or not, send an email to the Open Data Census list.

Bulk:
Data is available in bulk if the whole dataset can be downloaded easily. It is considered non-bulk if the citizens are limited to getting parts of the dataset through an online interface.

For example, if restricted to querying a web form and retrieving a few results at a time from a very large database.


Open Data Certificates
Question: Is this data in a standard open format?

Help Text: Open standards are created through a fair, transparent and collaborative process. Anyone can implement them and there?s lots of support so it?s easier for you to share data with more people. For example, XML, CSV and JSON are open standards. Read more? (links to https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/183962/Open-Standards-Principles-FINAL.pdf <https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/183962/Open-Standards-Principles-FINAL.pdf>)


Proposed changes
A harmonised definition
The work must be machine-readable and provided in an open format. An open format is one which places no restrictions, monetary or otherwise, upon its use and can be fully processed with at least one free/libre/open-source software tool.

In addition:
- Data should be provided in bulk, i.e. the whole dataset can be downloaded easily.
- An open format should be documented so it can be freely implemented by others.
- An open format should be defined through a fair, transparent and collaborative process.



Open Data Census and Open Data Certificates
Adjust questions and help text to reference the Open Format definition and/or conformant licenses page.

Open Definition site
- Consider changing the page names from ?Conformant Licences? and ?Conformant Formats? to ?Open Licences? and ?Open Formats?. 
- Delete the open format definition page <http://opendefinition.org/ofd/>. It is replaced by the Open Formats page and the updated Open Definition.



What do you think? 
Is this worth progressing? Could this extend to Open APIs like Web Map Services (WMS)?


thanks

Stephen Gates
(localiser of the Open Data Census and Open Data Certificates in Australia)


-------------- next part --------------
An HTML attachment was scrubbed...
URL: <http://lists.okfn.org/pipermail/od-discuss/attachments/20150421/8710c014/attachment-0001.html>

From wolftune at riseup.net  Tue Apr 21 16:30:53 2015
From: wolftune at riseup.net (Aaron Wolf)
Date: Tue, 21 Apr 2015 09:30:53 -0700
Subject: [od-discuss] A harmonised Open Format definition
In-Reply-To: <4A596E03-6C18-4C70-AF14-A3C4A80BE903@me.com>
References: <4A596E03-6C18-4C70-AF14-A3C4A80BE903@me.com>
Message-ID: <55367B3D.5020903@riseup.net>

I think this concept is excellent, the consolidation and the
clarification of having a page of recognized Open formats.

Your points here bring up a serious problem though.

If HTML and JPEG formats are considered non-machine-readable then we
absolutely *have* to *remove* the machine-readable requirement from the
Open Definition. This is a very serious issue. The OD covers thing like
photographs and other images along with stuff like the writings on a
blog. It is absolutely unacceptable to have the "machine-readable" part
in the requirements for format in the OD if it excludes these things!

I think we need to fix OD 2.1 to clarify that what is considered an Open
Format depends on the type of content. Obviously, a JPEG screenshot of a
webpage is not an Open Format for the webpage content, but HTML is. But
we cannot say that a JPEG photograph is non-Open format. We could say
that Open Data specifically should not be HTML? but I'm not certain
about that bit.

This absolutely must be addressed and clarified.

FWIW, I collected some initial bits about what qualifies as Open Format
at https://snowdrift.coop/p/snowdrift/w/en/formats-repositories and in
that case it is listed by the sort of project we're talking about. I
would love to see this more formally included in the OD.

Best,
Aaron

On 04/21/2015 06:18 AM, Stephen Gates wrote:
> Hello Open Knowledge and Open Data Institute friends,
> 
> I would like to explore the possibility of aligning the Open Definition
> <http://opendefinition.org/od/>, Open Data Census
> <http://census.okfn.org> and Open Data Certificates
> <https://certificates.theodi.org> definitions for Open Format. This
> would enable the Census, Certificate and other open data tools to refer
> to the Open Definition for a definition of Open Format, in the same way
> they currently do for Open Licences.
> 
> To extend this concept further, I would like to mirror the Conformant
> Licenses <http://opendefinition.org/licenses/> page in the Open
> Definition with a Conformant Formats page. This would provide a list of
> file formats that conform with the Open Format definition. New formats
> could be submitted for assessment. Common formats (e.g. XML, JSON, KML,
> CSV, etc.) would be seeded on the page. Similar to the non-conformant
> licences <http://opendefinition.org/licenses/nonconformant/>  partially
> conforming formats could also be captured (e.g. XLS, SHP). This would
> cater for the spectrum of open file formats proposed by Tim Burners-Lee
> in his 5 star scheme <http://5stardata.info>.
> 
> 
> The respective definitions or help text are:
> 
> *Open Definition* draft 2.1
> https://github.com/okfn/opendefinition/blob/master/source/open-definition-2.1-dev.markdown 
> 
> The *work*/must/be machine-readable and provided in an open format. An
> open format is one which places no restrictions, monetary or otherwise,
> upon its use and can be fully processed with at least one
> free/libre/open-source software tool. Data /should/be provided in bulk
> where possible.
> 
> *
> *
> 
> *Open Data Census* 
> 
> see format, machine readable and bulk rows in Google Sheet,
>  https://docs.google.com/spreadsheet/ccc?key=0AqR8dXc6Ji4JdFI0QkpGUEZyS0wxYWtLdG1nTk9zU3c&usp=drive_web#gid=0
> 
> *Format*:
> This question describes the form that the data is available in. For
> example, for tabular data it might be: Excel, CSV, HTML or even PDF. For
> geodata it might be shapefiles, geojson or something else. If available
> in multiple formats, the format descriptors are listed separated with
> commas. Any further information is put in the comments section.
> 
> *Machine Readable*:
> Files are digital, yes, but not all can be processed or parsed easily by
> a computer. In order to answer this question, you would need to look at
> the datasets file type.
> 
> As a rule of thumb the following file types are machine readable:
> 
> - XLS
> - CSV
> - JSON
> - XML
> 
> If the files are in the following formats, the are NOT machine readable:
> 
> - HTML
> - PDF
> - DOC
> - GIF
> - JPEG
> - PPT
> 
> If you have a different file type and you don?t know if it?s machine
> readable or not, send an email to the Open Data Census list.
> 
> *Bulk*:
> Data is available in bulk if the whole dataset can be downloaded easily.
> It is considered non-bulk if the citizens are limited to getting parts
> of the dataset through an online interface.
> 
> For example, if restricted to querying a web form and retrieving a few
> results at a time from a very large database.
> 
> *
> *
> *
> Open Data Certificates*
> 
> Question: Is this data in a standard open format?
> 
> Help Text: Open standards are created through a fair, transparent and
> collaborative process. Anyone can implement them and there?s lots of
> support so it?s easier for you to share data with more people. For
> example, XML, CSV and JSON are open standards. _Read more_? (links
> to https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/183962/Open-Standards-Principles-FINAL.pdf)*
> *
> 
> 
> *Proposed changes*
> *A harmonised definition*
> 
> The *work* /must/be machine-readable and provided in an open format. An
> open format is one which places no restrictions, monetary or otherwise,
> upon its use and can be fully processed with at least one
> free/libre/open-source software tool.
> 
> In addition:
> - Data /should/ be provided in bulk, i.e. the whole dataset can be
> downloaded easily.
> - An open format /should/ be documented so it can be freely implemented
> by others.
> - An open format /should/ be defined through a fair, transparent and
> collaborative process.
> 
> *Open Data Census and Open Data Certificates*
> Adjust questions and help text to reference the Open Format definition
> and/or conformant licenses page.
> 
> *Open Definition site*
> - C
> onsider changing the page names from ?Conformant Licences? and
> ?Conformant Formats? to ?Open Licences? and ?Open Formats?. 
> - Delete the open format definition page
> <http://opendefinition.org/ofd/>. It is replaced by the Open Formats
> page and the updated Open Definition.
> 
> 
> 
> *What do you think? *
> Is this worth progressing? Could this extend to Open APIs like Web Map
> Services (WMS)?
> 
> 
> thanks
> 
> Stephen Gates
> (localiser of the Open Data Census and Open Data Certificates in Australia)
> 
> 
> 
> 
> _______________________________________________
> od-discuss mailing list
> od-discuss at lists.okfn.org
> https://lists.okfn.org/mailman/listinfo/od-discuss
> Unsubscribe: https://lists.okfn.org/mailman/options/od-discuss
> 

From andrew.stott at dirdigeng.com  Tue Apr 21 18:16:28 2015
From: andrew.stott at dirdigeng.com (Andrew Stott)
Date: Tue, 21 Apr 2015 18:16:28 +0000
Subject: [od-discuss] A harmonised Open Format definition
In-Reply-To: <55367B3D.5020903@riseup.net>
References: <4A596E03-6C18-4C70-AF14-A3C4A80BE903@me.com>
 <55367B3D.5020903@riseup.net>
Message-ID: <032301d07c5f$48857eb0$d9907c10$@dirdigeng.com>

I had been puzzling over some of the same issues as Aaron.

 

A set of PNG format files would be a re-usable way of sharing digital images
of  paintings in a gallery's collection but it would not be an (easily)
re-usable way of sharing a national budget. 

 

We also need to be careful about terms like "machine-readable" - a PNG file
of a national budget is machine-readable (or, at least, more readable by a
machine than by a human!) but its machine-readability does not make the data
in it easily reusable. 

 

HTML illustrates a  further difficulty - the reusability of a dataset may
depend on how it is encoded in HTML - if it is just text then it is more
difficult to parse programmatically than if it structured with semantic
tagging. (Similarly there is some pretty tricky XML around for the same
reason.)

 

A lot of work was done a few years ago on the definition of an "Open
Standard", including a legal text that a number of Members of the European
Parliament tried to insert into EU law. There is a link between that work
and the Open Format initiative.

 

-----Original Message-----
From: od-discuss [mailto:od-discuss-bounces at lists.okfn.org] On Behalf Of
Aaron Wolf
Sent: 21 April 2015 17:31
To: od-discuss at lists.okfn.org
Subject: Re: [od-discuss] A harmonised Open Format definition

 

I think this concept is excellent, the consolidation and the clarification
of having a page of recognized Open formats.

 

Your points here bring up a serious problem though.

 

If HTML and JPEG formats are considered non-machine-readable then we
absolutely *have* to *remove* the machine-readable requirement from the Open
Definition. This is a very serious issue. The OD covers thing like
photographs and other images along with stuff like the writings on a blog.
It is absolutely unacceptable to have the "machine-readable" part in the
requirements for format in the OD if it excludes these things!

 

I think we need to fix OD 2.1 to clarify that what is considered an Open
Format depends on the type of content. Obviously, a JPEG screenshot of a
webpage is not an Open Format for the webpage content, but HTML is. But we
cannot say that a JPEG photograph is non-Open format. We could say that Open
Data specifically should not be HTML. but I'm not certain about that bit.

 

This absolutely must be addressed and clarified.

 

FWIW, I collected some initial bits about what qualifies as Open Format at
<https://snowdrift.coop/p/snowdrift/w/en/formats-repositories>
https://snowdrift.coop/p/snowdrift/w/en/formats-repositories and in that
case it is listed by the sort of project we're talking about. I would love
to see this more formally included in the OD.

 

Best,

Aaron

 

On 04/21/2015 06:18 AM, Stephen Gates wrote:

> Hello Open Knowledge and Open Data Institute friends,

> 

> I would like to explore the possibility of aligning the Open 

> Definition < <http://opendefinition.org/od/>
http://opendefinition.org/od/>, Open Data Census 

> < <http://census.okfn.org> http://census.okfn.org> and Open Data
Certificates 

> < <https://certificates.theodi.org> https://certificates.theodi.org>
definitions for Open Format. This 

> would enable the Census, Certificate and other open data tools to 

> refer to the Open Definition for a definition of Open Format, in the 

> same way they currently do for Open Licences.

> 

> To extend this concept further, I would like to mirror the Conformant 

> Licenses < <http://opendefinition.org/licenses/>
http://opendefinition.org/licenses/> page in the Open 

> Definition with a Conformant Formats page. This would provide a list 

> of file formats that conform with the Open Format definition. New 

> formats could be submitted for assessment. Common formats (e.g. XML, 

> JSON, KML, CSV, etc.) would be seeded on the page. Similar to the 

> non-conformant licences 

> < <http://opendefinition.org/licenses/nonconformant/>
http://opendefinition.org/licenses/nonconformant/>  partially 

> conforming formats could also be captured (e.g. XLS, SHP). This would 

> cater for the spectrum of open file formats proposed by Tim Burners-Lee in
his 5 star scheme < <http://5stardata.info> http://5stardata.info>.

> 

> 

> The respective definitions or help text are:

> 

> *Open Definition* draft 2.1

>  <https://github.com/okfn/opendefinition/blob/master/source/open-definit>
https://github.com/okfn/opendefinition/blob/master/source/open-definit

> ion-2.1-dev.markdown

> 

> The *work*/must/be machine-readable and provided in an open format. An 

> open format is one which places no restrictions, monetary or 

> otherwise, upon its use and can be fully processed with at least one 

> free/libre/open-source software tool. Data /should/be provided in bulk 

> where possible.

> 

> *

> *

> 

> *Open Data Census*

> 

> see format, machine readable and bulk rows in Google Sheet,

>  

>  <https://docs.google.com/spreadsheet/ccc?key=0AqR8dXc6Ji4JdFI0QkpGUEZyS>
https://docs.google.com/spreadsheet/ccc?key=0AqR8dXc6Ji4JdFI0QkpGUEZyS

> 0wxYWtLdG1nTk9zU3c&usp=drive_web#gid=0

> 

> *Format*:

> This question describes the form that the data is available in. For 

> example, for tabular data it might be: Excel, CSV, HTML or even PDF. 

> For geodata it might be shapefiles, geojson or something else. If 

> available in multiple formats, the format descriptors are listed 

> separated with commas. Any further information is put in the comments
section.

> 

> *Machine Readable*:

> Files are digital, yes, but not all can be processed or parsed easily 

> by a computer. In order to answer this question, you would need to 

> look at the datasets file type.

> 

> As a rule of thumb the following file types are machine readable:

> 

> - XLS

> - CSV

> - JSON

> - XML

> 

> If the files are in the following formats, the are NOT machine readable:

> 

> - HTML

> - PDF

> - DOC

> - GIF

> - JPEG

> - PPT

> 

> If you have a different file type and you don't know if it's machine 

> readable or not, send an email to the Open Data Census list.

> 

> *Bulk*:

> Data is available in bulk if the whole dataset can be downloaded easily.

> It is considered non-bulk if the citizens are limited to getting parts 

> of the dataset through an online interface.

> 

> For example, if restricted to querying a web form and retrieving a few 

> results at a time from a very large database.

> 

> *

> *

> *

> Open Data Certificates*

> 

> Question: Is this data in a standard open format?

> 

> Help Text: Open standards are created through a fair, transparent and 

> collaborative process. Anyone can implement them and there's lots of 

> support so it's easier for you to share data with more people. For 

> example, XML, CSV and JSON are open standards. _Read more_. (links to 

>  <https://www.gov.uk/government/uploads/system/uploads/attachment_data/f>
https://www.gov.uk/government/uploads/system/uploads/attachment_data/f

> ile/183962/Open-Standards-Principles-FINAL.pdf)*

> *

> 

> 

> *Proposed changes*

> *A harmonised definition*

> 

> The *work* /must/be machine-readable and provided in an open format. 

> An open format is one which places no restrictions, monetary or 

> otherwise, upon its use and can be fully processed with at least one 

> free/libre/open-source software tool.

> 

> In addition:

> - Data /should/ be provided in bulk, i.e. the whole dataset can be 

> downloaded easily.

> - An open format /should/ be documented so it can be freely 

> implemented by others.

> - An open format /should/ be defined through a fair, transparent and 

> collaborative process.

> 

> *Open Data Census and Open Data Certificates* Adjust questions and 

> help text to reference the Open Format definition and/or conformant 

> licenses page.

> 

> *Open Definition site*

> - C

> onsider changing the page names from "Conformant Licences" and 

> "Conformant Formats" to "Open Licences" and "Open Formats".

> - Delete the open format definition page 

> < <http://opendefinition.org/ofd/> http://opendefinition.org/ofd/>. It is
replaced by the Open Formats 

> page and the updated Open Definition.

> 

> 

> 

> *What do you think? *

> Is this worth progressing? Could this extend to Open APIs like Web Map 

> Services (WMS)?

> 

> 

> thanks

> 

> Stephen Gates

> (localiser of the Open Data Census and Open Data Certificates in 

> Australia)

> 

> 

> 

> 

> _______________________________________________

> od-discuss mailing list

>  <mailto:od-discuss at lists.okfn.org> od-discuss at lists.okfn.org

>  <https://lists.okfn.org/mailman/listinfo/od-discuss>
https://lists.okfn.org/mailman/listinfo/od-discuss

> Unsubscribe:  <https://lists.okfn.org/mailman/options/od-discuss>
https://lists.okfn.org/mailman/options/od-discuss

> 

_______________________________________________

od-discuss mailing list

 <mailto:od-discuss at lists.okfn.org> od-discuss at lists.okfn.org

 <https://lists.okfn.org/mailman/listinfo/od-discuss>
https://lists.okfn.org/mailman/listinfo/od-discuss

Unsubscribe:  <https://lists.okfn.org/mailman/options/od-discuss>
https://lists.okfn.org/mailman/options/od-discuss


-------------- next part --------------
An HTML attachment was scrubbed...
URL: <http://lists.okfn.org/pipermail/od-discuss/attachments/20150421/f63aadbb/attachment-0001.html>

From b.appleyard at ausgoal.gov.au  Tue Apr 21 21:36:45 2015
From: b.appleyard at ausgoal.gov.au (Baden Appleyard)
Date: Wed, 22 Apr 2015 07:36:45 +1000
Subject: [od-discuss] A harmonised Open Format definition
In-Reply-To: <4A596E03-6C18-4C70-AF14-A3C4A80BE903@me.com>
References: <4A596E03-6C18-4C70-AF14-A3C4A80BE903@me.com>
Message-ID: <CA+ziCe7p162=rLdS9mrgZjOSvov92PH296TkBBUX9FcPcfq3qg@mail.gmail.com>

Hi Stephen,

I agree.

Cheers

b


________________
*Baden M Appleyard*
National Programme Director
Australian Governments' Open Access and Licensing Programme (AusGOAL)
Mobile: +61(0)459 824 061
Linkedin: http://au.linkedin.com/in/badenappleyard

AusGOAL
Visit our Website <http://www.ausgoal.gov.au> | Like and Share us on
Facebook <https://www.facebook.com/AusGOAL> | Join our LinkedIn Group
<http://linkd.in/oq5L3u> | Follow Us on Twitter: @AusGOAL
<https://twitter.com/#!/AusGOAL> | +1 on Google Plus
<https://plus.google.com/u/0/b/108169778015177255341/108169778015177255341/posts/p/pub>
*New:*  *AusGOAL is now the Creative Commons Affiliate in Australia for
Publicly Funded Information.*


On Tue, Apr 21, 2015 at 11:18 PM, Stephen Gates <stephen.gates at me.com>
wrote:

> Hello Open Knowledge and Open Data Institute friends,
>
> I would like to explore the possibility of aligning the Open Definition
> <http://opendefinition.org/od/>, Open Data Census <http://census.okfn.org>
>  and Open Data Certificates <https://certificates.theodi.org> definitions
> for Open Format. This would enable the Census, Certificate and other open
> data tools to refer to the Open Definition for a definition of Open Format,
> in the same way they currently do for Open Licences.
>
> To extend this concept further, I would like to mirror the Conformant
> Licenses <http://opendefinition.org/licenses/> page in the Open
> Definition with a Conformant Formats page. This would provide a list of
> file formats that conform with the Open Format definition. New formats
> could be submitted for assessment. Common formats (e.g. XML, JSON, KML,
> CSV, etc.) would be seeded on the page. Similar to the non-conformant
> licences <http://opendefinition.org/licenses/nonconformant/>  partially
> conforming formats could also be captured (e.g. XLS, SHP). This would cater
> for the spectrum of open file formats proposed by Tim Burners-Lee in his 5
> star scheme <http://5stardata.info>.
>
>
> The respective definitions or help text are:
>
> *Open Definition* draft 2.1
>
> https://github.com/okfn/opendefinition/blob/master/source/open-definition-2.1-dev.markdown
>
>
> The *work* *must* be machine-readable and provided in an open format. An
> open format is one which places no restrictions, monetary or otherwise,
> upon its use and can be fully processed with at least one
> free/libre/open-source software tool. Data *should* be provided in bulk
> where possible.
>
>
> *Open Data Census*
>
> see format, machine readable and bulk rows in Google Sheet,
> https://docs.google.com/spreadsheet/ccc?key=0AqR8dXc6Ji4JdFI0QkpGUEZyS0wxYWtLdG1nTk9zU3c&usp=drive_web#gid=0
> *Format*:
> This question describes the form that the data is available in. For
> example, for tabular data it might be: Excel, CSV, HTML or even PDF. For
> geodata it might be shapefiles, geojson or something else. If available in
> multiple formats, the format descriptors are listed separated with commas.
> Any further information is put in the comments section.
>
> *Machine Readable*:
> Files are digital, yes, but not all can be processed or parsed easily by a
> computer. In order to answer this question, you would need to look at the
> datasets file type.
>
> As a rule of thumb the following file types are machine readable:
>
> - XLS
> - CSV
> - JSON
> - XML
>
> If the files are in the following formats, the are NOT machine readable:
>
> - HTML
> - PDF
> - DOC
> - GIF
> - JPEG
> - PPT
>
> If you have a different file type and you don?t know if it?s machine
> readable or not, send an email to the Open Data Census list.
>
> *Bulk*:
> Data is available in bulk if the whole dataset can be downloaded easily.
> It is considered non-bulk if the citizens are limited to getting parts of
> the dataset through an online interface.
>
> For example, if restricted to querying a web form and retrieving a few
> results at a time from a very large database.
>
>
> *Open Data Certificates*
>
> Question: Is this data in a standard open format?
> Help Text: Open standards are created through a fair, transparent and
> collaborative process. Anyone can implement them and there?s lots of
> support so it?s easier for you to share data with more people. For example,
> XML, CSV and JSON are open standards. *Read more*? (links to
> https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/183962/Open-Standards-Principles-FINAL.pdf
> )
>
>
> *Proposed changes*
> *A harmonised definition*
>
> The *work* *must* be machine-readable and provided in an open format. An
> open format is one which places no restrictions, monetary or otherwise,
> upon its use and can be fully processed with at least one
> free/libre/open-source software tool.
> In addition:
> - Data *should* be provided in bulk, i.e. the whole dataset can be
> downloaded easily.
> - An open format *should* be documented so it can be freely implemented
> by others.
> - An open format *should* be defined through a fair, transparent and
> collaborative process.
>
>  *Open Data Census and Open Data Certificates*
> Adjust questions and help text to reference the Open Format definition
> and/or conformant licenses page.
>
> *Open Definition site*
> - C
> onsider changing the page names from ?Conformant Licences? and ?Conformant
> Formats? to ?Open Licences? and ?Open Formats?.
> - Delete the open format definition page <http://opendefinition.org/ofd/>.
> It is replaced by the Open Formats page and the updated Open Definition.
>
>
>
> *What do you think? *
> Is this worth progressing? Could this extend to Open APIs like Web Map
> Services (WMS)?
>
>
> thanks
>
> Stephen Gates
> (localiser of the Open Data Census and Open Data Certificates in Australia)
>
>
>
> _______________________________________________
> od-discuss mailing list
> od-discuss at lists.okfn.org
> https://lists.okfn.org/mailman/listinfo/od-discuss
> Unsubscribe: https://lists.okfn.org/mailman/options/od-discuss
>
>
-------------- next part --------------
An HTML attachment was scrubbed...
URL: <http://lists.okfn.org/pipermail/od-discuss/attachments/20150422/015fe086/attachment.html>

From stephen.gates at me.com  Wed Apr 22 06:09:48 2015
From: stephen.gates at me.com (Stephen Gates)
Date: Wed, 22 Apr 2015 16:09:48 +1000
Subject: [od-discuss] A harmonised Open Format definition
In-Reply-To: <mailman.3975.1429641094.20065.od-discuss@lists.okfn.org>
References: <mailman.3975.1429641094.20065.od-discuss@lists.okfn.org>
Message-ID: <A49EF840-02BE-4BD9-8784-541E2D3A6E2D@me.com>

 
Hi Andrew and Aaron,
 
Thanks for your feedback. 
 
If I can summarise:
?         The Open Definition covers more than just data, hence the definition of Open Format needs to address all types of works, not just data.
?         Data may be open according to the 5 star scheme but it is not convenient to use (e.g. a pdf of a budget). 
?         We must encourage publishers to use formats that simplify reuse.

I also noticed that 1.2 Access mentions the work ?shall be available as a whole? and ?downloadable?.  By adding ?in bulk? you can remove the requirement from section 1.3. I?m not clear on the strength of ?shall? here. W3C states:

The key words must, must not, required, should, should not, recommended, may, and optional in this specification are to be interpreted as described in [RFC2119].
 
Lastly I found some best practices on selecting file formats for academic research.

Below is my attempt to address these concerns.
1.2 Access
The work must be available as a whole and at no more than a reasonable one-time reproduction cost, preferably downloadable in bulk via the Internet without charge. Any additional information necessary for license compliance (such as names of contributors required for compliance with attribution requirements) must also accompany the work.
1.3 Open Format 
The work must be distributed in an open format that is appropriate for its media type to maximise the opportunity for reuse. An open format is one that allows the work to be fully performed or processed with no restriction.

An open format must:
?         have no restrictions, monetary or otherwise, upon its use.
?         be machine-readable and able to be fully processed with at least one free/libre/open-source software tool.

An open format should:
?         be documented so it can be freely implemented by others.
?         be defined through a fair, transparent and collaborative process.
?         be widely used and accepted as best practice within your discipline or other user communities.
?         be lossless and uncompressed so all the original detail is retained.

Open Format definition page 
Describe:
?         The rationale behind our carefully choosen words e.g.
http://www.griffith.edu.au/__data/assets/pdf_file/0009/528993/Best_Practice_Guidelines.pdf
http://www.ands.org.au/guides/file-formats-working.html
?         Describe comformant Open Formats for Data, Image, Text, Font, Music, Video, ?

 

Thanks
Stephen Gates 

> On 22 Apr 2015, at 4:31 am, od-discuss-request at lists.okfn.org wrote:
> 
> Send od-discuss mailing list submissions to
>    od-discuss at lists.okfn.org
> 
> To subscribe or unsubscribe via the World Wide Web, visit
>    https://lists.okfn.org/mailman/listinfo/od-discuss
> or, via email, send a message with subject or body 'help' to
>    od-discuss-request at lists.okfn.org
> 
> You can reach the person managing the list at
>    od-discuss-owner at lists.okfn.org
> 
> When replying, please edit your Subject line so it is more specific
> than "Re: Contents of od-discuss digest..."
> Today's Topics:
> 
>   1. Re: A harmonised Open Format definition (Aaron Wolf)
>   2. Re: A harmonised Open Format definition (Andrew Stott)
> <mime-attachment>
> <mime-attachment>
> _______________________________________________
> od-discuss mailing list
> od-discuss at lists.okfn.org
> https://lists.okfn.org/mailman/listinfo/od-discuss
> Unsubscribe: https://lists.okfn.org/mailman/options/od-discuss
-------------- next part --------------
An HTML attachment was scrubbed...
URL: <http://lists.okfn.org/pipermail/od-discuss/attachments/20150422/6d8fd9aa/attachment-0001.html>

From rufus.pollock at okfn.org  Wed Apr 22 07:41:02 2015
From: rufus.pollock at okfn.org (Rufus Pollock)
Date: Wed, 22 Apr 2015 09:41:02 +0200
Subject: [od-discuss] A harmonised Open Format definition
In-Reply-To: <032301d07c5f$48857eb0$d9907c10$@dirdigeng.com>
References: <4A596E03-6C18-4C70-AF14-A3C4A80BE903@me.com>
 <55367B3D.5020903@riseup.net>
 <032301d07c5f$48857eb0$d9907c10$@dirdigeng.com>
Message-ID: <CAKssCpNTTG6QA1UKOw+sKzsQsepBchtZqBtRDHXk7QQ1UgC26A@mail.gmail.com>

On 21 April 2015 at 20:16, Andrew Stott <andrew.stott at dirdigeng.com> wrote:

> I had been puzzling over some of the same issues as Aaron.
>
>
>
> A set of PNG format files would be a re-usable way of sharing digital
> images of  paintings in a gallery's collection but it would not be an
> (easily) re-usable way of sharing a national budget.
>
>
>
> We also need to be careful about terms like "machine-readable" - a PNG
> file of a national budget is machine-readable (or, at least, more readable
> by a machine than by a human!) but its machine-readability does not make
> the data in it easily reusable.
>
This is a good point. We tried to come up with a more precise definition of
machine readability a couple of years back:

Material (data or content) is machine readable if it is in a format that
can be easily processed by a computer.

Non-digital material (for example printed or hand-written documents) is by
its non-digital nature not machine-readable. But even digital material need
not be machine-readable. For example, consider a PDF document containing
tables of data. These are definitely digital but are not machine-readable
because a computer would struggle to access the tabular information (even
though they are very human readable!). The equivalent tables in a format
such as a spreadsheet would be machine readable.

As another example scans (photographs) of text are not machine-readable
(but are human readable!) but the equivalent text in a format such as a
simple ASCII text file or a text-processing format such as Microsoft Word
file is machine readable.

Note: The appropriate machine readable format may vary by type ? so, for
example, machine readable form for geographic data may be different than
for tabular data.

http://webarchive.okfn.org/okfn.org/201404/opendata/glossary/#machine-readable

Regards,

Rufus

> HTML illustrates a  further difficulty - the reusability of a dataset may
> depend on how it is encoded in HTML - if it is just text then it is more
> difficult to parse programmatically than if it structured with semantic
> tagging. (Similarly there is some pretty tricky XML around for the same
> reason.)
>
>
>
> A lot of work was done a few years ago on the definition of an "Open
> Standard", including a legal text that a number of Members of the European
> Parliament tried to insert into EU law. There is a link between that work
> and the Open Format initiative.
>
>
>
> -----Original Message-----
> From: od-discuss [mailto:od-discuss-bounces at lists.okfn.org] On Behalf Of
> Aaron Wolf
> Sent: 21 April 2015 17:31
> To: od-discuss at lists.okfn.org
> Subject: Re: [od-discuss] A harmonised Open Format definition
>
>
>
> I think this concept is excellent, the consolidation and the clarification
> of having a page of recognized Open formats.
>
>
>
> Your points here bring up a serious problem though.
>
>
>
> If HTML and JPEG formats are considered non-machine-readable then we
> absolutely *have* to *remove* the machine-readable requirement from the
> Open Definition. This is a very serious issue. The OD covers thing like
> photographs and other images along with stuff like the writings on a blog.
> It is absolutely unacceptable to have the "machine-readable" part in the
> requirements for format in the OD if it excludes these things!
>
>
>
> I think we need to fix OD 2.1 to clarify that what is considered an Open
> Format depends on the type of content. Obviously, a JPEG screenshot of a
> webpage is not an Open Format for the webpage content, but HTML is. But we
> cannot say that a JPEG photograph is non-Open format. We could say that
> Open Data specifically should not be HTML? but I'm not certain about that
> bit.
>
>
>
> This absolutely must be addressed and clarified.
>
>
>
> FWIW, I collected some initial bits about what qualifies as Open Format at
> https://snowdrift.coop/p/snowdrift/w/en/formats-repositories and in that
> case it is listed by the sort of project we're talking about. I would love
> to see this more formally included in the OD.
>
>
>
> Best,
>
> Aaron
>
>
>
> On 04/21/2015 06:18 AM, Stephen Gates wrote:
>
> > Hello Open Knowledge and Open Data Institute friends,
>
> >
>
> > I would like to explore the possibility of aligning the Open
>
> > Definition <http://opendefinition.org/od/>, Open Data Census
>
> > <http://census.okfn.org> and Open Data Certificates
>
> > <https://certificates.theodi.org> definitions for Open Format. This
>
> > would enable the Census, Certificate and other open data tools to
>
> > refer to the Open Definition for a definition of Open Format, in the
>
> > same way they currently do for Open Licences.
>
> >
>
> > To extend this concept further, I would like to mirror the Conformant
>
> > Licenses <http://opendefinition.org/licenses/> page in the Open
>
> > Definition with a Conformant Formats page. This would provide a list
>
> > of file formats that conform with the Open Format definition. New
>
> > formats could be submitted for assessment. Common formats (e.g. XML,
>
> > JSON, KML, CSV, etc.) would be seeded on the page. Similar to the
>
> > non-conformant licences
>
> > <http://opendefinition.org/licenses/nonconformant/>  partially
>
> > conforming formats could also be captured (e.g. XLS, SHP). This would
>
> > cater for the spectrum of open file formats proposed by Tim Burners-Lee
> in his 5 star scheme <http://5stardata.info>.
>
> >
>
> >
>
> > The respective definitions or help text are:
>
> >
>
> > *Open Definition* draft 2.1
>
> > https://github.com/okfn/opendefinition/blob/master/source/open-definit
>
> > ion-2.1-dev.markdown
>
> >
>
> > The *work*/must/be machine-readable and provided in an open format. An
>
> > open format is one which places no restrictions, monetary or
>
> > otherwise, upon its use and can be fully processed with at least one
>
> > free/libre/open-source software tool. Data /should/be provided in bulk
>
> > where possible.
>
> >
>
> > *
>
> > *
>
> >
>
> > *Open Data Census*
>
> >
>
> > see format, machine readable and bulk rows in Google Sheet,
>
> >
>
> > https://docs.google.com/spreadsheet/ccc?key=0AqR8dXc6Ji4JdFI0QkpGUEZyS
>
> > 0wxYWtLdG1nTk9zU3c&usp=drive_web#gid=0
>
> >
>
> > *Format*:
>
> > This question describes the form that the data is available in. For
>
> > example, for tabular data it might be: Excel, CSV, HTML or even PDF.
>
> > For geodata it might be shapefiles, geojson or something else. If
>
> > available in multiple formats, the format descriptors are listed
>
> > separated with commas. Any further information is put in the comments
> section.
>
> >
>
> > *Machine Readable*:
>
> > Files are digital, yes, but not all can be processed or parsed easily
>
> > by a computer. In order to answer this question, you would need to
>
> > look at the datasets file type.
>
> >
>
> > As a rule of thumb the following file types are machine readable:
>
> >
>
> > - XLS
>
> > - CSV
>
> > - JSON
>
> > - XML
>
> >
>
> > If the files are in the following formats, the are NOT machine readable:
>
> >
>
> > - HTML
>
> > - PDF
>
> > - DOC
>
> > - GIF
>
> > - JPEG
>
> > - PPT
>
> >
>
> > If you have a different file type and you don?t know if it?s machine
>
> > readable or not, send an email to the Open Data Census list.
>
> >
>
> > *Bulk*:
>
> > Data is available in bulk if the whole dataset can be downloaded easily.
>
> > It is considered non-bulk if the citizens are limited to getting parts
>
> > of the dataset through an online interface.
>
> >
>
> > For example, if restricted to querying a web form and retrieving a few
>
> > results at a time from a very large database.
>
> >
>
> > *
>
> > *
>
> > *
>
> > Open Data Certificates*
>
> >
>
> > Question: Is this data in a standard open format?
>
> >
>
> > Help Text: Open standards are created through a fair, transparent and
>
> > collaborative process. Anyone can implement them and there?s lots of
>
> > support so it?s easier for you to share data with more people. For
>
> > example, XML, CSV and JSON are open standards. _Read more_? (links to
>
> > https://www.gov.uk/government/uploads/system/uploads/attachment_data/f
>
> > ile/183962/Open-Standards-Principles-FINAL.pdf)*
>
> > *
>
> >
>
> >
>
> > *Proposed changes*
>
> > *A harmonised definition*
>
> >
>
> > The *work* /must/be machine-readable and provided in an open format.
>
> > An open format is one which places no restrictions, monetary or
>
> > otherwise, upon its use and can be fully processed with at least one
>
> > free/libre/open-source software tool.
>
> >
>
> > In addition:
>
> > - Data /should/ be provided in bulk, i.e. the whole dataset can be
>
> > downloaded easily.
>
> > - An open format /should/ be documented so it can be freely
>
> > implemented by others.
>
> > - An open format /should/ be defined through a fair, transparent and
>
> > collaborative process.
>
> >
>
> > *Open Data Census and Open Data Certificates* Adjust questions and
>
> > help text to reference the Open Format definition and/or conformant
>
> > licenses page.
>
> >
>
> > *Open Definition site*
>
> > - C
>
> > onsider changing the page names from ?Conformant Licences? and
>
> > ?Conformant Formats? to ?Open Licences? and ?Open Formats?.
>
> > - Delete the open format definition page
>
> > <http://opendefinition.org/ofd/>. It is replaced by the Open Formats
>
> > page and the updated Open Definition.
>
> >
>
> >
>
> >
>
> > *What do you think? *
>
> > Is this worth progressing? Could this extend to Open APIs like Web Map
>
> > Services (WMS)?
>
> >
>
> >
>
> > thanks
>
> >
>
> > Stephen Gates
>
> > (localiser of the Open Data Census and Open Data Certificates in
>
> > Australia)
>
> >
>
> >
>
> >
>
> >
>
> > _______________________________________________
>
> > od-discuss mailing list
>
> > od-discuss at lists.okfn.org
>
> > https://lists.okfn.org/mailman/listinfo/od-discuss
>
> > Unsubscribe: https://lists.okfn.org/mailman/options/od-discuss
>
> >
>
> _______________________________________________
>
> od-discuss mailing list
>
> od-discuss at lists.okfn.org
>
> https://lists.okfn.org/mailman/listinfo/od-discuss
>
> Unsubscribe: https://lists.okfn.org/mailman/options/od-discuss
>
> _______________________________________________
> od-discuss mailing list
> od-discuss at lists.okfn.org
> https://lists.okfn.org/mailman/listinfo/od-discuss
> Unsubscribe: https://lists.okfn.org/mailman/options/od-discuss
>
>


-- 

*Rufus PollockFounder and President | skype: rufuspollock | @rufuspollock
<https://twitter.com/rufuspollock>Open Knowledge <http://okfn.org/> - see
how data can change the world**http://okfn.org/ <http://okfn.org/> | @okfn
<http://twitter.com/OKFN> | Open Knowledge on Facebook
<https://www.facebook.com/OKFNetwork> |  Blog <http://blog.okfn.org/>*
-------------- next part --------------
An HTML attachment was scrubbed...
URL: <http://lists.okfn.org/pipermail/od-discuss/attachments/20150422/3956acd1/attachment-0001.html>

From pm286 at cam.ac.uk  Wed Apr 22 08:01:23 2015
From: pm286 at cam.ac.uk (Peter Murray-Rust)
Date: Wed, 22 Apr 2015 09:01:23 +0100
Subject: [od-discuss] A harmonised Open Format definition
In-Reply-To: <CAKssCpNTTG6QA1UKOw+sKzsQsepBchtZqBtRDHXk7QQ1UgC26A@mail.gmail.com>
References: <4A596E03-6C18-4C70-AF14-A3C4A80BE903@me.com>
 <55367B3D.5020903@riseup.net>
 <032301d07c5f$48857eb0$d9907c10$@dirdigeng.com>
 <CAKssCpNTTG6QA1UKOw+sKzsQsepBchtZqBtRDHXk7QQ1UgC26A@mail.gmail.com>
Message-ID: <CAD2k14ODMRqRfysQNgH2oKpRiiaZs=iFTQM8CZ-C-_7xG2wvzQ@mail.gmail.com>

On Wed, Apr 22, 2015 at 8:41 AM, Rufus Pollock <rufus.pollock at okfn.org>
wrote:

> On 21 April 2015 at 20:16, Andrew Stott <andrew.stott at dirdigeng.com>
> wrote:
>
>>
>>
>> We also need to be careful about terms like "machine-readable" - a PNG
>> file of a national budget is machine-readable (or, at least, more readable
>> by a machine than by a human!) but its machine-readability does not make
>> the data in it easily reusable.
>>
>
This is a very important point but I don't think there is a simple answer
or term, and I think we have the opportunity to make a contribution.

I have struggled with this for 20 years (having been a facilitator of the
XML process (XML-DEV) and now actively involved in trying to develop
programs that "understand" PDF documents). I try to consider two categories
of disadvantaged "readers":
 * blind humans
 * machines

I have used the term "machine-readable" to mean that a stream of bits can
be read which can be displayed to a knowledgeable sighted  human and
potentially "understood" by them.

And "machine understandable" to mean that the machine can add some
significant meaning to the bits beyond simply displaying them on the
screen.

I also use "born digital" to mean documents created in a computer which
can, if properly transmitted without corruption, retain a significant part
of their meaning. Many of our problems come from born-digital documents
being dumbed down to PDF or TIF which destroys much or all of the
semantics. A similar problem happens when born-digital documents are
printed and then re-scanned.

Many processes today actively encourage the destruction of born-digital
content. Thus a student writes their thesis in Word or LaTeX and they are
required to transform it to PDF as the "archival" version. IMO this
avoidable action alone destroys 10 Billion dollars of scientific value per
year. Similar processes happen with government and companies. (I have
become involved in trying to "machine understand" the documents that
companies submit to Companies House).

Similar things happen with diagrams and graphs. They are born digital, as
vectors, and then destroyed into pixels PNG or (even worse) JPEG.

P




-- 
Peter Murray-Rust
Reader in Molecular Informatics
Unilever Centre, Dep. Of Chemistry
University of Cambridge
CB2 1EW, UK
+44-1223-763069
-------------- next part --------------
An HTML attachment was scrubbed...
URL: <http://lists.okfn.org/pipermail/od-discuss/attachments/20150422/8593f094/attachment.html>

From herb at dynamic-solutions.com  Wed Apr 22 15:32:35 2015
From: herb at dynamic-solutions.com (Herb Lainchbury)
Date: Wed, 22 Apr 2015 08:32:35 -0700
Subject: [od-discuss] A harmonised Open Format definition
In-Reply-To: <CAD2k14ODMRqRfysQNgH2oKpRiiaZs=iFTQM8CZ-C-_7xG2wvzQ@mail.gmail.com>
References: <4A596E03-6C18-4C70-AF14-A3C4A80BE903@me.com>
 <55367B3D.5020903@riseup.net>
 <032301d07c5f$48857eb0$d9907c10$@dirdigeng.com>
 <CAKssCpNTTG6QA1UKOw+sKzsQsepBchtZqBtRDHXk7QQ1UgC26A@mail.gmail.com>
 <CAD2k14ODMRqRfysQNgH2oKpRiiaZs=iFTQM8CZ-C-_7xG2wvzQ@mail.gmail.com>
Message-ID: <CA+Gq+xn1cSu4w=+92_mEn1yZ41xvX8n7f18BC9B5=HDkrRm41Q@mail.gmail.com>

I think this is a useful but difficult area, and it would be great if we
could make the format section of the OD more robust as a result.

Some years ago I worked on a rating system to rate the "useability" of open
data.  We called it the ODUI (Open Data Usability Index).  It was somewhat
crude, but we found it useful when explaining to publishers, why some
published material was more useable than other material.  The result of
using this index was that a dataset would end up with a certain number of
stars, from 1 to 5.
As part of this exercise we decided that because formats themselves can be
used suboptimally (as in the given examples in this thread), describing
open formats was not enough.  To get at what we wanted we created a
criteria group called "readability" and broke it down into four
sub-criteria.  They are:

1. Digital : The data is available electronically (as opposed to just
hard-copy print-outs)

2. Parse-able: The data can be parsed by a standard parser such as XML,
JSON, CSV

3. Open Format:
          YES = XML, JSON, CSV, SHP, SQL99, XHTML, PNG, SVG
          NO = PDF, Word, XLS, FLASH, PSD

4. Structured: The file is composed of regular structures such as rows and
columns, or objects, such that the various attributes represented by the
data are easily accessible with simple reusable program.
(e.g. CSV files with rows and columns with the first row representing the
column names)


It's the last one, "Structured" that speaks to using the format in a useful
way.

Breaking the idea of formats into these separate criteria proved useful to
help get at what we wanted from publishers.

Here is the original document: http://goo.gl/xGpLIs

Herb






On Wed, Apr 22, 2015 at 1:01 AM, Peter Murray-Rust <pm286 at cam.ac.uk> wrote:

>
>
> On Wed, Apr 22, 2015 at 8:41 AM, Rufus Pollock <rufus.pollock at okfn.org>
> wrote:
>
>> On 21 April 2015 at 20:16, Andrew Stott <andrew.stott at dirdigeng.com>
>> wrote:
>>
>>>
>>>
>>> We also need to be careful about terms like "machine-readable" - a PNG
>>> file of a national budget is machine-readable (or, at least, more readable
>>> by a machine than by a human!) but its machine-readability does not make
>>> the data in it easily reusable.
>>>
>>
> This is a very important point but I don't think there is a simple answer
> or term, and I think we have the opportunity to make a contribution.
>
> I have struggled with this for 20 years (having been a facilitator of the
> XML process (XML-DEV) and now actively involved in trying to develop
> programs that "understand" PDF documents). I try to consider two categories
> of disadvantaged "readers":
>  * blind humans
>  * machines
>
> I have used the term "machine-readable" to mean that a stream of bits can
> be read which can be displayed to a knowledgeable sighted  human and
> potentially "understood" by them.
>
> And "machine understandable" to mean that the machine can add some
> significant meaning to the bits beyond simply displaying them on the
> screen.
>
> I also use "born digital" to mean documents created in a computer which
> can, if properly transmitted without corruption, retain a significant part
> of their meaning. Many of our problems come from born-digital documents
> being dumbed down to PDF or TIF which destroys much or all of the
> semantics. A similar problem happens when born-digital documents are
> printed and then re-scanned.
>
> Many processes today actively encourage the destruction of born-digital
> content. Thus a student writes their thesis in Word or LaTeX and they are
> required to transform it to PDF as the "archival" version. IMO this
> avoidable action alone destroys 10 Billion dollars of scientific value per
> year. Similar processes happen with government and companies. (I have
> become involved in trying to "machine understand" the documents that
> companies submit to Companies House).
>
> Similar things happen with diagrams and graphs. They are born digital, as
> vectors, and then destroyed into pixels PNG or (even worse) JPEG.
>
> P
>
>
>
>
> --
> Peter Murray-Rust
> Reader in Molecular Informatics
> Unilever Centre, Dep. Of Chemistry
> University of Cambridge
> CB2 1EW, UK
> +44-1223-763069
>
> _______________________________________________
> od-discuss mailing list
> od-discuss at lists.okfn.org
> https://lists.okfn.org/mailman/listinfo/od-discuss
> Unsubscribe: https://lists.okfn.org/mailman/options/od-discuss
>
>


--
-------------- next part --------------
An HTML attachment was scrubbed...
URL: <http://lists.okfn.org/pipermail/od-discuss/attachments/20150422/3f298dff/attachment.html>

From pm286 at cam.ac.uk  Wed Apr 22 16:08:28 2015
From: pm286 at cam.ac.uk (Peter Murray-Rust)
Date: Wed, 22 Apr 2015 17:08:28 +0100
Subject: [od-discuss] A harmonised Open Format definition
In-Reply-To: <CA+Gq+xn1cSu4w=+92_mEn1yZ41xvX8n7f18BC9B5=HDkrRm41Q@mail.gmail.com>
References: <4A596E03-6C18-4C70-AF14-A3C4A80BE903@me.com>
 <55367B3D.5020903@riseup.net>
 <032301d07c5f$48857eb0$d9907c10$@dirdigeng.com>
 <CAKssCpNTTG6QA1UKOw+sKzsQsepBchtZqBtRDHXk7QQ1UgC26A@mail.gmail.com>
 <CAD2k14ODMRqRfysQNgH2oKpRiiaZs=iFTQM8CZ-C-_7xG2wvzQ@mail.gmail.com>
 <CA+Gq+xn1cSu4w=+92_mEn1yZ41xvX8n7f18BC9B5=HDkrRm41Q@mail.gmail.com>
Message-ID: <CAD2k14MKUDT4QefBi=y7Zr-q6jH9LU+dOxcjR0QcO5nFf_-XJg@mail.gmail.com>

On Wed, Apr 22, 2015 at 4:32 PM, Herb Lainchbury <herb at dynamic-solutions.com
> wrote:

> I think this is a useful but difficult area, and it would be great if we
> could make the format section of the OD more robust as a result.
>
> Some years ago I worked on a rating system to rate the "useability" of
> open data.  We called it the ODUI (Open Data Usability Index).  It was
> somewhat crude, but we found it useful when explaining to publishers, why
> some published material was more useable than other material.  The result
> of using this index was that a dataset would end up with a certain number
> of stars, from 1 to 5.
>

I think this is a useful approach.


> As part of this exercise we decided that because formats themselves can be
> used suboptimally (as in the given examples in this thread), describing
> open formats was not enough.
>

Yes. I like the "suboptimally". An XML document consisting of a base64 PNG
derived from a table is suboptimal. A PNG of a photograph of a bird is as
good as it gets. An Open Format has to make a reasonable effort to be as
semantic as possible.


> To get at what we wanted we created a criteria group called "readability"
> and broke it down into four sub-criteria.  They are:
>
> 1. Digital : The data is available electronically (as opposed to just
> hard-copy print-outs)
>
> 2. Parse-able: The data can be parsed by a standard parser such as XML,
> JSON, CSV
>

Agreed. I think this is a useful term. For example PDF is parse-able. It
doesn't guarantee that the results is interpretable. For example it may
have custom fonts instead of using Unicode. (I would insist on Unicode if
it's a reasonable approach in the context - I spend far too much time with
non-Unicode PDFs.


>
> 3. Open Format:
>           YES = XML, JSON, CSV, SHP, SQL99, XHTML, PNG, SVG
>           NO = PDF, Word, XLS, FLASH, PSD
>
>
I'd agree, but note that PDF and Word are ISO standards. Would we regard
ODT as Open? We need to be clear on terms.


> 4. Structured: The file is composed of regular structures such as rows and
> columns, or objects, such that the various attributes represented by the
> data are easily accessible with simple reusable program.
> (e.g. CSV files with rows and columns with the first row representing the
> column names)
>
>
I agree that structuring is critical.


>
> It's the last one, "Structured" that speaks to using the format in a
> useful way.
>
> Breaking the idea of formats into these separate criteria proved useful to
> help get at what we wanted from publishers.
>
> Here is the original document: http://goo.gl/xGpLIs
>
> Herb
>
>
>
>
>
>
> On Wed, Apr 22, 2015 at 1:01 AM, Peter Murray-Rust <pm286 at cam.ac.uk>
> wrote:
>
>>
>>
>> On Wed, Apr 22, 2015 at 8:41 AM, Rufus Pollock <rufus.pollock at okfn.org>
>> wrote:
>>
>>> On 21 April 2015 at 20:16, Andrew Stott <andrew.stott at dirdigeng.com>
>>> wrote:
>>>
>>>>
>>>>
>>>> We also need to be careful about terms like "machine-readable" - a PNG
>>>> file of a national budget is machine-readable (or, at least, more readable
>>>> by a machine than by a human!) but its machine-readability does not make
>>>> the data in it easily reusable.
>>>>
>>>
>> This is a very important point but I don't think there is a simple answer
>> or term, and I think we have the opportunity to make a contribution.
>>
>> I have struggled with this for 20 years (having been a facilitator of the
>> XML process (XML-DEV) and now actively involved in trying to develop
>> programs that "understand" PDF documents). I try to consider two categories
>> of disadvantaged "readers":
>>  * blind humans
>>  * machines
>>
>> I have used the term "machine-readable" to mean that a stream of bits can
>> be read which can be displayed to a knowledgeable sighted  human and
>> potentially "understood" by them.
>>
>> And "machine understandable" to mean that the machine can add some
>> significant meaning to the bits beyond simply displaying them on the
>> screen.
>>
>> I also use "born digital" to mean documents created in a computer which
>> can, if properly transmitted without corruption, retain a significant part
>> of their meaning. Many of our problems come from born-digital documents
>> being dumbed down to PDF or TIF which destroys much or all of the
>> semantics. A similar problem happens when born-digital documents are
>> printed and then re-scanned.
>>
>> Many processes today actively encourage the destruction of born-digital
>> content. Thus a student writes their thesis in Word or LaTeX and they are
>> required to transform it to PDF as the "archival" version. IMO this
>> avoidable action alone destroys 10 Billion dollars of scientific value per
>> year. Similar processes happen with government and companies. (I have
>> become involved in trying to "machine understand" the documents that
>> companies submit to Companies House).
>>
>> Similar things happen with diagrams and graphs. They are born digital, as
>> vectors, and then destroyed into pixels PNG or (even worse) JPEG.
>>
>> P
>>
>>
>>
>>
>> --
>> Peter Murray-Rust
>> Reader in Molecular Informatics
>> Unilever Centre, Dep. Of Chemistry
>> University of Cambridge
>> CB2 1EW, UK
>> +44-1223-763069
>>
>> _______________________________________________
>> od-discuss mailing list
>> od-discuss at lists.okfn.org
>> https://lists.okfn.org/mailman/listinfo/od-discuss
>> Unsubscribe: https://lists.okfn.org/mailman/options/od-discuss
>>
>>
>
>
> --
>
>
> _______________________________________________
> od-discuss mailing list
> od-discuss at lists.okfn.org
> https://lists.okfn.org/mailman/listinfo/od-discuss
> Unsubscribe: https://lists.okfn.org/mailman/options/od-discuss
>
>


-- 
Peter Murray-Rust
Reader in Molecular Informatics
Unilever Centre, Dep. Of Chemistry
University of Cambridge
CB2 1EW, UK
+44-1223-763069
-------------- next part --------------
An HTML attachment was scrubbed...
URL: <http://lists.okfn.org/pipermail/od-discuss/attachments/20150422/b49df536/attachment-0001.html>

From rob at robmyers.org  Thu Apr 23 03:32:18 2015
From: rob at robmyers.org (Rob Myers)
Date: Wed, 22 Apr 2015 20:32:18 -0700
Subject: [od-discuss] A harmonised Open Format definition
In-Reply-To: <4A596E03-6C18-4C70-AF14-A3C4A80BE903@me.com>
References: <4A596E03-6C18-4C70-AF14-A3C4A80BE903@me.com>
Message-ID: <553867C2.9000703@robmyers.org>

On 21/04/15 06:18 AM, Stephen Gates wrote:
> 
> The work must be machine-readable and provided in an open format

This is a good idea but the Open Definition refers to all kinds of
knowledge, not just to data.

Declaring HTML, PDF and bitmap image formats non-conformant would impact
on OER and other key forms of Open Knowledge that are released e.g. as
videos or as web sites. They would either be declared non-Open or have
to wrap themselves in an xml fig-leaf.

- Rob.


