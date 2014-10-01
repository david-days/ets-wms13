WMS 1.3.0 Test Suite Release Notes
==================================

r10 (2014-10-01)
------------------
* [#1](https://github.com/opengeospatial/ets-wms13/issues/1) - update maven structure and clean project for release
* [#7](https://github.com/opengeospatial/ets-wms13/issues/7) - image/png8 and image/png24 are not valid iana media types

r9 (2014-06-20)
---------------
* Fix CITE-950: XPath error in getfeatureinfo:query_layers-not-queryable

r8 (2013-12-10)
----------------
* Fixed 912 Handling of queryable attribute in GFI requests. 
* Fixed 829 Problem with negative coordinates in boundingbox

r7 (2013-09-19)
---------------
* Removed FPS tests to separate test suite (wms-sld).

r6 (2013-05-30)
---------------
* Added FPS profile (WMS-SLD 1.1, Conformance Class C).

r5
---------------
* Fixed functions:layer-info so only one CRS reference is included in result.
* Modified functions:encode to use encode-for-uri XPath function instead of deprecated java.net.URLEncoder.encode method.
* Fixed various XPath errors in getmap.xml: A sequence of more than one item is not allowed as the first argument of string()
* Added assertion error messages to basic_elements.xml.
* Fixed various typos.

r4
---------------
* https://portal.opengeospatial.org/?m=projects&amp;a=view&amp;project_id=85&amp;tab=5&amp;act=details&amp;issue_id=665[Issue #665]:
  Added test (layer-extents) to check that layer extent is consistent with 
  CRS reference.

r3 (2012-04-05)
---------------
* 4549 - properly encode bboxes
* 4548 - updated coordinate system as suggested in ticket #644

