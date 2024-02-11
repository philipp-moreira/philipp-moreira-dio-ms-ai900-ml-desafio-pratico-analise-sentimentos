### Speech to Text
![image](https://github.com/philipp-moreira/philipp-moreira-dio-ms-ai900-ml-desafio-pratico-analise-sentimentos/assets/17642499/92a25a14-638f-4c2c-9cbd-661dc1023dc9)

### Analyze Tex

![image](https://github.com/philipp-moreira/philipp-moreira-dio-ms-ai900-ml-desafio-pratico-analise-sentimentos/assets/17642499/b16d77b2-fff6-4248-bd74-a799d1070291)

![image](https://github.com/philipp-moreira/philipp-moreira-dio-ms-ai900-ml-desafio-pratico-analise-sentimentos/assets/17642499/fd97e07d-dd41-4346-85b3-8224a9b086b1)

![image](https://github.com/philipp-moreira/philipp-moreira-dio-ms-ai900-ml-desafio-pratico-analise-sentimentos/assets/17642499/3228819f-1f95-4c9e-9d0d-88e765599f78)

```json
{
    "documents": [
        {
            "id": "id__445",
            "sentiment": "negative",
            "confidenceScores": {
                "positive": 0,
                "neutral": 0.03,
                "negative": 0.96
            },
            "sentences": [
                {
                    "sentiment": "negative",
                    "confidenceScores": {
                        "positive": 0,
                        "neutral": 0.01,
                        "negative": 0.98
                    },
                    "offset": 0,
                    "length": 219,
                    "text": " Tired hotel with poor service  The Royal Hotel, London, United Kingdom  5/6/2018  This is an old hotel (has been around since 1950's) and the room furnishings are average - becoming a bit old now and require changing. ",
                    "targets": [
                        {
                            "sentiment": "negative",
                            "confidenceScores": {
                                "positive": 0.01,
                                "negative": 0.99
                            },
                            "offset": 7,
                            "length": 5,
                            "text": "hotel",
                            "relations": [
                                {
                                    "relationType": "assessment",
                                    "ref": "#/documents/0/sentences/0/assessments/0"
                                }
                            ]
                        },
                        {
                            "sentiment": "negative",
                            "confidenceScores": {
                                "positive": 0.01,
                                "negative": 0.99
                            },
                            "offset": 23,
                            "length": 7,
                            "text": "service",
                            "relations": [
                                {
                                    "relationType": "assessment",
                                    "ref": "#/documents/0/sentences/0/assessments/1"
                                }
                            ]
                        }
                    ],
                    "assessments": [
                        {
                            "sentiment": "negative",
                            "confidenceScores": {
                                "positive": 0.01,
                                "negative": 0.99
                            },
                            "offset": 1,
                            "length": 5,
                            "text": "Tired",
                            "isNegated": false
                        },
                        {
                            "sentiment": "negative",
                            "confidenceScores": {
                                "positive": 0.01,
                                "negative": 0.99
                            },
                            "offset": 18,
                            "length": 4,
                            "text": "poor",
                            "isNegated": false
                        }
                    ]
                },
                {
                    "sentiment": "negative",
                    "confidenceScores": {
                        "positive": 0,
                        "neutral": 0.01,
                        "negative": 0.99
                    },
                    "offset": 219,
                    "length": 102,
                    "text": "The internet didn't work and had to come to one of their office rooms to check in for my flight home. ",
                    "targets": [
                        {
                            "sentiment": "negative",
                            "confidenceScores": {
                                "positive": 0,
                                "negative": 1
                            },
                            "offset": 223,
                            "length": 8,
                            "text": "internet",
                            "relations": [
                                {
                                    "relationType": "assessment",
                                    "ref": "#/documents/0/sentences/1/assessments/0"
                                }
                            ]
                        }
                    ],
                    "assessments": [
                        {
                            "sentiment": "negative",
                            "confidenceScores": {
                                "positive": 0,
                                "negative": 1
                            },
                            "offset": 239,
                            "length": 4,
                            "text": "work",
                            "isNegated": true
                        }
                    ]
                },
                {
                    "sentiment": "negative",
                    "confidenceScores": {
                        "positive": 0.01,
                        "neutral": 0.08,
                        "negative": 0.91
                    },
                    "offset": 321,
                    "length": 77,
                    "text": "The website says it's close to the British Museum, but it's too far to walk. ",
                    "targets": [],
                    "assessments": []
                }
            ],
            "warnings": []
        }
    ],
    "errors": [],
    "modelVersion": "2022-11-01"
}
```
