---
description: How to download documents using Gatenox API?
---

# Attachments download

#### How to Download Your Document

1. Each document in Gatenox Hub will have its own set of URLs

```json
"documents": [
            {
                "id": "e302f38a-2bca-4d36-a6a4-1601e3bfd629",
                "purposes": [
                    "personal_document"
                ],
                "created_at": "2023-06-13T10:26:44.218Z",
                "updated_at": "2023-06-13T10:26:44.218Z",
                "document": {
                    "id": "6896ec93-7069-4467-80c1-ff9cd8e26213",
                    "country_of_issue": "PL",
                    "name": "Polish passport.png",
                    "number": "ANV 123123",
                    "document_type": "passport",
                    "date_of_issue": "2023-01-01",
                    "expiration_date": "2033-01-01",
                    "created_at": "2023-06-13T10:26:42.248Z",
                    "updated_at": "2023-06-13T10:26:42.248Z",
                    "attachments": [
                        {
                            "id": "62833342-2db1-487c-b189-4b27133dbdae",
                            "attachment_type": "main",
                            "created_at": "2023-06-13T10:26:43.193Z",
                            "updated_at": "2023-06-13T10:26:43.948Z",
                            "filename": "Polish passport.png",
                            "filesize": 22118,
                            "mime": "image/png",
                            "urls": {
                                "thumb": "https://api.sandbox.gatenox.com/verifications/47978c9b-d63f-445e-96e6-80e808e3bab1/documents/download/eyJpZCI6IjlhZDhiZmZiY.....lX3R5cGUiOiJpbWFnZS9wb",
                                "medium": "https://api.sandbox.gatenox.com/verifications/47978c9b-d63f-445e-96e6-80e808e3bab1/documents/download/eyJpZCI6ImUzZWU2NjI4NmZhM..DYxMy0yLXI4b3h3Zi5wbmc",
                                "original": "https://api.sandbox.gatenox.com/verifications/47978c9b-d63f-445e-96e6-80e808e3bab1/documents/download/eyJpZCI6IjVhMmFmNDVl...R5cGUiOiJpbWFnZS9wbmcifX0"
                            }
                        }
                    ]
                }
            }
```

2. To download the document get the last set of chars after "/" (for example: eyJpZCI6IjlhZDhiZmZiY.....lX3R5cGUiOiJpbWFnZS9wb) and invoke /attachment endpoint providing the verification\_id and rest parameter ("eyJpZCI6IjlhZDhiZmZiY.....lX3R5cGUiOiJpbWFnZS9wb").&#x20;

{% swagger src="../../.gitbook/assets/gatenox_api_1_5_1.yaml" path="/api/v1/attachments/{rest}" method="get" %}
[gatenox_api_1_5_1.yaml](../../.gitbook/assets/gatenox_api_1_5_1.yaml)
{% endswagger %}

