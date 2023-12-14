# System of entities

System of entities is based on the system of classes in ontology of Computational Linguistics (ontology we currently working on).

List of classes (the subclasses of the classes are indicated in brackets):
* Task,
* Object,
* Metric,
* Model,
* Dataset,
* Organization,
* Science,
* Person,
* Publication,
* Method (Method_ML),
* Application (Library, App_system, Technology),
* Environment,
* InfoResource (Corpus),
* Activity. 

List of attributes:
* Date, 
* Value, 
* Lang.

We used the following template to indicate relations with ***data properties***: `Name_(Name-of-relation)_Name`. In places where *Name* is specified, the class and attribute names are inputted. For example, `Metric_hasValue_Value`.

List of data properties: 
* Date_isDateOf_Application,
* Date_isDateOf_Method,
* Date_isDateOf_Model,
* Metric_IsAlternativeNameFor_Metric, 
* Metric_hasValue_Value, 
* Method_IsAlternativeNameFor_Method, 
* Science_IsAlternativeNameFor_Science,
* Task_IsAlternativeNameFor_Task, 
* Organization_IsAlternativeNameFor_Organization, 
* Application_IsAlternativeNameFor_Application, 
* Model_IsShortNameFor_Model, 
* InfoResource_IsAlternativeNameFor_InfoResource, 
* Model_Language_Lang,
* InfoResource_Language_Lang.

We used the following template to indicate relations with ***object properties***: `Name_(Name-of-relation)_Name`. In places where *Name* is specified, names of the classes are inputted. For example, `Model_hasAuthor_Person`.

List of object properties:
* Object_includes_Object,
* Method_includes_Method, 
* Object_isUsedInSolving_Task, 
* Method_hasAuthor_Person, 
* Method_hasAuthor_Organization,
* Application_hasAuthor_Person, 
* Application_hasAuthor_Organization, 
* Model_hasAuthor_Person, 
* Model_hasAuthor_Organization, 
* Activity_hasAuthor_Organization,
* Method_solves_Task, 
* Method_is_applied_to_Object, 
* Method_isUsedIn_Science, 
* Method_isUsedIn_Application,
* Model_includes_Model, 
* Model_isTrainedOn_Dataset, 
* Model_isUsedIn_Application, 
* Model_isUsedForSolving_Task,
* Metric_isUsedFor_Model, 
* Metric_isAppliedTo_Method,
* Metric_isUsedIn_Task, 
* Environment_isUsedIn_Application, 
* Application_isUsedIn_Science, 
* Application_isUsedForSolving_Task, 
* Application_is_applied_to_Object, 
* Dataset_isTrainedForSolving_Task, 
* Task_isSolvedIn_Science.
