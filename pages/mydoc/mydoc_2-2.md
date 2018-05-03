---
summary: General explanation of how to use flow charts
keywords: 'visualization, flow-chart, data'
permalink: mydoc_2-2.html
folder: mydoc
last_updated: 'August 24, 2017'
title: Flow Charts
tags:
  - technical_writing
sidebar: mydoc_sidebar
---

# mydoc\_2-2

A flowchart is a type of diagram that represents an algorithm, workflow or process, showing the steps as boxes of various kinds, and their order by connecting them with arrows. This diagrammatic representation illustrates a solution model to a given problem. Flowcharts are used in analyzing, designing, documenting or managing a process or program in various fields.

Generally, there are four types of flowcharts:

* Document flowcharts, showing controls over a document-flow through a system
* Data flowcharts, showing controls over a data-flow in a system
* System flowcharts, showing controls at a physical or resource level
* Program flowchart, showing the controls in a program within a system

Thus, if you are using a flow-chart to represent the writing process, the "document" flowchart makes sense. In this case, you are the system.

Flowcharts typically use common symbols to represent different aspects of a process. Some of the standard symbols include:

| ANSI/ISO Shape | Name | Description |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ![Flowchart Line.svg](https://github.com/writ300/writ300.github.io/tree/da1da9210b9a78098b041b6d124db2a4ebc5af76/upload.wikimedia.org/wikipedia/commons/thumb/6/6c/Flowchart_Line.svg/100px-Flowchart_Line.svg.png) | Flowline \(Arrowhead\)[\[15\]](mydoc_2-2.md#cite_note-Myler1998-15) | Shows the program's order of operation. A line coming from one symbol and ending at another.[\[14\]](mydoc_2-2.md#cite_note-ShellyVermaat2011-14) Arrowheads are added if the flow is not the standard top-to-bottom, left-to right.[\[15\]](mydoc_2-2.md#cite_note-Myler1998-15) |
| ![Flowchart Terminal.svg](https://github.com/writ300/writ300.github.io/tree/da1da9210b9a78098b041b6d124db2a4ebc5af76/upload.wikimedia.org/wikipedia/commons/thumb/a/ad/Flowchart_Terminal.svg/100px-Flowchart_Terminal.svg.png) | Terminal[\[14\]](mydoc_2-2.md#cite_note-ShellyVermaat2011-14) | Beginning or ending of a program or sub-process. Represented as a [stadium](https://github.com/writ300/writ300.github.io/tree/da1da9210b9a78098b041b6d124db2a4ebc5af76/wiki/Stadium_%28geometry%29/README.md),[\[14\]](mydoc_2-2.md#cite_note-ShellyVermaat2011-14) oval or rounded \(fillet\) rectangle. They usually contain the word "Start" or "End", or another phrase signaling the start or end of a process, such as "submit inquiry" or "receive product". |
| ![Flowchart Process.svg](https://github.com/writ300/writ300.github.io/tree/da1da9210b9a78098b041b6d124db2a4ebc5af76/upload.wikimedia.org/wikipedia/commons/thumb/7/7e/Flowchart_Process.svg/100px-Flowchart_Process.svg.png) | Process[\[15\]](mydoc_2-2.md#cite_note-Myler1998-15) | Set of operations that change value, form, or location of data. Represented as a [rectangle](https://github.com/writ300/writ300.github.io/tree/da1da9210b9a78098b041b6d124db2a4ebc5af76/wiki/Rectangle/README.md).[\[15\]](mydoc_2-2.md#cite_note-Myler1998-15) |
| ![Flowchart Decision.svg](https://github.com/writ300/writ300.github.io/tree/da1da9210b9a78098b041b6d124db2a4ebc5af76/upload.wikimedia.org/wikipedia/commons/thumb/0/0e/Flowchart_Decision.svg/100px-Flowchart_Decision.svg.png) | Decision[\[15\]](mydoc_2-2.md#cite_note-Myler1998-15) | Conditional operation determining which of two paths the program will take.[\[14\]](mydoc_2-2.md#cite_note-ShellyVermaat2011-14) The operation is commonly a yes/no question or true/false test. Represented as a diamond \([rhombus](https://github.com/writ300/writ300.github.io/tree/da1da9210b9a78098b041b6d124db2a4ebc5af76/wiki/Rhombus/README.md)\).[\[15\]](mydoc_2-2.md#cite_note-Myler1998-15) |
| ![Flowchart IO.svg](https://github.com/writ300/writ300.github.io/tree/da1da9210b9a78098b041b6d124db2a4ebc5af76/upload.wikimedia.org/wikipedia/commons/thumb/f/f4/Flowchart_IO.svg/100px-Flowchart_IO.svg.png) | Input/Output[\[15\]](mydoc_2-2.md#cite_note-Myler1998-15) | Input and output of data,[\[15\]](mydoc_2-2.md#cite_note-Myler1998-15) as in entering data or displaying results. Represented as a [parallelogram](https://github.com/writ300/writ300.github.io/tree/da1da9210b9a78098b041b6d124db2a4ebc5af76/wiki/Parallelogram/README.md).[\[14\]](mydoc_2-2.md#cite_note-ShellyVermaat2011-14) |
| ![Flowchart Annotation.svg](https://github.com/writ300/writ300.github.io/tree/da1da9210b9a78098b041b6d124db2a4ebc5af76/upload.wikimedia.org/wikipedia/commons/thumb/e/e3/Flowchart_Annotation.svg/100px-Flowchart_Annotation.svg.png) | Annotation[\[14\]](mydoc_2-2.md#cite_note-ShellyVermaat2011-14) \(Comment\)[\[15\]](mydoc_2-2.md#cite_note-Myler1998-15) | Additional information about a step the program. Represented as an open rectangle with a dashed or solid line connecting it to the corresponding symbol in the flowchart.[\[15\]](mydoc_2-2.md#cite_note-Myler1998-15) |
| ![Flowchart Predefined Process.svg](https://github.com/writ300/writ300.github.io/tree/da1da9210b9a78098b041b6d124db2a4ebc5af76/upload.wikimedia.org/wikipedia/commons/thumb/7/74/Flowchart_Predefined_Process.svg/100px-Flowchart_Predefined_Process.svg.png) | Predefined Process[\[14\]](mydoc_2-2.md#cite_note-ShellyVermaat2011-14) | Named process which is defined elsewhere. Represented as a rectangle with double-struck vertical edges.[\[14\]](mydoc_2-2.md#cite_note-ShellyVermaat2011-14) |
| ![Flowchart Connector.svg](https://github.com/writ300/writ300.github.io/tree/da1da9210b9a78098b041b6d124db2a4ebc5af76/upload.wikimedia.org/wikipedia/commons/thumb/8/8e/Flowchart_Connector.svg/50px-Flowchart_Connector.svg.png) | On-page Connector[\[14\]](mydoc_2-2.md#cite_note-ShellyVermaat2011-14) | Pairs of labeled connectors replace long or confusing lines on a flowchart page. Represented by a small circle with a letter inside.[\[14\]](mydoc_2-2.md#cite_note-ShellyVermaat2011-14)[\[18\]](mydoc_2-2.md#cite_note-RFF-18) |
| ![Off page connector.png](https://github.com/writ300/writ300.github.io/tree/da1da9210b9a78098b041b6d124db2a4ebc5af76/upload.wikimedia.org/wikipedia/commons/thumb/4/44/Off_page_connector.png/50px-Off_page_connector.png) | Off-page Connector[\[14\]](mydoc_2-2.md#cite_note-ShellyVermaat2011-14) | A labeled connector for use when the target is on another page. Represented as a [home plate](https://github.com/writ300/writ300.github.io/tree/da1da9210b9a78098b041b6d124db2a4ebc5af76/wiki/Baseball_field/README.md#Home_plate)-shaped [pentagon](https://github.com/writ300/writ300.github.io/tree/da1da9210b9a78098b041b6d124db2a4ebc5af76/wiki/Pentagon/README.md).[\[14\]](mydoc_2-2.md#cite_note-ShellyVermaat2011-14)[\[18\]](mydoc_2-2.md#cite_note-RFF-18) |

## Other Process Visualizations

Flowcharts are not the only tool for visualizing process. In fact, most graphs can be purposed to illustrate process. For example, a pie graph can illustrate time devoted to different aspects of a process, while a line graph can illustrate changes over time.

The important thing to consider when creating visualizations is that they should either help in your own understanding of the data or clarify the data for an external audience.

[Next Page](https://github.com/writ300/writ300.github.io/tree/da1da9210b9a78098b041b6d124db2a4ebc5af76/mydoc_2-3.html)

## Attribution

1. "Flowchart" Provided by Wikipedia. Located at: [https://en.wikipedia.org/wiki/Flowchart](https://en.wikipedia.org/wiki/Flowchart). License: CC BY-SA 

