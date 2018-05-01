# fileDB
A database query system using node's fs package. Creates and reads files as a database!

**Create a Database**
`fileDB('myDB').createDB;`

**Create a Collection**
`fileDB('myDB').mkCol('myCol');`

**Veiw a Collection**
`fileDB('myDb').logCol('myCol');`

**Add a document to collection**
`fileDB('myDB').addDoc('myCol', 'MyDocumentName');`

**Find a Document** *Currently no implemented*
`file('myDB').findDoc('myCol', 'SearchTerm');`
