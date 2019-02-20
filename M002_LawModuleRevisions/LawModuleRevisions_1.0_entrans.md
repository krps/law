<pre>
=====================================================
*Translation of: Модуль права №2: "Ревизии Модулей Права"*
*Original Revision: 1.0*
*Original Author: Andrey Galkin*
=====================================================
Law Module 2: "Law Module Revisions"
=====================================================
</pre>

# Translation notice

This is a translation of the original document. Any translation errors
have no legal force.

# Introduction

In the modern technological world, the concepts of revision, backward compatibility and incompatible changes of a certain definition are established. This approach allows individual definitions to be expanded and improved without the need to revise all dependencies.

The norms of law are considered from the point of view of set theory to simplify the interpretation of compatibility and making logical conclusions.

This module separately formalizes the principle already laid down in the Constitution of the Confederation. The coexistence of two or more existing definitions of one document that may not be incompatible is acceptable. The date of the document has no semantic significance.

# 1. The concept of a revision:

## 1.1. A revision is an internal document number made up of one or more numeric components.

## 1.2. The component is a monotonically increasing sequence number, starting from zero.

## 1.3. The main component - the first part, defines a set of document versions that are not compatible with other such sets.

## 1.4. The secondary component — the one following the main component, defines a subset of documents with the same main component and includes a fully compatible subset of documents with a smaller secondary component.

## 1.5. The corrective component - following the minor one, serves only to correct errors without changing the essence of the document.


# 2. Document Identification:

## 2.1. The total set of all revisions of a document is indicated by the name and name of the main author or a number in the registry of the Confederation for short.

## 2.2. The change of the main author means creation of a new incompatible set.


# 3. Compatibility concept:

## 3.1. The difference of the main component means a separate incompatible set.

## 3.2. The difference in the minor component means that all the norms of the previous minor revisions of the main set act invariably. New or changed rules are not valid in previous revisions. Such rules do not apply in other documents that clearly use any previous revisions.

## 3.3. The difference of other components is not taken into account for compatibility rules.

## 3.4. An author may explicitly establish the backward compatibility of a document with respect to a different set.


# 4. Notes and exceptions

## 4.1. The main component with the value "0" - defines a special set of documents without guarantees of compatibility.

## 4.2. In a generally accepted form, the revision is recorded in Arabic numerals with the main component on the left and a dot between the components.

## 4.3. Omitting of the least significant components is allowed, implying a zero value. It is allowed to add additional not generally accepted components, if it does not conflict with these norms.


== END OF DOC ==
