# EDI2XML
This is EDI to XML conversion using edi_xml_medi file using Smooks.
Just pass your EDI file and edi_xml_mapping file and get XML as Output in Result.
  smooks.filterSource(executionContext,Source inputEdi ,InputStream inputXml, result);
  String outputXML = result.getResult()
