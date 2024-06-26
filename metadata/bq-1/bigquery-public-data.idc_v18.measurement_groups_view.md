# `idc_v18.measurement_groups_view` [view]
`bq-1` | `bigquery-public-data`
Measurement group sequences extracted from the DICOM SR TID1500 objects; see source code for the underlying query at https://github.com/ImagingDataCommons/etl_flow/blob/master/bq/generate_tables_and_views/derived_tables/BQ_Table_Building/derived_data_views/sql/measurement_groups.sql

## Column details
* [STRING]    `SOPInstanceUID`
* [INTEGER]   `measurementGroup_number`
* [STRING]    `trackingUniqueIdentifier`
* [STRING]    `trackingIdentifier`
* [STRING]    `PatientID`
* [STRING]    `SeriesDescription`
* [RECORD]    `finding`
* [STRING]    `finding.CodeValue`
* [STRING]    `finding.CodingSchemeDesignator`
* [STRING]    `finding.CodingSchemeVersion`
* [STRING]    `finding.CodeMeaning`
* [RECORD]    `findingSite`
* [STRING]    `findingSite.CodeValue`
* [STRING]    `findingSite.CodingSchemeDesignator`
* [STRING]    `findingSite.CodingSchemeVersion`
* [STRING]    `findingSite.CodeMeaning`
* [STRING]    `sourceSegmentedSeriesUID`
* [STRING]    `segmentationInstanceUID`
* [INTEGER]   `segmentationSegmentNumber`
* [RECORD]    `contentSequence`
* [RECORD]    `contentSequence.ReferencedSOPSequence`
* [STRING]    `contentSequence.ReferencedSOPSequence.ReferencedSOPClassUID`
* [STRING]    `contentSequence.ReferencedSOPSequence.ReferencedSOPInstanceUID`
* [STRING]    `contentSequence.ReferencedSOPSequence.ReferencedFrameNumber`
* [STRING]    `contentSequence.RelationshipType`
* [STRING]    `contentSequence.ValueType`
* [RECORD]    `contentSequence.ConceptNameCodeSequence`
* [STRING]    `contentSequence.ConceptNameCodeSequence.CodeValue`
* [STRING]    `contentSequence.ConceptNameCodeSequence.CodingSchemeDesignator`
* [STRING]    `contentSequence.ConceptNameCodeSequence.CodeMeaning`
* [STRING]    `contentSequence.ContinuityOfContent`
* [STRING]    `contentSequence.UID`
* [STRING]    `contentSequence.TextValue`
* [RECORD]    `contentSequence.ConceptCodeSequence`
* [STRING]    `contentSequence.ConceptCodeSequence.CodeValue`
* [STRING]    `contentSequence.ConceptCodeSequence.CodingSchemeDesignator`
* [STRING]    `contentSequence.ConceptCodeSequence.CodeMeaning`
* [RECORD]    `contentSequence.MeasuredValueSequence`
* [RECORD]    `contentSequence.MeasuredValueSequence.MeasurementUnitsCodeSequence`
* [STRING]    `contentSequence.MeasuredValueSequence.MeasurementUnitsCodeSequence.CodeValue`
* [STRING]    `contentSequence.MeasuredValueSequence.MeasurementUnitsCodeSequence.CodingSchemeDesignator`
* [STRING]    `contentSequence.MeasuredValueSequence.MeasurementUnitsCodeSequence.CodingSchemeVersion`
* [STRING]    `contentSequence.MeasuredValueSequence.MeasurementUnitsCodeSequence.CodeMeaning`
* [STRING]    `contentSequence.MeasuredValueSequence.NumericValue`
* [RECORD]    `contentSequence.ContentTemplateSequence`
* [STRING]    `contentSequence.ContentTemplateSequence.MappingResource`
* [STRING]    `contentSequence.ContentTemplateSequence.MappingResourceUID`
* [STRING]    `contentSequence.ContentTemplateSequence.TemplateIdentifier`
* [RECORD]    `contentSequence.ContentSequence`
* [RECORD]    `contentSequence.ContentSequence.ReferencedSOPSequence`
* [STRING]    `contentSequence.ContentSequence.ReferencedSOPSequence.ReferencedSOPClassUID`
* [STRING]    `contentSequence.ContentSequence.ReferencedSOPSequence.ReferencedSOPInstanceUID`
* [INTEGER]   `contentSequence.ContentSequence.ReferencedSOPSequence.ReferencedSegmentNumber`
* [STRING]    `contentSequence.ContentSequence.RelationshipType`
* [STRING]    `contentSequence.ContentSequence.ValueType`
* [RECORD]    `contentSequence.ContentSequence.ConceptNameCodeSequence`
* [STRING]    `contentSequence.ContentSequence.ConceptNameCodeSequence.CodeValue`
* [STRING]    `contentSequence.ContentSequence.ConceptNameCodeSequence.CodingSchemeDesignator`
* [STRING]    `contentSequence.ContentSequence.ConceptNameCodeSequence.CodeMeaning`
* [STRING]    `contentSequence.ContentSequence.ContinuityOfContent`
* [DATE]      `contentSequence.ContentSequence.Date`
* [TIME]      `contentSequence.ContentSequence.Time`
* [STRING]    `contentSequence.ContentSequence.UID`
* [STRING]    `contentSequence.ContentSequence.TextValue`
* [RECORD]    `contentSequence.ContentSequence.ConceptCodeSequence`
* [STRING]    `contentSequence.ContentSequence.ConceptCodeSequence.CodeValue`
* [STRING]    `contentSequence.ContentSequence.ConceptCodeSequence.CodingSchemeDesignator`
* [STRING]    `contentSequence.ContentSequence.ConceptCodeSequence.CodingSchemeVersion`
* [STRING]    `contentSequence.ContentSequence.ConceptCodeSequence.CodeMeaning`
* [RECORD]    `contentSequence.ContentSequence.MeasuredValueSequence`
* [RECORD]    `contentSequence.ContentSequence.MeasuredValueSequence.MeasurementUnitsCodeSequence`
* [STRING]    `contentSequence.ContentSequence.MeasuredValueSequence.MeasurementUnitsCodeSequence.CodeValue`
* [STRING]    `contentSequence.ContentSequence.MeasuredValueSequence.MeasurementUnitsCodeSequence.CodingSchemeDesignator`
* [STRING]    `contentSequence.ContentSequence.MeasuredValueSequence.MeasurementUnitsCodeSequence.CodingSchemeVersion`
* [STRING]    `contentSequence.ContentSequence.MeasuredValueSequence.MeasurementUnitsCodeSequence.CodeMeaning`
* [STRING]    `contentSequence.ContentSequence.MeasuredValueSequence.NumericValue`
* [RECORD]    `contentSequence.ContentSequence.ContentSequence`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.RelationshipType`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ValueType`
* [RECORD]    `contentSequence.ContentSequence.ContentSequence.ConceptNameCodeSequence`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ConceptNameCodeSequence.CodeValue`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ConceptNameCodeSequence.CodingSchemeDesignator`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ConceptNameCodeSequence.CodeMeaning`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContinuityOfContent`
* [TIMESTAMP] `contentSequence.ContentSequence.ContentSequence.DateTime`
* [DATE]      `contentSequence.ContentSequence.ContentSequence.Date`
* [TIME]      `contentSequence.ContentSequence.ContentSequence.Time`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.UID`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.TextValue`
* [RECORD]    `contentSequence.ContentSequence.ContentSequence.ConceptCodeSequence`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ConceptCodeSequence.CodeValue`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ConceptCodeSequence.CodingSchemeDesignator`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ConceptCodeSequence.CodeMeaning`
* [RECORD]    `contentSequence.ContentSequence.ContentSequence.MeasuredValueSequence`
* [RECORD]    `contentSequence.ContentSequence.ContentSequence.MeasuredValueSequence.MeasurementUnitsCodeSequence`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.MeasuredValueSequence.MeasurementUnitsCodeSequence.CodeValue`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.MeasuredValueSequence.MeasurementUnitsCodeSequence.CodingSchemeDesignator`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.MeasuredValueSequence.MeasurementUnitsCodeSequence.CodeMeaning`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.MeasuredValueSequence.NumericValue`
* [RECORD]    `contentSequence.ContentSequence.ContentSequence.ContentSequence`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.RelationshipType`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ValueType`
* [RECORD]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ConceptNameCodeSequence`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ConceptNameCodeSequence.CodeValue`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ConceptNameCodeSequence.CodingSchemeDesignator`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ConceptNameCodeSequence.CodeMeaning`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContinuityOfContent`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.TextValue`
* [RECORD]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ConceptCodeSequence`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ConceptCodeSequence.CodeValue`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ConceptCodeSequence.CodingSchemeDesignator`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ConceptCodeSequence.CodeMeaning`
* [RECORD]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence`
* [RECORD]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ReferencedSOPSequence`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ReferencedSOPSequence.ReferencedSOPClassUID`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ReferencedSOPSequence.ReferencedSOPInstanceUID`
* [RECORD]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ReferencedSOPSequence.ReferencedSOPSequence`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ReferencedSOPSequence.ReferencedSOPSequence.ReferencedSOPClassUID`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ReferencedSOPSequence.ReferencedSOPSequence.ReferencedSOPInstanceUID`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.RelationshipType`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ValueType`
* [RECORD]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ConceptNameCodeSequence`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ConceptNameCodeSequence.CodeValue`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ConceptNameCodeSequence.CodingSchemeDesignator`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ConceptNameCodeSequence.CodeMeaning`
* [RECORD]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ConceptCodeSequence`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ConceptCodeSequence.CodeValue`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ConceptCodeSequence.CodingSchemeDesignator`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ConceptCodeSequence.CodeMeaning`
* [RECORD]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.MeasuredValueSequence`
* [RECORD]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.MeasuredValueSequence.MeasurementUnitsCodeSequence`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.MeasuredValueSequence.MeasurementUnitsCodeSequence.CodeValue`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.MeasuredValueSequence.MeasurementUnitsCodeSequence.CodingSchemeDesignator`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.MeasuredValueSequence.MeasurementUnitsCodeSequence.CodingSchemeVersion`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.MeasuredValueSequence.MeasurementUnitsCodeSequence.CodeMeaning`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.MeasuredValueSequence.NumericValue`
* [RECORD]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.RelationshipType`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ValueType`
* [RECORD]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ConceptNameCodeSequence`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ConceptNameCodeSequence.CodeValue`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ConceptNameCodeSequence.CodingSchemeDesignator`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ConceptNameCodeSequence.CodeMeaning`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.TextValue`
* [RECORD]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ConceptCodeSequence`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ConceptCodeSequence.CodeValue`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ConceptCodeSequence.CodingSchemeDesignator`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ConceptCodeSequence.CodeMeaning`
* [RECORD]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence`
* [RECORD]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ReferencedSOPSequence`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ReferencedSOPSequence.ReferencedSOPClassUID`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ReferencedSOPSequence.ReferencedSOPInstanceUID`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ReferencedSOPSequence.ReferencedFrameNumber`
* [RECORD]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ReferencedSOPSequence.ReferencedSOPSequence`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ReferencedSOPSequence.ReferencedSOPSequence.ReferencedSOPClassUID`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ReferencedSOPSequence.ReferencedSOPSequence.ReferencedSOPInstanceUID`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.RelationshipType`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ValueType`
* [FLOAT]     `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.GraphicData`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.ContentSequence.GraphicType`
* [FLOAT]     `contentSequence.ContentSequence.ContentSequence.ContentSequence.GraphicData`
* [STRING]    `contentSequence.ContentSequence.ContentSequence.ContentSequence.GraphicType`
* [STRING]    `contentSequence.ContentSequence.GraphicType`
* [STRING]    `contentSequence.ContentSequence.ReferencedFrameOfReferenceUID`
* [RECORD]    `contentSequence.ContentSequence.OtherElements`
* [STRING]    `contentSequence.ContentSequence.OtherElements.Tag`
* [STRING]    `contentSequence.ContentSequence.OtherElements.Data`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
