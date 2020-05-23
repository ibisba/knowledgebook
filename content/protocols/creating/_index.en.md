---
title: "4.3 Creating protocols"
date: 2020-02-14T10:00:00+06:00
lastmod: 2020-03-27T10:00:00+06:00
weight: 403
---

### Minimal requirements and recommendations for IBISBA protocols

#### General guidelines

**Scope of IBISBA protocols**

Each IBISBA protocol should cover a single Task. Before starting to write an IBISBA protocol, you should first identify which Task in the IBISBA Task Curation system would be covered by the protocol. If no such Task can be identified, a new Task must be added to the Task Curation system. Protocols covering multiple Tasks should be divided into several smaller protocols to make them IBISBA-compatible. For example, if a protocol covers both: 1) preparation of electrocompetent cells and 2) transformation of electrocompetent cells, it should be divided into two protocols (i.e. “Preparation of electrocompetent cells” and “Transformation of electrocompetent cells”). If a protocol that covers multiple Tasks or a single Task only partially has been uploaded, the Main Protocol Curator will contact the Protocol Curator of the responsible organization. If two protocols for the same Task have been uploaded to the IBISBA Hub, the Main Curator will make the decision which protocol will be left in the IBISBA Hub and which protocol will be removed.

**Input, output and critical points**

Each IBISBA protocol must have defined inputs and outputs. Inputs include any material or information produced in other Tasks that are needed to execute the protocol. All commonly used materials that can be purchased (e.g. D-glucose, electroporation cuvettes, thermocycler) shall not be included as input. However, all materials that are custom-made for the project or have been designed in the project (e.g. synthetic DNAs) shall be included as inputs.

Output values constitute every material and information produced by executing this protocol regardless if it may or may not be needed in subsequent protocols. If the protocol has a material output which can have varying quality, information about the quality is also required. For example, the protocol “Extraction of plasmid DNA from bacterial cells” has a material output ‘Plasmid DNA’ and thus it should also contain information such as ‘Concentration of the plasmid DNA’ and ‘Purity of the plasmid DNA’.

Each protocol contains important steps that need to be carried out in a specific way to ensure the quality of the output. Such steps are termed critical points and form the core of IBISBA protocols. Everything that is not considered a critical point in the protocol should be made as general as possible to ensure wide applicability of the protocol. Critical points should be made specific enough to ensure high quality of the output. For example, if a protocol for long term storage of bacterial cells at -80 °C is written, it should not be made species-specific. If this protocol cannot be used for a certain bacterial species, a new species-specific protocol must be written. In this particular case, the steps which prevented using the more general protocol constituted the critical points.

**When to write a new IBISBA protocol or update an old one**

Before starting to write a new IBISBA protocol you should check from the IBISBA Hub whether it already contains a protocol for the Task in question. If the IBISBA Hub contains such a protocol, you should review it for critical points and consider whether it can be used in your project. If the existing protocol differs too much with respect to its critical points, i.e. the output cannot be obtained or the quality of the output is compromised, a new protocol shall be written. If changes are made to an existing protocol without affecting the critical points, then a new version of the protocol has to be generated.


### Structure of IBISBA protocols

An IBISBA protocol consists of a header section and a body section. A part of the header section is repeated on every page. The body section consists of titled subsections.

**1.	Page header**

The title, version number, contact person name and affiliation, and date shall be placed in the page header and thus repeat on every page of the protocol.

**1.1.	Descriptive title**

A descriptive title without ambiguous or rare abbreviations shall distinguish this protocol from all other potential protocols in a protocol database. If the protocol is closely related to another protocol already uploaded to the IBISBA Hub, it should be obvious from the title how they differ.

Tip: Bad example: ‘Maxwell 16LEV simply RNA kit’. Good example: ‘RNA isolation from tissue samples using the Maxwell instrument’).

**1.2.	Editor for most recent version**

This field shall contain the name of the contact person, i.e. lead editor, in the organization (= institution) responsible for this version of the protocol. Initials must not be used. Public identifiers such as ORCID may be added.

**1.3.	Institution**

The institution is the organization of the lead editor responsible for this version of the protocol.

**1.4.	Version**

In the case of new (second, third,....) version of existing protocol, increment the version number. Version numbers with decimals means that the same authors are making a minor correction to the protocol. Drafts are to be marked with a ‘DRAFT’ label.

**1.5.	Date**

The date when this version of the protocol was published/drafted for comments.

**2.	Document header**

The document header (not in the page header) shall additionally explain why changes were made to the title (if any), what the terms in the title mean (unless obvious), which version this protocol version replaces or extends, and the names and affiliations of all authors that contributed to this version of the protocol.

**3.	Keywords and key phrases**

Add as many keywords as possible. Use keywords that already exist in the Keyword list file. If none of the existing keywords are useful, add your new keyword to the Keyword list file.

**4.	Description**

A few sentences that explain the aim, content, and context of the protocol. This should introduce the reader to the topic and allow the reader to judge the usefulness of this protocol for their particular application. 

**5.	Prerequisites**

The prerequisites include the inputs from other IBISBA protocols or IBISBA project plan, the consumables, and the equipment necessary to execute this protocol.

**5.1	Inputs from other IBISBA protocols or IBISBA project plan**

A protocol input is a piece of information or physical object I) produced by another TasCu step or IBISBA protocol, II) required to execute the protocol, and III) cannot be purchased as a consumable.

If the quality of e.g. a buffer or cultivation media may critically affect the outcome of this protocol, the necessary requirements must be stated in the input section. This includes freshness.

**5.2	Chemicals**

List chemicals and reagent kits as one would when writing a scientific paper. Additionally, include ordering details such as supplier (not necessarily the same as manufacturer) and catalogue identifier.

Tip: Include details, (e.g. don’t type ‘Tris buffered saline’ when you mean ‘Tris buffered saline pH 8 powder’; otherwise people will use the ‘Tris buffered saline pH 7.6 tablet’ that they have in their lab).

Manufacturer-made media and buffers bought as consumables shall be specified in the chemicals section.

Note: Recipes for media and buffers shall be isolated into their own protocols.

**5.3	Special consumables**

Common things like pipette tips and bottles are not necessary in this list, but more uncommon things like needles of a certain gauge or specific types of 96-wells plates must be mentioned.

**5.4	Other materials**

For example plasmids, proteins and PCR fragments. For plasmids, proteins, PCR fragments, etc. links to the sequences should be specified: e.g. the supplier name/webpage/product number. For short sequences the entire sequence should be given, for longer sequences a link to the appropriate source should be provided. This section should not however contain any materials generated or designed in other Tasks. Any material, including nucleic acids, generated in other IBISBA protocols must be included in the Inputs section.

**5.5	Equipment**

Type of equipment needed to execute this protocol. Specifics like brand name are not necessary (also see Protocol steps section).

**6.	Protocol steps**

This section shall contain all steps in chronological order needed to produce the output in the specified format from the inputs and consumables in their specified formats using the specified equipment.

-	The steps need to be written at least as specifically as in peer-reviewed research articles. 
-	Write down generic instructions regarding use of equipment: the settings on the machine only, don’t specify which button to push since we all use different equipment. For example, temperature and centrifugal force in the case of a centrifuge. For complex equipment like fermentors write down as much settings as you can think of.
-	Describe data management (explain what to do with the data of a microarray experiment for example, even if it only is: ‘store at such-and-such drive and hand over to your statistician’).
-	Include all seemingly unimportant things that you do to make the protocol a success (for example flicking a tube 5 times instead of 8 times to mix its contents).
-	Include controls and instructions how to proceed if controls indicate a problem in the execution of the protocol.

Note: This section must contain all steps necessary to convert the primary measurements into the output in the specified data format. 

Tip: For example in a protocol that describes how to make a growth curve, not only explain how to measure optical density, but the method of making the actual curve should be described as well (what goes onto which axis in the graph, how to do the statistics, etc.).

Note: The protocol steps must include all information needed to produce output of high quality.

Note: The steps must also include anything critical to the successful execution of the protocol. 

**7.	Output**

The Output section shall contain all materials and information resulting from executing this protocol. This section should also contain information about the format in which the output data is to be stored. The quality metric, minimal expected/acceptable score, and any information needed to interpret the quality of the output shall also be specified.

Tip: You may explain potential objectives/uses of the information, data and/or materials resulted from this protocol.

**8.	Safety guidelines**

Any dangerous procedures or chemicals shall be mentioned, accompanied by instructions about how to use them safely. Do not forget to mention biosafety risks.

The user must read and understand all material data safety sheets, documents detailing safe operation of equipment, and any regulatory documents.

The user must understand and follow all guidelines for laboratory safety including good laboratory practice.

The user must follow all guidelines, recommendations, and procedures set forth by their institution and adhere to all safety rules at the place of execution.

The user must not under any circumstance execute or attempt the execution of this protocol with weak or insufficient understanding of safety procedures.

**9.	Liability statement**

The protocol is provided as is, without guaranties of correctness, safety, or fitness for purpose, to be used at own risk. IBISBA, IBISBA 1.0, the authors, and the authors’ institutions are under no circumstances liable for any damages resulting from the use of this protocol or any part of it.

**10.	References**

The original publications where the protocol has been described or on which the protocol is based on shall be listed here. If the protocol is not based on any published work, this section can be empty.
