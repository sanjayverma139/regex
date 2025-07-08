Regex
Aadhar Card
^[2-9]{1}[0-9]{3}[-\s]?[0-9]{4}[-\s]?[0-9]{4}$

Advance :-  (?<![\/:\=\-\"\'\.\|\\\!\@\#\$\%\^\&\*\;\(\)\+\[\]\{\}])\b[2-9][0-9]{3}[-\s]?[0-9]{4}[-\s]?[0-9]{4}\b(?![\/:\=\-\"\'\.\|\\\!\@\#\$\%\^\&\*\;\(\)\+\[\]\{\}])

Indian Driving license:
^(([A-Z]{2}[0-9]{2})( )|([A-Z]{2}-[0-9]{2}))((19|20)[0-9][0-9])[0-9]{7}

^(AP|AR|AS|BR|CG|GA|GJ|HR|HP|JH|KA|KL|MP|MH|MN|ML|MZ|NL|OD|PB|RJ|SK|TN|TS|TR|UP|UK|WB|AN|CH|DD|LD|DL|PY|LA|JK)[- ]?\d{1,2}[- ]?\d{4}[- ]?\d{7}$

Voter id:
^[A-Z]{3}[ -]?\d{7}$

Passport
[A-PR-WYa-zr-wy][1-9]\d\s?\d{4}[1-9] - with exclusion on Q, X, Z
Or 
[A-Za-z][1-9]\d\s?\d{4}[1-9]{1-3} - without exclusion on Q, X, Z
GST 
\d{2}[A-Za-z]{5}\d{4}[a-zA-Z]{1}[A-Za-z\d]{1}[Zz]{1}[a-zA-Z\d]{1}
MAC Address 
(?:[0-9A-Fa-f]{2}[:-]){5}(?:[0-9A-Fa-f]{2}


Pan Card 
(?<![\/:\=\-\"\'\.\|\\\!\@\#\$\%\^\&\*\;\(\)\+\{\}])\b[a-zA-Z]{3}[PCHABGJLFpchabgJlf][A-Za-z]\d{4}[a-zA-Z]\b(?![\/:\=\-\"\'\.\|\\\!\@\#\$\%\^\&\*\;\(\)\+\{\}])



