# RESUME_NER_DATASET
Resume ner dataset in spacy format

# Description
The data was collect and label on 120 CVs in IT (Web, android, data science, project manager, database, network,...) domain and some are on HR, Marketing, Sale

The data format as spacy json format, total length 634 files

# Data example

```
{
    "classes": [
        "PERSON_NAME",
        "ADDRESS",
        "EDUCATION",
        "GPA",
        "SKILL",
        "EXPERIENCE_LEVEL",
        "JOB_TITLE",
        "DATE_BIRTH",
        "MAJOR",
        "MARIAGE_STATUS",
        "ORGANIZATION",
        "GENDER"
    ],
    "annotations": [
        [
            "Responsible for administration of AutoCAD Inventor and Vault for configurations environments and licenses Work with daily CAD users to determine and implement best practices training and solutions for CAD related issues in a timely manner.",
            {
                "entities": [
                    [
                        34,
                        50,
                        "SKILL"
                    ],
                    [
                        55,
                        60,
                        "SKILL"
                    ],
                    [
                        122,
                        125,
                        "SKILL"
                    ],
                    [
                        201,
                        204,
                        "SKILL"
                    ]
                ]
            }
        ]
    ]
}
```

You can view ner resume project for usage example at link: https://github.com/minhquan23102000/NLP_NER_ON_RESUME
