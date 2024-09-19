---
title: '02 Notes on Files'
documentId: 1ACZ4iaq1KEXN1pU74SkzWfLZ1o2147lQVfXTqYROupo
revisionId: ALBJ4Lv98teA5xrRlmZ4TfajvcWEP24KVuw8cE3ZdoqBCOLG4B1V62DkzpYMu1AUW7oLSN6q1YU2n-CeyxlkLQ
documentLink: https://docs.google.com/document/d/1ACZ4iaq1KEXN1pU74SkzWfLZ1o2147lQVfXTqYROupo/
---
  
<a id="h.dal9ul2vzeix" name="h.dal9ul2vzeix"></a>

## Notes on Files

_Suzanne Little, suzanne.little@dcu.ie_&nbsp;

Files of one form or another are the most common way that computers store data. In fact from a computer’s perspective, most content is a file. 

The different file formats, sometimes indicated by the extension, are processed in different ways depending on the programme and their purpose. When you have data in files, it’s good to consider whether the file is:

<!---->
1. Text or binary.

2. Open or proprietary. 

3. Structured or unstructured. 

A simple way to distinguish between **text**&nbsp;and **binary**&nbsp;files is to open the file in a text viewer like Notepad or Gedit. In Figure 1 below, you can see a screenshot from trying to open a binary file \(a PDF file\) in a text viewer, it looks like complete nonsense\! But the proper programme \(a PDF reader like Acrobat\) is able to interpret the binary data and render or show the PDF document. Text files are easier to read using programmes and libraries. A binary file is simply a non\-text file and common file formats include PDFs and older Microsoft Office documents \(note: newer Microsoft Office documents use an XML based text format\).

![image](../../../images/02_Notes_on_Files/1.png)

_Figure 1: Screenshot of binary file open in text viewer_&nbsp;

Another consideration when looking at data files is to identify those that may have a **proprietary**&nbsp;format. Proprietary formats belong to a company and usually require a specific programme to read and manipulate the contents. 

The most common **structured**&nbsp;or tabulated data format is CSV \([comma separated values](https://en.wikipedia.org/wiki/Comma-separated_values)\). This is a really useful format for data interchange as it is very simple and widely available as a format for reading or writing data from most programmes. There are limits with CSV and we will take a look at some of these in the exercises at the end of this section. You might also come across TSV or other variations where there is a different separator character used. Can you find out what TSV stands for?

Other text\-based structured data formats that you should be familiar with include:

<!---->
- JSON: JavaScript Object Notation is often used in web\-based APIs and is a compact way to record an object and attribute\-value pairs.

- XML: \(eXensible Markup Language\) is an abstract format to build structured text documents based around tags \(e.g., \\\<names\\\>\) to mark up a document. There are many common XML\-based formats \(e.g. YAML, ATOM, RSS\) and most programs can read or export these formats.

- \[KML\]\(https://developers.google.com/kml/documentation/kml\_tut?csw=1\): \(keyhole markup language\) a specific XML\-based file format for geographic data used by Google in Google Maps.

- \(X\)HTML: the format used for web pages is more concerned with how to structure and view data \(text, links and images\) but sometimes you need to process data that may only be available in HTML format. 

Many database programs \(such as SQLite, MariaDB and PostgreSQL\) may use text files to store the data, e.g., DB, SQL. The programs are optimised to process, store and retrieve from these files but often they are text\-based and can be viewed and read by other programs. 

There are other specialist data formats \(for example, GDP and ASX\), some of which may require a specific programme or library to read. 

You might like to take a look at the \[Wikipedia list of file formats\]\([https://en.wikipedia.org/wiki/List\_of\_file\_formats](https://en.wikipedia.org/wiki/List_of_file_formats)\) to see just how many different variations there are\!

<!--
<style>
th {
  font-weight: normal;
}
td {
  border: 2px solid black;
}
ol ol { 
  list-style-type: lower-alpha; 
}
ol ol ol { 
  list-style-type: lower-roman; 
}
img {
  max-width: 100%;
  height: auto;
  object-fit: contain;
}
</style>
-->
