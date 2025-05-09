# transit-test-data
Test data for public transport guide app

## lineId logic

First two digits: Region code 1<br />
Second two digits: Region code 2
- Those are supposed to be in ascending order.<br />

Third two digits: Line identifier between those two regions.
Fourth two digits: Direction identifier

### Region codes
50 - Nevşehir<br />
51 - Acıgöl<br />
52 - Avanos<br />
53 - Derinkuyu<br />
54 - Gülşehir<br />
55 - Hacıbektaş<br />
56 - Kozaklı<br />
57 - Ürgüp<br />
58 - Göreme<br />
59 - Avanos<br />
60 - Uçhisar<br />
61 - Özkonak<br />

### lineId example
52610101 - First line assigned that runs between Avanos and Özkonak, route 1
50500302 - Third local line in Nevşehir, route 2
