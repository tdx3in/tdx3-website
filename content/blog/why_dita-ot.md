+++
title = "Why have DITA Customizations"
date = "2024-01-22"
tags = ["DITA", "DITA-OT", "hugo"]
categories = []
banner = "img/banners/banner-2.jpg"
<!-- authors = ["Chugh"]-->
+++

# DITA XML and DITA Open Toolkit 

DITA is an XML standard with a defined syntax or element structure that is supported by many XML authoring tools, such as Oxygen XML Author/Editor. Many organizations use XML authoring tools to write, edit, and review technical documentation. Although you can write DITA XML without such a tool, an XML authoring tool provides so many useful features, such as authoring support and automatic validation, that it is not worth it.

However, the DITA XML standard does not define how to convert the created content into a format that customers expect, that web applications can render, or that is easy to read. This is where the DITA OT comes in.
## What is the DITA Open Toolkit?

DITA OT is a toolkit that allows you to transform DITA content into various output formats. DITA OT also provides a technical  implementation of the DITA architecture in the form of Document Type Definitions (DTDs), XML Schemas (XSD) or Relax NG (RNG). These schemas guide the authors and ensure that their content is valid DITA.

Many authoring tools and content delivery portals support the DITA OT out-of-the-box. That means you can use the DITA OT to customize your output formats and schemas and then integrate the DITA OT with your customizations in the authoring tool or content delivery portal. Here are the key features of the DITA OT:

   - Free and vendor-independent. The DITA OT can be used anywhere and by anyone.
   - Open source. The DITA OT is maintained and developed by a small, independent group and a larger community on GitHub.
   - Supports multiple output formats including HTML, PDF, Markdown, and WebHelp.
   - Includes the core technologies Java, ANT and XSLT. PDF can be generated out-of-the-box using the free XSL-FO processor Apache FOP.
   - Scalable. New or customized output formats and schemas can be integrated via the plug-in mechanism.


FOr more information, see {{< youtube Ao_Jvk1J5i0>}}
