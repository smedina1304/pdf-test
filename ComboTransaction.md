# Documentação 'Transaction MII': ComboTransaction.trx

---


<br>

### Identificação:

|    | Name_ID                                          |   Version_TRX | Version_MII   |
|---:|:-------------------------------------------------|--------------:|:--------------|
|  0 | SaoMartinho/global/Transactions/ComboTransaction |           291 | 15.4.1.14     |
<br><br>

### Roles:

|    | Writer_Roles                 |
|---:|:-----------------------------|
|  0 | SAP_XMII_Administrator       |
|  1 | SAP_XMII_Developer           |
|  2 | SAP_XMII_Super_Administrator |
<br><br>

### Attributos da 'Transaction':
|    | Name_Item                 | Description                                                                                                                          | Type         | Value               |
|---:|:--------------------------|:-------------------------------------------------------------------------------------------------------------------------------------|:-------------|:--------------------|
|  0 | Description               | Transaction Description                                                                                                              | string       |                     |
|  1 | Comments                  | User Comments                                                                                                                        | string       |                     |
|  2 | CreatedBy                 | Created By                                                                                                                           | string       | ubv_henry           |
|  3 | CreationDate              | Creation Date                                                                                                                        | dateTime     | 2008-06-15T18:45:34 |
|  4 | Category                  | Transaction Category                                                                                                                 | string       |                     |
|  5 | Status                    | Deployment Status                                                                                                                    | string       | DEVELOPMENT         |
|  6 | LastEditedBy              | Last Edited By                                                                                                                       | xsd:string   | ubv_alvaro          |
|  7 | LastEditedDate            | Last Edited Date                                                                                                                     | xsd:dateTime | 2022-01-08T12:25:43 |
|  8 | LegacyProcessingMode      | Support the pre MII 12.1 Transaction Engine.                                                                                         | boolean      | 1                   |
|  9 | ThrowOnLinkError          | Throws an exception when a link error occures                                                                                        | boolean      | 1                   |
| 10 | ThrowOnActionError        | Throws an exception when an action error occurs                                                                                      | boolean      | 0                   |
| 11 | AutoAppendBlankNamespaces | Automatically append blank namepsacpes were appropriate in XML appends.                                                              | boolean      | 0                   |
| 12 | FormatXMLOnConversion     | By default XML will be formatted when assigned from XML data type to String data type. This behaviour can be changed with this flag. | boolean      | 1                   |
<br><br>

### Estrutras do Contexto Geral:
|    | Name_Item   | Description   | Type   | Value   |
|---:|:------------|:--------------|:-------|:--------|
|  0 | CD_SAP      |               | string | 0103    |
|  1 | Output      |               | xml    |         |
|  2 | Safra       |               | string | 2021    |
|  3 | Tipo        |               | string | MES     |
<br><br>

### Estrutras do Contexto Local:
|    | Name_Item      | Description   | Type     | Value               |
|---:|:---------------|:--------------|:---------|:--------------------|
|  0 | Dia            |               | dateTime | 2008-06-16T08:46:27 |
|  1 | DiaFim         |               | dateTime | 2008-06-16T23:23:30 |
|  2 | DiaInicio      |               | dateTime | 2008-06-16T23:23:25 |
|  3 | DiaReferencial |               | dateTime | 2008-06-16T23:23:38 |
|  4 | Mes            |               | dateTime | 2008-06-15T19:03:31 |
|  5 | MesFim         |               | dateTime | 2008-06-16T22:57:00 |
|  6 | MesInicio      |               | dateTime | 2008-06-16T22:56:54 |
|  7 | MesReferencial |               | dateTime | 2008-06-16T23:06:07 |
|  8 | SemanaData     |               | dateTime | 2008-06-16T08:27:55 |
<br><br>

### Listas de 'Actions:'
|    | Name_Item            | Description   | Type                      | Value                                           | Properties   |
|---:|:---------------------|:--------------|:--------------------------|:------------------------------------------------|:-------------|
|  0 | SafraListSelectQuery |               | IlluminatorSQLQueryObject | SaoMartinho/global/Queries/SafraListSelectQuery | {}           |
<br><br>

