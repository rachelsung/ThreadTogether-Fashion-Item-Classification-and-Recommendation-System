## ThreadTogether Fashion Item Classification and Recommendation System

### I.     Project Proposal

There are 2 main sources of input data that Thread Together(TT)leverages –Image and web data. Our present proposal pertains tomining the web data via text analytics.

There are **4 primary objectives**:

- **Attribution of web data**–TT will provide a dataset previously extracted from various retail websites, we would like to organize and extract meaningful product informationfrom the web data. <br>

- **Attribution tool/app**–As a supplement to extracting features from current datasets, wepropose the development of a text parsing app that would provide a repeatable solution and will require minimal human interventionfor future datasets from retailers. The input to this app would be product descriptions, tags, and other metadata.

- **Business application**–It is our hope that by immersing the students in solving a real world business problem with active business/technical support, that the students will gain immediate and valuable experience as theircompetitive edge in the evolving data science market.

- **Outfitting recommendation**–Given tagged data about different women’s fashion items, produce a customer recommendation system.

### II.       Data

This section describes the available data and the supporting library of attributes. <br>
A.  Leveraging previously scraped web data, TT product data consist of mainly 2 forms of text(verbatim to reflect actual nature of data):

1. Product descriptions –<em>"People often think of sundresses when temperatures rise, but Zimmermann's floral-print 'Amari'jumpsuit is an equally good alternative. Its ruched sleeveless bodice is designed with tie shoulder straps and a square neckline with shirred trim. Wear the wide-leg cotton style with flat sandals and oversized gold jewelry. "
2. Product details –<em>Zip fastening along backComposition: 100% cotton Dry clean Imported This style fits true to size We suggest taking your normal size<em>
<br>

B. The objective of our initiative is **focused on women’s fashion**.However, the data sources may also contain non-relevant products depending on the brand and retail sites. <br> - Examples of non-relevant products: Home goods, holiday decorations, etc.

C. There are 2 main types of attributesto identify:

1. **Explicit product attributes**–Color, material, care, sleeve length, etc.
2. **Implicit product attributes**–Business casual, season, etc.

D. ThreadTogether has created a library of pre-determined fashion attribute names anda list of possible values;the students mayleverage this information to shave off time required. 

E. For any additional attribute names/values developed through this project, we also ask that the new attribute names/values be included in the library. The categorization of the terms in the library will be optional and can be supported internally by the TT Data Science teamif need be.

### III. Methods

A. Identifying relevant fashion products from non-relevant products. <br>
B. Of the relevant fashion products, using the product description & product detail with the TT library of terms to identify.<br>
C. Identifying any gaps in attributes and documentin the attribution library.<br>
D. Packaging code into a repeatable solutionsuch as an app that would identify attribute values based on product descriptions with minimal user intervention, or a priori tagging.<br>
E. Outfit recommendationbased on tagged attributes.
