---
content_type: page
description: This section provides the lab assignments for the course, solutions,
  and supporting files.
learning_resource_types:
- Assignments
ocw_type: CourseSection
title: Assignments
uid: 647ec78d-ce25-991a-1d58-c5306ef23f53
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

This section contains the labs that were done during class, along with example solutions, and a small section of [miscellaneous](#Miscellaneous) items.

Labs and Solutions
------------------

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
DESCRIPTION
{{< thclose >}}
{{< thopen >}}
FILES
{{< thclose >}}
{{< thopen >}}
SOLUTIONS
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
Lab 3 covered control flow with if-elif-else statements.
{{< tdclose >}}
{{< tdopen >}}
({{% resource_link f2930339-101f-9dce-da43-7c08189b8559 "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Lab 4 covered control flow with while statements.
{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 6faeb3af-6a54-f766-8cd2-69a3ab66f49f "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}


login.py ({{% resource_link 0308ce98-8bb2-fc2f-a3ec-af2a49b6aa69 "PY" %}})

nims1.py ({{% resource_link aa10d0e2-36b6-e2c9-ea37-5cd82e59cadf "PY" %}})

nims2.py ({{% resource_link 7d8356ce-b1c4-3021-1771-83186cde0ffc "PY" %}})


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Lab 5 covered the use of lists in storing a dynamic number of values.
{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 54293c9e-0f4f-bf51-5f59-981e7196fa13 "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}


sorting.py ({{% resource_link a86a0ff0-9e86-fdc3-a0e7-dd64a7c3e6bb "PY" %}})

reportcard.py ({{% resource_link 9dfe3354-3db0-11b5-3986-dc2a27e9202a "PY" %}})


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Lab 6 covered the use of tuples instead of lists and their similarity with strings.
{{< tdclose >}}
{{< tdopen >}}
({{% resource_link caf21161-eee5-53ab-c08e-e9618bee7821 "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}


collision.py ({{% resource_link 1780c031-9d1c-efe0-339a-511f77bec244 "PY" %}})

piglatin.py ({{% resource_link e9e28522-4c2e-7cb5-ed4b-bea90725099f "PY" %}})


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


Lab 7 was a walkthrough tutorial that introduced the idea of objects as opposed to primitive types like ints and floats. By exploring concepts like primitives (e.g. numbers) versus references to objects (e.g. lists), mutability versus immutability, and the effects of scope on objects, we now better understand how to use objects correctly.

### Notes

  

1\. Some commands will not produce the expected results when performed on the shell. Instead, run the commands from a file. I'm not sure why this is.

2\. I was under the impression that Python aliases tuples automatically. It turns out this is **not** the case. In other words:

> a = (1, 2, 3)  
> b = (1, 2, 3)  
> print a is b

However, you can still alias by saying b = a. Strings are still automatically aliased.


{{< tdclose >}}
{{< tdopen >}}
({{% resource_link d2c23ab0-3e28-f535-cd3f-8a28d717f4e3 "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Lab 8 covered the use of member functions in various objects.
{{< tdclose >}}
{{< tdopen >}}
({{% resource_link 42fc2a54-dbb8-983e-0be8-cadfbd26a3ff "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}
genetic.py ({{% resource_link bfea0c8b-6483-d4fc-187e-dd3b4c93556e "PY" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Lab 9 covered the use and syntax of dictionaries. The bulk of the lab was to explore one common use of dictionaries as indexes, in this case, for searching the Web.
{{< tdclose >}}
{{< tdopen >}}


({{% resource_link 8ba24c16-0461-566a-2c14-f8c6c21eff03 "PDF" %}})

namesages.py ({{% resource_link 78d40094-f200-7c2c-2618-93871dceed51 "PY" %}})

websearch1.py ({{% resource_link 1ef2381c-c3d9-a868-786c-873ad7c6e5ed "PY" %}})

webindexer1.py ({{% resource_link b739d7db-6df6-27f0-fbfc-298b89dbbf16 "PY" %}})

htmltext.py ({{% resource_link dbe6614a-f641-9849-c578-107771134d09 "PY" %}})

smallsites.txt ({{% resource_link 224abc3a-7686-524f-3f57-1a13f55884e9 "TXT" %}})

mitsites20.txt ({{% resource_link 39a3102f-e3af-cd9d-6a5a-e6079b039f00 "TXT" %}})

mitsites50.txt ({{% resource_link 5bb15eca-cf39-1521-fd62-5793ef1a227c "TXT" %}})

localsites.zip ({{% resource_link b6644342-9ea6-028e-ed90-641b5e40b9f7 "ZIP" %}})


{{< tdclose >}}
{{< tdopen >}}


namesages\_soln.py ({{% resource_link 2a5cd162-4ce6-4153-031b-6ca7cc4b87a3 "PY" %}})

webindexer1\_soln.py ({{% resource_link 4ffd00ef-fbae-e4bc-03d6-bcae2d38f9cb "PY" %}})


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Lab 10 covered a more advanced use of dictionaries. The bulk of the lab was to improve the web indexer we built in the previous lab.
{{< tdclose >}}
{{< tdopen >}}


({{% resource_link 0e7532cd-e788-d3ad-983c-d77eafe1a1de "PDF" %}})

inventory.py ({{% resource_link 4e37c0f7-b3fb-58af-3fd8-96e37d088b1a "PY" %}})

websearch2.py ({{% resource_link cad99704-bc00-3155-2f44-e92b75640d8d "PY" %}})

webindexer2.py ({{% resource_link 2c10d255-3f0e-16aa-3262-ac1a69a6780b "PY" %}})


{{< tdclose >}}
{{< tdopen >}}


inventory\_soln.py ({{% resource_link 8838b497-f701-e8eb-6381-e5580eeb0c73 "PY" %}})

webindexer2\_soln.py ({{% resource_link cdd02bd5-36a8-e0b4-48d1-9c3526e1db52 "PY" %}})


{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

{{< anchor "Miscellaneous" >}}{{< /anchor >}}Miscellaneous
----------------------------------------------------------

Optional Assignment ({{% resource_link 022163a7-b3dc-fc52-d57b-cc71802afceb "PDF" %}}): This walks you through the building of a computer from scratch. Starting at the gate level, you'll understand how a computer works.

Operator Cheat Sheet ({{% resource_link 6a1d2475-4b9b-468c-5dd9-fdb42b56a16e "PDF" %}}): This lists some of the various arithmetic and boolean (comparison, equality, and logic) operators we've learned.