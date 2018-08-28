{
  "info": {
    "name": "Global Change Information System API List roles",
    "_postman_id": "17ca0260-6d8c-45b2-adc8-40c657b8f2b7",
    "description": "Get a list of the types of roles for contributors.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Activities",
      "item": [
        {
          "id": "b40beecf-996a-43e1-a5f3-d57edf506688",
          "name": "list-the-activities-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/activity?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the activities, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "73f7622d-9d58-41bc-8f4f-0fd7bcc4c331"
            }
          ]
        }
      ]
    },
    {
      "name": "Representation",
      "item": [
        {
          "id": "8af30526-c89f-416c-9118-280164fce5b0",
          "name": "get-json-which-represents-the-structure-of-an-activity",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "activity/:activity_identifier"
              ],
              "variable": [
                {
                  "id": "activity_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of an activity."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "641a4114-05f8-4607-b6da-4d8ae80e92ee"
            }
          ]
        },
        {
          "id": "5317c154-df45-4b96-851a-c20b88db6f20",
          "name": "get-json-which-represents-the-structure-of-an-array",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "array/:array_identifier"
              ],
              "query": [
                {
                  "key": "with_gcmd",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "with_regions",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "array_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of an array."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8e211dea-7259-4384-bd91-df7f3163ec77"
            }
          ]
        },
        {
          "id": "f082ba64-493b-4889-946b-60a9c0a8acb0",
          "name": "get-json-which-represents-the-structure-of-an-article",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "article/:article_identifier"
              ],
              "query": [
                {
                  "key": "with_gcmd",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "with_regions",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "article_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of an article."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7b8577c5-8550-47df-aa02-cdc319757c0c"
            }
          ]
        },
        {
          "id": "f96783f2-2aa4-47cb-966b-43c2cba62c0c",
          "name": "get-json-which-represents-the-structure-of-a-book",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "book/:book_identifier"
              ],
              "query": [
                {
                  "key": "with_gcmd",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "with_regions",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "book_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a book."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8a40b8f3-367a-452d-bea3-4b48de7939cc"
            }
          ]
        },
        {
          "id": "a479aad0-c9eb-4683-a987-a0c642e26ab5",
          "name": "get-json-which-represents-the-structure-of-a-dataset",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "dataset/:dataset_identifier"
              ],
              "variable": [
                {
                  "id": "dataset_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a dataset."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d3424bdb-7c52-4d64-ae7d-34dfb94c55b9"
            }
          ]
        },
        {
          "id": "f22d6512-4ef6-40eb-ae45-f9d72cfb54e3",
          "name": "get-json-which-represents-the-structure-of-a-file",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "file/:file_identifier"
              ],
              "variable": [
                {
                  "id": "file_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a file."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "17a26091-9599-4e53-a925-ad60a05c482d"
            }
          ]
        },
        {
          "id": "265d0b3a-94d7-4bdd-937c-b0268618ee12",
          "name": "get-json-which-represents-the-structure-of-a-gcmd-keyword",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "gcmd_keyword/:gcmd_keyword_identifier"
              ],
              "variable": [
                {
                  "id": "gcmd_keyword_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a GCMD keyword."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ee256980-eda8-45a2-83d0-1e9c2a2ac6f1"
            }
          ]
        },
        {
          "id": "630b9519-2779-4e3e-bf80-80e04b53f98b",
          "name": "get-json-which-represents-the-structure-of-a-generic-publication",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "generic/:generic_identifier"
              ],
              "variable": [
                {
                  "id": "generic_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a generic publication."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f6106d1e-e069-40e0-abeb-7cd90c9d960a"
            }
          ]
        },
        {
          "id": "66711ae9-a9af-43c6-a6d9-4f9fa0f17510",
          "name": "get-json-which-represents-the-structure-of-an-image",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "image/:image_identifier"
              ],
              "query": [
                {
                  "key": "with_gcmd",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "with_regions",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "image_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of an image."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a37d2c54-5d65-42e7-bd78-622d6dbe9323"
            }
          ]
        },
        {
          "id": "7abb01f3-901e-4514-af9e-a17d8dca5d54",
          "name": "get-json-which-represents-the-structure-of-an-instrument",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "instrument/:instrument_identifier"
              ],
              "variable": [
                {
                  "id": "instrument_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of an instrument."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fa819186-c434-461a-ba8a-2ea84ed28003"
            }
          ]
        },
        {
          "id": "751c721b-3e86-4aed-8a0e-fb206d5d880d",
          "name": "get-json-which-represents-the-structure-of-a-journal",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "journal/:journal_identifier"
              ],
              "variable": [
                {
                  "id": "journal_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a journal."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "22da807b-e4af-4f5e-88e9-8d6cae6ac0c6"
            }
          ]
        },
        {
          "id": "1d3b65d2-5015-47f6-a2a5-29110b90414c",
          "name": "get-json-which-represents-the-structure-of-a-lexicon",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "lexicon/:lexicon_identifier"
              ],
              "variable": [
                {
                  "id": "lexicon_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a lexicon."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b9d8e87c-793f-4a16-bf83-eef195a3a3ad"
            }
          ]
        },
        {
          "id": "0e3ecf79-2b59-4019-9df6-ac55ac28aebe",
          "name": "get-json-which-represents-the-structure-of-a-model",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "model/:model_identifier"
              ],
              "variable": [
                {
                  "id": "model_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a model."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "85845280-0f59-4602-9ee3-5a75bba9b08e"
            }
          ]
        },
        {
          "id": "7398293b-27e9-4c80-8211-610a3c5d04ab",
          "name": "get-json-which-represents-the-structure-of-a-model-run",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "model_run/:model_identifier/:scenario_identifier/:range_start/:range_end/:spatial_resolution/:time_resolution/:sequence"
              ],
              "variable": [
                {
                  "id": "model_identifier",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "range_end",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "range_start",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "scenario_identifier",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "sequence",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "spatial_resolution",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "time_resolution",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a model run."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cd6a621e-2066-47dc-a989-98d615e82ccb"
            }
          ]
        },
        {
          "id": "68f1e1e3-1226-4b31-82be-7c9f3a93b1c9",
          "name": "get-json-which-represents-the-structure-of-a-model-run",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "model_run/:model_run_identifier"
              ],
              "variable": [
                {
                  "id": "model_run_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a model run."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "12a91585-8c98-4719-b0d5-d1ca348abb78"
            }
          ]
        },
        {
          "id": "ace345f6-71df-4f53-a060-bcdcebb1a462",
          "name": "get-json-which-represents-the-structure-of-an-organization",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "organization/:organization_identifier"
              ],
              "variable": [
                {
                  "id": "organization_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of an organization."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0ae9359d-ebad-431b-b625-dca6c45a5f60"
            }
          ]
        },
        {
          "id": "e05ba766-f202-4f83-8789-9b8e8c93af9c",
          "name": "get-json-which-represents-the-structure-of-a-person",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "person/:person_identifier"
              ],
              "variable": [
                {
                  "id": "person_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a person."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ddbecb7b-e1da-4628-b1d8-c80c5ea7dea4"
            }
          ]
        },
        {
          "id": "c2b2518f-6c3a-40f2-8ac7-dbba92f5b235",
          "name": "get-json-which-represents-the-structure-of-a-platform",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "platform/:platform_identifier"
              ],
              "variable": [
                {
                  "id": "platform_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a platform."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "50f2c808-3679-4dd1-915c-7ceaefb24156"
            }
          ]
        },
        {
          "id": "5c2446f7-3913-4216-9083-6213fc5f13f7",
          "name": "get-json-which-represents-the-structure-of-an-instrument-on-a-platform",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "platform/:platform_identifier/instrument/:instrument_identifier"
              ],
              "variable": [
                {
                  "id": "instrument_identifier",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "platform_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of an instrument on a platform."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b243d448-ed81-44f8-8384-a7cec161e890"
            }
          ]
        },
        {
          "id": "14acd4d0-0544-4772-88c2-818bdcece26c",
          "name": "get-json-which-represents-the-structure-of-a-project",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "project/:project_identifier"
              ],
              "variable": [
                {
                  "id": "project_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a project."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0d6e947c-dfc8-4f7b-bd5e-46e1c644679c"
            }
          ]
        },
        {
          "id": "8b91b8c0-d843-4c17-a8fb-134e8700cd32",
          "name": "get-json-which-represents-the-structure-of-a-reference",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "reference/:reference_identifier"
              ],
              "variable": [
                {
                  "id": "reference_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a reference."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a4024c4b-3fd7-477f-aa3a-bec42a77a893"
            }
          ]
        },
        {
          "id": "43e16ba2-8908-4b19-b962-78df9f466316",
          "name": "get-json-which-represents-the-structure-of-a-region",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "region/:region_identifier"
              ],
              "variable": [
                {
                  "id": "region_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a region."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "91652988-e9c6-46d1-957b-230d2d24373d"
            }
          ]
        },
        {
          "id": "02aa35ab-df98-48d8-b25c-6fab40170960",
          "name": "get-json-which-represents-the-structure-of-a-report",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "report/:report_identifier"
              ],
              "query": [
                {
                  "key": "with_gcmd",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "with_regions",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "report_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a report."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8479774e-50da-4ea6-a257-9014017347c2"
            }
          ]
        },
        {
          "id": "a696078b-4b54-4835-89a6-a3b5303cd56d",
          "name": "get-json-which-represents-the-structure-of-a-chapter",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "report/:report_identifier/chapter/:chapter_identifier"
              ],
              "query": [
                {
                  "key": "ids",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "with_gcmd",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "with_regions",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "chapter_identifier",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "report_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a chapter."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "86eca7ca-8c60-4375-9f21-193875114ce9"
            }
          ]
        },
        {
          "id": "92ea3c48-eacb-4a63-abda-df80616eb8c0",
          "name": "get-json-which-represents-the-structure-of-a-figure-in-a-chapter",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "report/:report_identifier/chapter/:chapter_identifier/figure/:figure_identifier"
              ],
              "query": [
                {
                  "key": "ids",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "with_gcmd",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "with_regions",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "chapter_identifier",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "figure_identifier",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "report_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a figure in a chapter."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6218147d-9c01-4c9d-a575-a4ec54aec36d"
            }
          ]
        },
        {
          "id": "67684e13-826b-4d98-9073-46fd390f508b",
          "name": "get-json-which-represents-the-structure-of-a-finding-in-a-chapter",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "report/:report_identifier/chapter/:chapter_identifier/finding/:finding_identifier"
              ],
              "query": [
                {
                  "key": "with_gcmd",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "with_regions",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "chapter_identifier",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "finding_identifier",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "report_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a finding in a chapter."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8423c56e-b240-443c-abff-c95926afd70f"
            }
          ]
        },
        {
          "id": "c591cef5-58a9-4254-8ed2-734bb384adcc",
          "name": "get-json-which-represents-the-structure-of-a-table-in-a-chapter",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "report/:report_identifier/chapter/:chapter_identifier/table/:table_identifier"
              ],
              "query": [
                {
                  "key": "with_gcmd",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "with_regions",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "chapter_identifier",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "report_identifier",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "table_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a table in a chapter."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "144c83de-60e4-48a1-8b52-a6994575ec4c"
            }
          ]
        },
        {
          "id": "659d4b94-f154-4455-ab0b-f6ff4d87b245",
          "name": "get-json-which-represents-the-structure-of-a-figure",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "report/:report_identifier/figure/:figure_identifier"
              ],
              "query": [
                {
                  "key": "with_gcmd",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "with_regions",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "figure_identifier",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "report_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a figure."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eaad4cd9-49fb-46ad-9404-2499127994b0"
            }
          ]
        },
        {
          "id": "0ce91621-2361-4c24-a099-5058e966358a",
          "name": "get-json-which-represents-the-structure-of-a-finding",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "report/:report_identifier/finding/:finding_identifier"
              ],
              "query": [
                {
                  "key": "with_gcmd",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "with_regions",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "finding_identifier",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "report_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a finding."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e4b66268-8e07-4bdf-9d03-e8d48e1d4dd3"
            }
          ]
        },
        {
          "id": "9f58c361-6399-45bc-9118-12a26b7abd74",
          "name": "get-json-which-represents-the-structure-of-a-table",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "report/:report_identifier/table/:table_identifier"
              ],
              "query": [
                {
                  "key": "with_gcmd",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "with_regions",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "report_identifier",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "table_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a table."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6bd98d4a-196a-4ff6-b93e-fa9e0932ef88"
            }
          ]
        }
      ]
    },
    {
      "name": "Arrays",
      "item": [
        {
          "id": "c159f173-9f82-48dd-adff-c2d832650b6f",
          "name": "list-the-arrays-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/array?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the arrays, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c24882a0-76a7-49b3-9491-fc92ee4b1f61"
            }
          ]
        },
        {
          "id": "4de13573-6a7f-4bcd-b87c-e23fa8aedac0",
          "name": "list-the-arrays-associated-with-a-report-20-per-page",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "report/:report_identifier/array"
              ],
              "query": [
                {
                  "key": "all",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "report_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the arrays associated with a report, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "38361b22-cfe3-40dc-a41d-69c0d8b6d8d7"
            }
          ]
        }
      ]
    },
    {
      "name": "Articles",
      "item": [
        {
          "id": "86bd9f21-ad7d-42ba-bc59-5b2d861262ba",
          "name": "list-the-articles-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/article?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the articles, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "806eafb0-d964-47db-9411-151c9d7ac738"
            }
          ]
        }
      ]
    },
    {
      "name": "Books",
      "item": [
        {
          "id": "a8756bd0-2f48-43c1-963a-19730a278867",
          "name": "list-the-books-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/book?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the books, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fe1986e4-9c08-4027-bb53-5750d579638a"
            }
          ]
        },
        {
          "id": "eaf613e9-1f98-4c78-8a6d-4e15b682dde5",
          "name": "list-the-books-associated-with-a-report-20-per-page",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "report/:report_identifier/book"
              ],
              "query": [
                {
                  "key": "all",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "report_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the books associated with a report, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7e0c9748-6562-4d4a-a806-98baa2a49257"
            }
          ]
        }
      ]
    },
    {
      "name": "Redirect",
      "item": [
        {
          "id": "dc8acc29-ad28-405e-881f-a857dac9b863",
          "name": "given-a-numeric-id-redirect-to-the-full-uri-of-a-contributor",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "contributor/:contributor_identifier"
              ],
              "variable": [
                {
                  "id": "contributor_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Given a numeric ID, redirect to the full URI of a contributor."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fe6cb1d3-7058-4a0b-8fd9-4aeec1df73e2"
            }
          ]
        },
        {
          "id": "b68d14ae-3471-413d-995c-a6b10fe17416",
          "name": "given-a-name-case-sensitive-concatenated-by-dashes-redirect-if-there-is-a-single-match--the-first-an",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "person/:name"
              ],
              "variable": [
                {
                  "id": "name",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Given a name (case sensitive, concatenated by dashes), redirect if there is a single match.  The first and last names can be in either order."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4a568574-9652-4ee7-9d85-17967777438b"
            }
          ]
        },
        {
          "id": "58812b9b-2c84-4287-93c2-474e91f0d0dd",
          "name": "given-an-orcid-if-there-is-a-match-redirect-to-the-persons-uri",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "person/:orcid"
              ],
              "variable": [
                {
                  "id": "orcid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Given an ORCID, if there is a match, redirect to the persons URI."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "955f8bf7-564e-4422-bcc5-d7dd763c9fb4"
            }
          ]
        },
        {
          "id": "2a148846-618b-4b77-bb81-9707f73f9ec5",
          "name": "given-a-numeric-id-redirect-to-the-full-uri-of-a-publication",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "publication/:publication_identifier"
              ],
              "variable": [
                {
                  "id": "publication_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Given a numeric ID, redirect to the full URI of a publication."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4fc1b99f-6efa-43f4-9e33-fd2ce6d9c0b9"
            }
          ]
        }
      ]
    },
    {
      "name": "Datasets",
      "item": [
        {
          "id": "990072f1-240c-4723-b61e-173f6182d1a5",
          "name": "list-the-datasets-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/dataset?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the datasets, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f1736bd8-d011-4e27-b5a5-d29fe8d1a23c"
            }
          ]
        }
      ]
    },
    {
      "name": "Look",
      "item": [
        {
          "id": "12caec33-db9f-4ba9-9b9c-e9876bd22388",
          "name": "given-a-doi-return-a-redirect-to-the-gcis-dataset",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "dataset/lookup/:doi"
              ],
              "variable": [
                {
                  "id": "doi",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Given a DOI, return a redirect to the GCIS dataset."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3fd36119-742b-4dd1-a602-10632a619905"
            }
          ]
        }
      ]
    },
    {
      "name": "Folder",
      "item": [
        {
          "id": "1d3f538d-07dd-49b7-af7c-14861ea03c06",
          "name": "list-all-the-figures-in-gcis",
          "request": {
            "url": "http://data.globalchange.gov/figure?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List all the figures in GCIS."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7c6d1319-364f-4fab-b76f-23b2440eddb4"
            }
          ]
        }
      ]
    },
    {
      "name": "GCMD",
      "item": [
        {
          "id": "5e6974cf-80af-48b4-8a34-399c55d3581d",
          "name": "list-the-gcmd-keywords-in-the-gcis-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/gcmd_keyword?page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the GCMD keywords in the GCIS, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "19908307-fade-4748-832e-8814e3a8cb86"
            }
          ]
        }
      ]
    },
    {
      "name": "Generic",
      "item": [
        {
          "id": "e3a094a3-c936-42da-a989-d46836ca3a3b",
          "name": "list-the-generic-publications-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/generic?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the generic publications, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "daf9a181-e584-47ce-aeef-6ef0d1168b82"
            }
          ]
        }
      ]
    },
    {
      "name": "Images",
      "item": [
        {
          "id": "299388f6-e55c-4744-a657-50400e0b6b5d",
          "name": "list-the-images-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/image?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the images, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6b0f26ed-2bbd-4338-89ed-fd34957bd317"
            }
          ]
        },
        {
          "id": "6758032d-9fd7-45ad-ae73-24c4237e41f7",
          "name": "list-the-images-associated-with-a-report-20-per-page",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "report/:report_identifier/image"
              ],
              "query": [
                {
                  "key": "all",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "report_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the images associated with a report, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c175e446-bf97-4c6f-beab-c0aef00b17d4"
            }
          ]
        }
      ]
    },
    {
      "name": "Instruments",
      "item": [
        {
          "id": "3d9a1ee3-699f-4d8a-8a7f-ac3430ad633a",
          "name": "list-the-instruments-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/instrument?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the instruments, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aef7792f-06c8-4413-8a2a-a42c24dba603"
            }
          ]
        },
        {
          "id": "aa7fe075-6f36-4c9c-bfd7-3fea538c14d9",
          "name": "list-the-instruments-on-a-platform-20-per-page",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "platform/:platform_identifier/instrument"
              ],
              "query": [
                {
                  "key": "all",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "platform_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the instruments on a platform, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e192fe40-484c-4d28-a852-c9b2598607df"
            }
          ]
        }
      ]
    },
    {
      "name": "Journals",
      "item": [
        {
          "id": "716f3a3d-c368-40a1-950c-1598901ef924",
          "name": "list-the-journals-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/journal?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the journals, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2fcc88e9-a3fb-4916-9a74-8e0bb51562c5"
            }
          ]
        }
      ]
    },
    {
      "name": "Lexicons",
      "item": [
        {
          "id": "4020a075-0671-4f57-8dc8-987433d9d4b6",
          "name": "list-the-lexicons-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/lexicon?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the lexicons, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5168dca9-ad8a-4aa7-89d5-665ae92d9174"
            }
          ]
        }
      ]
    },
    {
      "name": "Lookup",
      "item": [
        {
          "id": "a9dceda1-ff83-4c53-b6b2-421605b8a622",
          "name": "given-a-lexicon-term-and-context-return-a-303-redirect-to-a-gcid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "lexicon/:lexicon_identifier/find/:context/:term"
              ],
              "variable": [
                {
                  "id": "context",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "lexicon_identifier",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "term",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Given a lexicon, term, and context, return a 303 redirect to a GCID"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "79ef6bf8-791d-44e9-9171-e4488f4601aa"
            }
          ]
        },
        {
          "id": "202567ab-b326-4cca-98b0-b870586e09d5",
          "name": "given-a-lexicon-term-and-context-return-a-303-redirect-to-a-gcid1",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "lexicon/:lexicon_identifier/:context/:term"
              ],
              "variable": [
                {
                  "id": "context",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "lexicon_identifier",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "term",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Given a lexicon, term, and context, return a 303 redirect to a GCID"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "45547ca6-c093-4a92-9054-72cf1e7c537d"
            }
          ]
        }
      ]
    },
    {
      "name": "Terms",
      "item": [
        {
          "id": "8d83ae75-e5a6-4a91-a34a-5e1e417adfdc",
          "name": "list-the-terms-within-a-context-of-a-lexicon",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "lexicon/:lexicon_identifier/list/:context"
              ],
              "variable": [
                {
                  "id": "context",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "lexicon_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the terms within a context of a lexicon"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b95a6e1d-8e23-4399-bfc2-240167060491"
            }
          ]
        }
      ]
    },
    {
      "name": "Overall",
      "item": [
        {
          "id": "40c93b86-c2a2-48be-b39a-565e9ec74544",
          "name": "get-overall-metrics-about-gcis-data",
          "request": {
            "url": "http://data.globalchange.gov/metrics",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get overall metrics about GCIS data"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "185a8e31-068e-4eee-b718-fc4d7e92fe03"
            }
          ]
        }
      ]
    },
    {
      "name": "Models",
      "item": [
        {
          "id": "3291448d-ec66-484c-bedf-a380c1071302",
          "name": "list-the-models-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/model?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the models, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "33c88b09-b8bb-46a3-b55a-7f9ad7878e6f"
            }
          ]
        }
      ]
    },
    {
      "name": "Model",
      "item": [
        {
          "id": "098795da-1b78-4c2f-8b41-fec47e732cef",
          "name": "list-the-model-runs-for-a-particular-model-20-per-page",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "model/:model_identifier/run"
              ],
              "query": [
                {
                  "key": "all",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "model_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the model runs for a particular model, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1036e275-5e08-4a9a-bf9d-8f0cc07f6ff4"
            }
          ]
        },
        {
          "id": "77d63924-12c2-4418-a158-c84ebb8ab696",
          "name": "list-the-model-runs-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/model_run?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the model runs, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1ea58056-6606-4f1f-bb49-230f7ab84418"
            }
          ]
        }
      ]
    },
    {
      "name": "Organizations",
      "item": [
        {
          "id": "b3a7d830-ecce-48e3-b59e-cfdf42134d57",
          "name": "list-the-organizations-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/organization?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Li