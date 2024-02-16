# Exercise 2 - Immunisation

**[E2P2Q1] Complete the `Immunisation` resource in FHIR JSON file ([IMMU_Excercise.json](IMMU_Excercise.json)) by adding the following values.**

_Element ID: vaccineCode_

|Field Name|FHIR Structure|Value|
|:--|:--|:--|
|Vaccine - recognised terminology name|coding.system|http://ehealth.org.hk/RPP|
|Vaccine identifier - recognised terminology|coding.code|48297|
|Vaccine description - recognised terminology|coding.display|BOOSTRIX VACCINE|
|Vaccine local indicator|coding.system|http://ehealth.gov.hk/HCP/vaccinelocal|
|Vaccine local description|coding.display|BOOSTRIX VACCINE|

_Element ID : extension_

|Field Name|FHIR Structure|Value|
|:--|:--|:--|
|Historical Immunisation|url|http://ehealth.gov.hk/FHIR/1004028-Historicalimmunisation|
| |valueString|N|
|Vaccine administration remark|url|http://ehealth.gov.hk/FHIR/1003428-vaccineAdminRemark|
| |valueString|[Put anything here]|
