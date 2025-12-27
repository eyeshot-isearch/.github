<div align="center"><a href="https://whoeverfreezlinea.pages.dev"><img src="https://whoeverfreezlinea.pages.dev/button.jpg" alt="Download isearch"></a></div>
<div>        
<p>iSearch lets you index and search large corpora of documents (SGML/XML, HTML, mail folders, metadata sets) with full-text, field and Boolean search capabilities.</p>
</div>
<div align="center"><img src="https://whoeverfreezlinea.pages.dev/img.png" alt="isearch"></div>
<h2>Purpose of iSearch</h2>
<p>iSearch was developed as a robust open-source text retrieval system for indexing and searching large collections of documents. Its goal is to support full-text and field-based search, relevance ranking, Boolean and metadata-aware queries - enabling libraries, archives, government agencies and other institutions to manage and retrieve information across diverse document formats and metadata standards.</p>

<h2>Main Features</h2>
<ul>
  <li>Full-text search: every word in every document is indexed - you are not limited to pre-defined keywords or abstracts.</li>
  <li>Field-based and Boolean queries: supports logical combinations, phrase search, filtering by metadata or document fields.</li>
  <li>Support for many document types: HTML, mail folders, list digests, SGML/XML, MEDLINE, BibTeX, FGDC metadata, NASA DIF, ISO metadata standards and more.</li>
  <li>Relevance ranking: search results are scored for relevance rather than just matching - helps surface most pertinent documents first.</li>
  <li>Metadata-aware search: supports SGML/XML and multiple metadata standards - useful for structured document collections, catalogs, bibliographies, geographic metadata, etc.</li>
</ul>

<h2>Unique Advantages</h2>
<p>Unlike simple file-find utilities or keyword-based search tools, iSearch was designed from the ground up to handle complex, structured documents (SGML/XML, metadata, library catalogs) - a real advantage for archives, libraries, scientific databases, and large document repositories. Its document-type model makes it flexible: each document type can be associated with a class of functions to properly parse and index it.</p>
<p>Because it indexes entire documents (not just summaries or keywords), iSearch can locate documents even if the search term appears deep inside the text or metadata - improving recall for research or archival work.</p>

<h2>Target Audience</h2>
<p>iSearch is aimed at institutions and professionals dealing with large document collections - libraries, archives, governmental agencies, research institutions, publishers - as well as developers and researchers who need a custom search solution for specialized corpora (e.g. legal texts, scientific papers, metadata catalogs, etc.).</p>

<h2>Benefits of Using iSearch</h2>
<ul>
  <li>Efficient retrieval from large text collections - indexing and searching is fast even on large data sets.</li>
  <li>Flexible support for many document types and metadata standards - useful for heterogeneous repositories.</li>
  <li>Powerful query capabilities - boolean logic, field queries, full-text search, structured metadata queries.</li>
  <li>Open source - can be adapted, extended or integrated into larger systems, with transparency over code and behavior.</li>
</ul>

<h2>Functional Modules & How iSearch Works</h2>
<ul>
  <li><strong>Indexing Module</strong> - parses documents of various types (SGML/XML, HTML, mail folders, metadata records), extracts tokens (words, metadata fields), builds inverted indexes for fast retrieval.</li>
  <li><strong>Document-Type Abstraction Layer</strong> - for each supported document type, a class of functions handles parsing, metadata extraction and indexing - ensures consistent handling of diverse formats.</li>
  <li><strong>Search Engine & Query Processor</strong> - accepts Boolean expressions, phrase and field queries, processes them against the index, ranks results by relevance.</li>
  <li><strong>Metadata & Field Search Module</strong> - handles metadata-aware searches, for example searching by author, date, document type, or metadata fields defined in SGML/XML.</li>
</ul>

<h2>Supported Platforms & Requirements</h2>
<p>iSearch is platform-independent text-retrieval software originally developed under UNIX/LINUX environments (common for networked information systems in 1990s and 2000s).</p>
<p>Because it's open-source, it can be compiled and run on modern Unix-like systems; for Windows usage, one would need a compatible runtime environment or port (noting that official Windows binaries may not be maintained). The hardware requirements are minimal relative to modern data-scale: like most indexing engines, demand depends on data size, but even large document collections (thousands of documents) can be handled on typical server/desktop hardware.</p>

<h2>Limitations and Considerations</h2>
<p>Originally designed in the mid-1990s, iSearch may not be well-optimized for extremely large modern datasets compared to modern search engines based on more advanced indexing techniques or distributed search frameworks (e.g. Elasticsearch, Solr).</p>
<p>Because support and active development appear limited, modern features like full Unicode support, advanced scoring/tuning, distributed indexing, web-scale performance or integration with contemporary databases might be lacking. Users may need to adapt or extend the system to match modern requirements. </p>

<h2>Typical Use Cases and Applications</h2>
<ul>
  <li>Archival and library catalogs - indexing collections of documents, metadata records (SGML/XML, Dublin Core, FGDC, etc.) for efficient retrieval. </li>
  <li>Research databases - indexing scientific papers, bibliographies, MEDLINE records, legal documents, allowing complex queries over text & metadata. </li>
  <li>Government or institutional document repositories - metadata-aware search over public records, geospatial metadata, standards-compliant datasets (e.g. ISO, FGDC, NASA DIF).</li>
  <li>Custom information retrieval systems - as a backend for websites, internal tools or intranet search, especially where documents vary in format and metadata. </li>
</ul>

<h2>Legacy and Influence</h2>
<p>iSearch was one of the first engines designed from the ground up to support SGML/XML and metadata-rich documents, paving the way for later search systems to handle structured documents beyond simple text.</p>
<p>Its document-type model, flexible parsing and metadata support influenced subsequent search and library catalog software; for many years, it served as a reference implementation for catalog services and metadata harvesting across government agencies and institutions.</p>

<h2>Why iSearch Still Matters</h2>
<p>For organizations dealing with structured documents, metadata standards, and heterogeneous data formats - especially legacy archives, libraries, government or research institutions - iSearch provides a transparent, open-source search engine capable of handling complexity. Its flexibility and minimal dependencies make it a useful tool even today for niche use-cases where modern heavyweight search platforms may be overkill or where customization is required.</p>
