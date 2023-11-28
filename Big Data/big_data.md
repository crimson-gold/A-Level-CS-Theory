# Big Data

big data is a term used to describe data sets that are too large and complex to
deal with through traditional data-processing

## Volume, Velocity & Variety

big data can be described in terms of

- volume - the amount of data is too big to fit onto a single server / storage device
- velocity - the speed at which the data is created and how fast it moves
- variety - the diversity of data in its format and structure

these factors impact the ease of handling and manipulating the data; larger
volumes with more variety and a greater velocity are harder to analyse

## Issues with big data

- relational databases can't be used for big data as they don’t scale well
  across multiple servers as they require data to fit into neat rows and columns
- variety makes analysing the data more difficult

to combat these issues techniques like machine learning and functional
programming can be used to more efficiently manage big data

## Specification

| Content | Additional information |
| --- | --- |
| Know that 'Big Data' is a catch-all term for data<br>that won't fit the usual containers. Big Data can<br>be described in terms of:<br><ul><li> volume - too big to fit into a single server<br></li><li> velocity - streaming data, milliseconds to<br>seconds to respond<br></li><li> variety - data in many forms such as<br>structured, unstructured, text, multimedia.</li></ul> | Whilst its size receives all the attention, the<br>most difficult aspect of Big Data really involves<br>its lack of structure. This lack of structure poses<br>challenges because:<br><ul><li> analysing the data is made significantly<br>more difficult<br></li><li> relational databases are not appropriate<br>because they require the data to fit into a<br>row-and-column format.</li></ul>Machine learning techniques are needed to<br>discern patterns in the data and to extract<br>useful information.<br>'Big' is a relative term, but size impacts when<br>the data doesn’t fit onto a single server because<br>relational databases don’t scale well across<br>multiple machines.<br>Data from networked sensors, smartphones,<br>video surveillance, mouse clicks etc are<br>continuously streamed. |
| Know that when data sizes are so big as not to<br>fit on to a single server:<br><ul><li> the processing
must be distributed across<br>more than one machine<br></li><li> functional programming is a solution,<br>because it makes it easier to write correct<br>and efficient distributed code.<br>Know what features of functional programming<br>make it easier to write:<br></li><li> correct code<br></li><li> code that can be distributed to run across<br>more than one server.</li></ul> | Functional programming languages support:<br><ul><li> immutable data structures<br></li><li> statelessness<br></li><li> higher-order functions.</li></ul> |
| Be familiar with the:<br><ul><li> fact-based model for representing data<br></li><li> graph schema for capturing the structure<br>of the dataset<br></li><li> nodes, edges and properties in graph<br>schema.</li></ul> | Each fact within a fact-based model captures a<br>single piece of information. |
