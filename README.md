Collects class information from the [University of Maryland Schedule of
classes]. 

```
pipenv install
./testudo.py
```

Then you should find a populated directory structure in the data directory:

    data/{term}/{dept}/{class}.json

Each class JSON file looks something like:

```json
{
  "id": "ANTH222",
  "title": "Introduction to Ecological and Evolutionary Anthropology",
  "credits": "4",
  "description": "Credit only granted for: ANTH220 or ANTH222.",
  "grading-method": [
    "Reg",
    "P-F",
    "Aud"
  ],
  "sections": [
    {
      "id": "0101",
      "instructor": "Barnet Pavao-Zuckerman",
      "seats": "20,",
      "open-seats": "0,",
      "waitlist": "0",
      "days": "TuTh",
      "start": "9:30am",
      "end": "10:45am",
      "building": "ATL",
      "room": "2324"
    },
    {
      "id": "0102",
      "instructor": "Barnet Pavao-Zuckerman",
      "seats": "20,",
      "open-seats": "0,",
      "waitlist": "0",
      "days": "TuTh",
      "start": "9:30am",
      "end": "10:45am",
      "building": "ATL",
      "room": "2324"
    },
    {
      "id": "0103",
      "instructor": "Barnet Pavao-Zuckerman",
      "seats": "20,",
      "open-seats": "0,",
      "waitlist": "0",
      "days": "TuTh",
      "start": "9:30am",
      "end": "10:45am",
      "building": "ATL",
      "room": "2324"
    },
    {
      "id": "0104",
      "instructor": "Barnet Pavao-Zuckerman",
      "seats": "20,",
      "open-seats": "0,",
      "waitlist": "0",
      "days": "TuTh",
      "start": "9:30am",
      "end": "10:45am",
      "building": "ATL",
      "room": "2324"
    },
    {
      "id": "0105",
      "instructor": "Barnet Pavao-Zuckerman",
      "seats": "20,",
      "open-seats": "0,",
      "waitlist": "0",
      "days": "TuTh",
      "start": "9:30am",
      "end": "10:45am",
      "building": "ATL",
      "room": "2324"
    },
    {
      "id": "0106",
      "instructor": "Barnet Pavao-Zuckerman",
      "seats": "20,",
      "open-seats": "0,",
      "waitlist": "0",
      "days": "TuTh",
      "start": "9:30am",
      "end": "10:45am",
      "building": "ATL",
      "room": "2324"
    }
  ],
  "term": "201801",
  "department": "Anthropology"
}
```
