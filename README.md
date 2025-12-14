# Google Maps Scraper v3

A tool for extracting **accurate and comprehensive place data from Google Maps**. This scraper collects **full place details**, including **name, category, precise address, geographic coordinates, international and local phone numbers, opening hours, user ratings, service features**, and other related metadata.  
The generated output consists of **raw responses retrieved directly from the official Google Maps Places API**. The data is stored **without modification**, preserving the original **field names, structure, and semantics** exactly as returned by Google, making it suitable for **geospatial data analysis, auditing, and location-based software development**.

The purpose of this repository is to **demonstrate the scraper and provide verified samples of raw place data directly collected from the official Google Maps Places API**. If you require **custom place datasets**, you may contact me for **tailored data extraction**, without geographic or place-type limitations.

---

## 🔹 Sample Output

- A sample dataset for **100 restaurants in London** is available in the [examples](https://github.com/parhamkhani/google-maps-scraper-v3-en/tree/main/examples) directory.

### Example Google Maps place + simplified JSON output

<div style="text-align: center; margin: 20px;">
  <img src="https://github.com/parhamkhani/google-maps-scraper-v3-en/blob/main/Toklas.png"
       width="600"
       style="text-align: center; margin: 20px;">
</div><br>

<details>
<summary>View JSON (click to expand)</summary>

<div style="max-height:400px; overflow:100px; border:1px solid #ddd; padding:10px; background:#f7f7f7; margin:10px;">
<pre>
{
    "accessibilityOptions": {
        "wheelchairAccessibleEntrance": true,
        "wheelchairAccessibleParking": false,
        "wheelchairAccessibleRestroom": true,
        "wheelchairAccessibleSeating": true
    },
    "addressComponents": [
        {
            "languageCode": "en-US",
            "longText": "1",
            "shortText": "1",
            "types": [
                "street_number"
            ]
        },
        {
            "languageCode": "en",
            "longText": "Surrey Street",
            "shortText": "Surrey St",
            "types": [
                "route"
            ]
        },
        {
            "languageCode": "en",
            "longText": "Temple",
            "shortText": "Temple",
            "types": [
                "neighborhood",
                "political"
            ]
        },
        {
            "languageCode": "en",
            "longText": "London",
            "shortText": "London",
            "types": [
                "postal_town"
            ]
        },
        {
            "languageCode": "en",
            "longText": "Greater London",
            "shortText": "Greater London",
            "types": [
                "administrative_area_level_2",
                "political"
            ]
        },
        {
            "languageCode": "en",
            "longText": "England",
            "shortText": "England",
            "types": [
                "administrative_area_level_1",
                "political"
            ]
        },
        {
            "languageCode": "en",
            "longText": "United Kingdom",
            "shortText": "GB",
            "types": [
                "country",
                "political"
            ]
        },
        {
            "languageCode": "en-US",
            "longText": "WC2R 2ND",
            "shortText": "WC2R 2ND",
            "types": [
                "postal_code"
            ]
        }
    ],
    "addressDescriptor": {
        "areas": [
            {
                "containment": "OUTSKIRTS",
                "displayName": {
                    "languageCode": "en",
                    "text": "Temple"
                },
                "name": "places/ChIJFxpJdLMEdkgRDlwTEZAvFIY",
                "placeId": "ChIJFxpJdLMEdkgRDlwTEZAvFIY"
            },
            {
                "containment": "OUTSKIRTS",
                "displayName": {
                    "languageCode": "en",
                    "text": "King's College London"
                },
                "name": "places/ChIJ3VW0o7UEdkgR8eAcbhKByyg",
                "placeId": "ChIJ3VW0o7UEdkgR8eAcbhKByyg"
            }
        ],
        "landmarks": [
            {
                "displayName": {
                    "languageCode": "en",
                    "text": "King's College London"
                },
                "name": "places/ChIJ3VW0o7UEdkgRjZLQfvs-ZLA",
                "placeId": "ChIJ3VW0o7UEdkgRjZLQfvs-ZLA",
                "spatialRelationship": "DOWN_THE_ROAD",
                "straightLineDistanceMeters": 64.58972,
                "travelDistanceMeters": 56.682156,
                "types": [
                    "establishment",
                    "point_of_interest",
                    "university"
                ]
            },
            {
                "displayName": {
                    "languageCode": "en",
                    "text": "Somerset House"
                },
                "name": "places/ChIJcWfE87UEdkgRoYClOMTsOQQ",
                "placeId": "ChIJcWfE87UEdkgRoYClOMTsOQQ",
                "spatialRelationship": "AROUND_THE_CORNER",
                "straightLineDistanceMeters": 156.42497,
                "travelDistanceMeters": 218.00893,
                "types": [
                    "establishment",
                    "museum",
                    "point_of_interest",
                    "tourist_attraction"
                ]
            },
            {
                "displayName": {
                    "languageCode": "en",
                    "text": "National Trust - Strand Lane \"Roman Bath\""
                },
                "name": "places/ChIJlWj6t8sEdkgRP9R6RuyRIBE",
                "placeId": "ChIJlWj6t8sEdkgRP9R6RuyRIBE",
                "straightLineDistanceMeters": 35.51498,
                "travelDistanceMeters": 75.29127,
                "types": [
                    "establishment",
                    "point_of_interest",
                    "tourist_attraction"
                ]
            },
            {
                "displayName": {
                    "languageCode": "en",
                    "text": "Australian High Commission"
                },
                "name": "places/ChIJz0jn7M0EdkgRi3rBwJKM4jI",
                "placeId": "ChIJz0jn7M0EdkgRi3rBwJKM4jI",
                "straightLineDistanceMeters": 104.788025,
                "travelDistanceMeters": 104.9503,
                "types": [
                    "embassy",
                    "establishment",
                    "point_of_interest"
                ]
            },
            {
                "displayName": {
                    "languageCode": "en",
                    "text": "Hidden London - Aldwych Station"
                },
                "name": "places/ChIJq6z3rrUEdkgRRWqGWkfEirQ",
                "placeId": "ChIJq6z3rrUEdkgRRWqGWkfEirQ",
                "spatialRelationship": "ACROSS_THE_ROAD",
                "straightLineDistanceMeters": 29.556519,
                "travelDistanceMeters": 24.175316,
                "types": [
                    "establishment",
                    "point_of_interest",
                    "tourist_attraction"
                ]
            }
        ]
    },
    "allowsDogs": true,
    "businessStatus": "OPERATIONAL",
    "currentOpeningHours": {
        "nextOpenTime": "2025-12-11T12:00:00Z",
        "openNow": false,
        "periods": [
            {
                "close": {
                    "date": {
                        "day": 15,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 1,
                    "hour": 21,
                    "minute": 30
                },
                "open": {
                    "date": {
                        "day": 15,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 1,
                    "hour": 12,
                    "minute": 0
                }
            },
            {
                "close": {
                    "date": {
                        "day": 16,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 2,
                    "hour": 21,
                    "minute": 30
                },
                "open": {
                    "date": {
                        "day": 16,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 2,
                    "hour": 12,
                    "minute": 0
                }
            },
            {
                "close": {
                    "date": {
                        "day": 17,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 3,
                    "hour": 21,
                    "minute": 30
                },
                "open": {
                    "date": {
                        "day": 17,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 3,
                    "hour": 12,
                    "minute": 0
                }
            },
            {
                "close": {
                    "date": {
                        "day": 11,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 4,
                    "hour": 21,
                    "minute": 30
                },
                "open": {
                    "date": {
                        "day": 11,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 4,
                    "hour": 12,
                    "minute": 0
                }
            },
            {
                "close": {
                    "date": {
                        "day": 12,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 5,
                    "hour": 21,
                    "minute": 30
                },
                "open": {
                    "date": {
                        "day": 12,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 5,
                    "hour": 12,
                    "minute": 0
                }
            },
            {
                "close": {
                    "date": {
                        "day": 13,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 6,
                    "hour": 21,
                    "minute": 30
                },
                "open": {
                    "date": {
                        "day": 13,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 6,
                    "hour": 12,
                    "minute": 0
                }
            }
        ],
        "weekdayDescriptions": [
            "Monday: 12:00 – 9:30 PM",
            "Tuesday: 12:00 – 9:30 PM",
            "Wednesday: 12:00 – 9:30 PM",
            "Thursday: 12:00 – 9:30 PM",
            "Friday: 12:00 – 9:30 PM",
            "Saturday: 12:00 – 9:30 PM",
            "Sunday: Closed"
        ]
    },
    "delivery": false,
    "dineIn": true,
    "displayName": {
        "languageCode": "en",
        "text": "Toklas"
    },
    "editorialSummary": {
        "languageCode": "en",
        "text": "Trendy restaurant with a bakery & an old-school vibe offering Mediterranean-inspired cuisine."
    },
    "formattedAddress": "1 Surrey St, Temple, London WC2R 2ND, UK",
    "goodForChildren": false,
    "goodForGroups": true,
    "goodForWatchingSports": false,
    "googleMapsLinks": {
        "directionsUri": "https://www.google.com/maps/dir//''/data=!4m7!4m6!1m1!4e2!1m2!1m1!1s0x487605970abb3463:0x8bad066586d43c5a!3e0?g_mp=Cilnb29nbGUubWFwcy5wbGFjZXMudjEuUGxhY2VzLlNlYXJjaE5lYXJieRACGAEgAA",
        "photosUri": "https://www.google.com/maps/place//data=!4m3!3m2!1s0x487605970abb3463:0x8bad066586d43c5a!10e5?g_mp=Cilnb29nbGUubWFwcy5wbGFjZXMudjEuUGxhY2VzLlNlYXJjaE5lYXJieRACGAEgAA",
        "placeUri": "https://maps.google.com/?cid=10064707775366446170&g_mp=Cilnb29nbGUubWFwcy5wbGFjZXMudjEuUGxhY2VzLlNlYXJjaE5lYXJieRACGAEgAA",
        "reviewsUri": "https://www.google.com/maps/place//data=!4m4!3m3!1s0x487605970abb3463:0x8bad066586d43c5a!9m1!1b1?g_mp=Cilnb29nbGUubWFwcy5wbGFjZXMudjEuUGxhY2VzLlNlYXJjaE5lYXJieRACGAEgAA",
        "writeAReviewUri": "https://www.google.com/maps/place//data=!4m3!3m2!1s0x487605970abb3463:0x8bad066586d43c5a!12e1?g_mp=Cilnb29nbGUubWFwcy5wbGFjZXMudjEuUGxhY2VzLlNlYXJjaE5lYXJieRACGAEgAA"
    },
    "googleMapsUri": "https://maps.google.com/?cid=10064707775366446170&g_mp=Cilnb29nbGUubWFwcy5wbGFjZXMudjEuUGxhY2VzLlNlYXJjaE5lYXJieRACGAEgAA",
    "iconBackgroundColor": "#FF9E67",
    "iconMaskBaseUri": "https://maps.gstatic.com/mapfiles/place_api/icons/v2/restaurant_pinlet",
    "id": "ChIJYzS7CpcFdkgRWjzUhmUGrYs",
    "internationalPhoneNumber": "+44 20 3930 8592",
    "liveMusic": false,
    "location": {
        "latitude": 51.5120126,
        "longitude": -0.11526009999999999
    },
    "menuForChildren": false,
    "name": "places/ChIJYzS7CpcFdkgRWjzUhmUGrYs",
    "nationalPhoneNumber": "020 3930 8592",
    "outdoorSeating": true,
    "parkingOptions": {
        "paidStreetParking": true
    },
    "paymentOptions": {
        "acceptsCashOnly": false,
        "acceptsCreditCards": true,
        "acceptsDebitCards": true,
        "acceptsNfc": true
    },
    "photos": [
        {
            "authorAttributions": [
                {
                    "displayName": "Toklas",
                    "photoUri": "https://lh3.googleusercontent.com/a-/ALV-UjXy3hfUw3TODM9IsQ1Cf5F6bgyyQpu_GDbiAqAuSUj2zJ3Zpo0=s100-p-k-no-mo",
                    "uri": "https://maps.google.com/maps/contrib/106106648981812001215"
                }
            ],
            "flagContentUri": "https://www.google.com/local/imagery/report/?cb_client=maps_api_places.places_api&image_key=!1e10!2sAF1QipMSp5IVy-LC5VLU1dEpHEkmDyZocoOeYRmgS2Mu&hl=en-US",
            "googleMapsUri": "https://www.google.com/maps/place//data=!3m4!1e2!3m2!1sAF1QipMSp5IVy-LC5VLU1dEpHEkmDyZocoOeYRmgS2Mu!2e10!4m2!3m1!1s0x487605970abb3463:0x8bad066586d43c5a",
            "heightPx": 1102,
            "name": "places/ChIJYzS7CpcFdkgRWjzUhmUGrYs/photos/AZLasHqjzo6hIv7a2kyBgH6AIy1dOGR5xAsbZGVOjbjYaT-liPGcr7CzejOGvVf8PRfeLyUielpO6GsNwnPDVETfdO64B4ILiuMNC55ELq_VDB52Bgb39u49-_rG3d0NB0-U2k_9ljN4cWR9RUVzV-BA62l6R6rJm22YwN9zpEBE6gPn1YHLcyS7OtfD_leeVKFu-fTzZpZQUR2ar9LBfqBBeuUmO4hffhdbeObzZ0sNldmw8apI9gUwSzW8BU-i7nqE3VNdYsYZ5AvcfTIk2C0tKbg7-bkywON0M7irKBXN5RCt-g",
            "widthPx": 1560
        },
        {
            "authorAttributions": [
                {
                    "displayName": "Toklas",
                    "photoUri": "https://lh3.googleusercontent.com/a-/ALV-UjXy3hfUw3TODM9IsQ1Cf5F6bgyyQpu_GDbiAqAuSUj2zJ3Zpo0=s100-p-k-no-mo",
                    "uri": "https://maps.google.com/maps/contrib/106106648981812001215"
                }
            ],
            "flagContentUri": "https://www.google.com/local/imagery/report/?cb_client=maps_api_places.places_api&image_key=!1e10!2sAF1QipPW_MJ81S3riQE7mzei9Gr1gXt-mG2dqUWDuDrn&hl=en-US",
            "googleMapsUri": "https://www.google.com/maps/place//data=!3m4!1e2!3m2!1sAF1QipPW_MJ81S3riQE7mzei9Gr1gXt-mG2dqUWDuDrn!2e10!4m2!3m1!1s0x487605970abb3463:0x8bad066586d43c5a",
            "heightPx": 3600,
            "name": "places/ChIJYzS7CpcFdkgRWjzUhmUGrYs/photos/AZLasHr9oi31O23YkBSTSM_ISMF1kk4_7WDrR3viukdR2_7y4UXLoqTcWl_bh1Urr5nJ9H1batzSW9VXguVJr8_nhZ-36O_uxDl95eyFuGvYMk4qVODYho-98WqeIJF2sWTwc8Xaur92PcrCjC5aukpZS1GbUMURZw7yPmwt-l-U7_0jrfKMUlxUEkRTr8roHZctFubYKLppxtD-N0Q7xR66Etanvq0m4eqQMJB6OUGbPaUnM79dOqdgTwfd3Ulvldy8NArPo5veKtVpi22FxhVFSimQOhcZ5_FSrcD4i3jrBMf_9A",
            "widthPx": 4800
        },
        {
            "authorAttributions": [
                {
                    "displayName": "Charlie Smith",
                    "photoUri": "https://lh3.googleusercontent.com/a/ACg8ocJxwEa6WW2CEWhrgPOUKFmg7x6-sJitIr2iowejEGYfuxnLcA=s100-p-k-no-mo",
                    "uri": "https://maps.google.com/maps/contrib/107351684230236804718"
                }
            ],
            "flagContentUri": "https://www.google.com/local/imagery/report/?cb_client=maps_api_places.places_api&image_key=!1e10!2sCIABIhAxoBjGM9_sRsBJj2KXe97E&hl=en-US",
            "googleMapsUri": "https://www.google.com/maps/place//data=!3m4!1e2!3m2!1sCIABIhAxoBjGM9_sRsBJj2KXe97E!2e10!4m2!3m1!1s0x487605970abb3463:0x8bad066586d43c5a",
            "heightPx": 4032,
            "name": "places/ChIJYzS7CpcFdkgRWjzUhmUGrYs/photos/AZLasHriZLzN5ZhD9iheZn3gfL0HZAZdmu-it_3SysYre4jihUT7MBKsaSmVbgB6KqHHN4XnXYuoSrVOeObrYJb8Z8K8jhOA6suwayJMGg_QwuTadDD90r-NXQyIz-t8cFk5RdOEOqwYnmDp3WFPOmLnom4N46jO9WGyGismQHRXjEmCw00YzZQB_5jcHCVEzKpneb2rCdS5E2vSV1XmfWg6xvXR0DffH8U9uhs9ry52RKLCbuv4oFgmrA4VZ2DFynkhyMHf7-6FziCt4HCcviEsfV9zLGK8h6BFC9Fztl_VUKj0HnQ2Vfi1ja7xxHvVsge6xPpYN0Nmy7XE-GLnAmyZMIshN0qv5KABD0GOWFZw1V-lgj6hllffZ9Jakow0hGpLjbDX_1vwCLJMZuwQkttVDRGgQNRk5ylA1RQjJLJLAtrG6k8xtSaDcT63R9VjaDJF",
            "widthPx": 3024
        },
        {
            "authorAttributions": [
                {
                    "displayName": "MKO LDN",
                    "photoUri": "https://lh3.googleusercontent.com/a-/ALV-UjV06DgbIXKJnzbl3XQtXTJYfEd8vqES0FfgaTKM6cgIqzq4ox4=s100-p-k-no-mo",
                    "uri": "https://maps.google.com/maps/contrib/107715376984553565306"
                }
            ],
            "flagContentUri": "https://www.google.com/local/imagery/report/?cb_client=maps_api_places.places_api&image_key=!1e10!2sCIABIhAA3ilWZhkhEGfw0ygADHbm&hl=en-US",
            "googleMapsUri": "https://www.google.com/maps/place//data=!3m4!1e2!3m2!1sCIABIhAA3ilWZhkhEGfw0ygADHbm!2e10!4m2!3m1!1s0x487605970abb3463:0x8bad066586d43c5a",
            "heightPx": 3072,
            "name": "places/ChIJYzS7CpcFdkgRWjzUhmUGrYs/photos/AZLasHqktGabDHOa81gnSyrim2dSmJix3O1uYLMpnO1mt6tD4afe44k4c-zXHGmL9I_r53v4Eahhdv-lr5PIbdDB3kNrXka6DmSJiSR83_2T9VCt4YWYdniEzhIkK10fw71NPL8Ja1YllunM1aYbYsBj9i90dmAEmvsNzZXaRL1R7dkf5n1yWiRv8qJ_KDr3TRHA_S4HjfXAEPzbQNiFMzL-dCo2Koq-g1bonC_opJACmdVfYo4lM2V33ULQQTY8Dy-2ykK9fe0jACS20zylkUnHbWRH2EJWWYb0wdOcfBqYy7QoC1yCpVTX4FiOMBCVT9xdYbFC5e3UMKoFlfrDrMYXku00FA_yYMpsWcvzRM6T7uDfylGuUxjD4esW3wImZIhzLkE9wGxafyrHk98h-tdQzyNXdm23Tc2CC5n1-UgWA1FlXsGqgl5sK4iXM36mcg",
            "widthPx": 3072
        },
        {
            "authorAttributions": [
                {
                    "displayName": "Sharon Nash",
                    "photoUri": "https://lh3.googleusercontent.com/a/ACg8ocIIsYGUnpn1qYGbuArO8chzvfWjdjlt24YASMoGGTiZEU8lEw=s100-p-k-no-mo",
                    "uri": "https://maps.google.com/maps/contrib/106430088356431139308"
                }
            ],
            "flagContentUri": "https://www.google.com/local/imagery/report/?cb_client=maps_api_places.places_api&image_key=!1e10!2sCIHM0ogKEICAgIC_6OO1Pw&hl=en-US",
            "googleMapsUri": "https://www.google.com/maps/place//data=!3m4!1e2!3m2!1sCIHM0ogKEICAgIC_6OO1Pw!2e10!4m2!3m1!1s0x487605970abb3463:0x8bad066586d43c5a",
            "heightPx": 3024,
            "name": "places/ChIJYzS7CpcFdkgRWjzUhmUGrYs/photos/AZLasHot1Km_RUTPWwUx9yFyELY0d6X8I1YJZUyrzqiv1xKFr9Kbr4xGdbTG7Zg3NFjFmNeK5eDGjS4kpBLvvymrPZp9366l3DkLARlmdbQsFVCR4Y8pe5Wfti8jIu8PB32ic04lje_yK5bdq4CDm4kfuhkLS3cjZUrStYUjlsonjB4PWHKnzMxM_RO8dcgjeqpXVNzDuC2F2aMEafpsmm5T0iYdXbR_4RTI2dPd6XfoWsHtAZvqhPKIVSD3jF1YXfvL4cO9R1nVZNJNmLsB3t74xL7jZr7oaY__xRcUTL6jiUgHk-y_hh8ED1u9M-NKsaGsTmt30f_-NQ-HNetLHEayLGA82S8WTsSd4mceb9rmlydkeMo_c7980RgcB_JKNsMlIe54GxSRZRS_Em14fwfAuZ62C6Mw-r8zmljEdnqVaiA",
            "widthPx": 4032
        },
        {
            "authorAttributions": [
                {
                    "displayName": "Alex Isen",
                    "photoUri": "https://lh3.googleusercontent.com/a-/ALV-UjUQvwff7Gm0rtum88E1QG0ZchzjsgjKAW_-6jUOtrYph6Mzm54=s100-p-k-no-mo",
                    "uri": "https://maps.google.com/maps/contrib/100369817197716048526"
                }
            ],
            "flagContentUri": "https://www.google.com/local/imagery/report/?cb_client=maps_api_places.places_api&image_key=!1e10!2sCIHM0ogKEICAgMCwqLKbaQ&hl=en-US",
            "googleMapsUri": "https://www.google.com/maps/place//data=!3m4!1e2!3m2!1sCIHM0ogKEICAgMCwqLKbaQ!2e10!4m2!3m1!1s0x487605970abb3463:0x8bad066586d43c5a",
            "heightPx": 3024,
            "name": "places/ChIJYzS7CpcFdkgRWjzUhmUGrYs/photos/AZLasHpN27nEabKE2WlVpTlc1rmI0D9d4sPGVyPyD8zhPtAR2WzxUNUqDRtkspTRjeO8NJaJ55AH1drEp8AYonN7vd1XX3KPaRpZUP7P8mpNhgSZ5WiHCXTVbYTBMGQskTNShWUzAW0-VBpJ-qjr36Q5y1nR2gJ3_pzEWZ_htqbAEg_4RSYYady29urMVmFQn_tl58PV7YWqTCDH_YA1FuzguhoU0iahvgkjAFY6o9-wb3q_4ZaCfsz9SNJQ_Tn5UYgbFkoPA7Avj7ZOGQonR6uCRtHmSuQhksFjHH-X3OmB5DQBjYeCYnPFtMUo1rcmG3zZZlc6mirgheU7_L1ixw5ymvJ_emDd7LPdpPTGQ-p6r8gAwl927nE1dCUUP-sb3_XeYGsBLRnMBLweqNs76-toekP5M1jJb5YvkHJlyi9UUZijQg",
            "widthPx": 4032
        },
        {
            "authorAttributions": [
                {
                    "displayName": "Richard Schuster",
                    "photoUri": "https://lh3.googleusercontent.com/a-/ALV-UjXW8OJExee6h9SyK3pt5vVe7LIxsAhC9MRYd39sDHwgzapuDhyUVw=s100-p-k-no-mo",
                    "uri": "https://maps.google.com/maps/contrib/100977422275552690234"
                }
            ],
            "flagContentUri": "https://www.google.com/local/imagery/report/?cb_client=maps_api_places.places_api&image_key=!1e10!2sCIHM0ogKEICAgIC_1_2huwE&hl=en-US",
            "googleMapsUri": "https://www.google.com/maps/place//data=!3m4!1e2!3m2!1sCIHM0ogKEICAgIC_1_2huwE!2e10!4m2!3m1!1s0x487605970abb3463:0x8bad066586d43c5a",
            "heightPx": 3072,
            "name": "places/ChIJYzS7CpcFdkgRWjzUhmUGrYs/photos/AZLasHrkSEr0zVLDbDzn0t9BO2cXKh1t8ZJdsHgbVSiDEcLmNDa_WblBA9ZC08VHG056pqKKAzXVo76Z3vXCdmEzZZcqjnGx24IHR3chJk9IH_RHpb--WSdqryRqvUrcjUz-NUGoC7OLbD-5gv9sfc30jMP68HE8wQC9RkuHXu_vQsVCo4BsPJmV5ZegQZEfs-usEeuHg6T-V3s8EVeU1UuO3NwrX9pRmobaIzDeXaVshK07xgPiJnWL_pW64IRWu8ob5uxJH4cGEDooqWDxcdlCNn8wmcZ2SWn16138DjCVSDQ6rzgkkl3eLByOt9o9dELv-QQYKaslNHswlKKxOORJcPfINbCD4PQkq_Mnla9fjnoTZS_Q1rmZRWbjgtN9IFRxSQmsXX9K7aufZqN93jf-zmIxAamqQg2QX1vCNY81hPp-UBnD",
            "widthPx": 4080
        },
        {
            "authorAttributions": [
                {
                    "displayName": "Takumi Endo",
                    "photoUri": "https://lh3.googleusercontent.com/a-/ALV-UjX3r2JhLGhuTu_bOs_2ME3AQn7ymL_-7rwQK7FKgsTq60KjShJs=s100-p-k-no-mo",
                    "uri": "https://maps.google.com/maps/contrib/116723725642833353538"
                }
            ],
            "flagContentUri": "https://www.google.com/local/imagery/report/?cb_client=maps_api_places.places_api&image_key=!1e10!2sCIHM0ogKEICAgIDvscDDMA&hl=en-US",
            "googleMapsUri": "https://www.google.com/maps/place//data=!3m4!1e2!3m2!1sCIHM0ogKEICAgIDvscDDMA!2e10!4m2!3m1!1s0x487605970abb3463:0x8bad066586d43c5a",
            "heightPx": 3283,
            "name": "places/ChIJYzS7CpcFdkgRWjzUhmUGrYs/photos/AZLasHr17WHlLLW-0Gb3VOhzGzS3eGsiULmUNUmHT9FySDyIP3jkSliOoCYf36pSttM0lFBi2xqo4LGi24XtGXP2nMqocJdeznsnz3xFhNZvC4Bo_jy0b7DPSdV1w38FyR6f1nzgozbUkH1W9DnbxySMI57H2KDKeiP2AYYILZUd_DLWrRj7CBOmRT7s3RMtDHN8A80ep0Tc8VtFfQMOHzMvXWM8DzcP76a6kZScwHYr4IvAb8sj2H9aQH4B9B1k3d-VSWoDCMqZvQO3vAoFwqZ8GRYcrk14eVBOQOUIh4r6A-TDpflwBaM6UpVtR0Bj3vnldKuzEnYCts0dCOvekGZjeDYmmYrbC0jLA7kTMVJzDtJCxc8ZynCBkOpks9HnqP-91jxE3JspXRwkHVnDH8muZg1fQr-aDKmF95_48rNM3NA",
            "widthPx": 3510
        },
        {
            "authorAttributions": [
                {
                    "displayName": "Licia Capra",
                    "photoUri": "https://lh3.googleusercontent.com/a-/ALV-UjUgKRBS8-a8nOmJ-i4gsjzlZ8qbShGfXTliV6dzXsYkCgWwzETC0A=s100-p-k-no-mo",
                    "uri": "https://maps.google.com/maps/contrib/104721598269657934708"
                }
            ],
            "flagContentUri": "https://www.google.com/local/imagery/report/?cb_client=maps_api_places.places_api&image_key=!1e10!2sCIABIhAA3ilWYAGlLGgNFmQABp02&hl=en-US",
            "googleMapsUri": "https://www.google.com/maps/place//data=!3m4!1e2!3m2!1sCIABIhAA3ilWYAGlLGgNFmQABp02!2e10!4m2!3m1!1s0x487605970abb3463:0x8bad066586d43c5a",
            "heightPx": 2299,
            "name": "places/ChIJYzS7CpcFdkgRWjzUhmUGrYs/photos/AZLasHrk_YGvHyS_ZccKSDFY1ST6Tp8J-BVVg05dT6ciZkd_NKLn1GvdvTCrzxpHDFFfKTmN7b58AZ05f_IzYlIYcdUxq15C0QzvnVvkNSUdKdOUCHVhO4q5wcMBeohxy2gmYvW3ekIqZmz901mHy0_eoWW_cS5agYMGbXUFfKyGjHzxCVEH0xf3Q-f-bQS_Tn8s7Zye1R--F089qjxBUk0L83eJLhJnQ5g8aM2AHzkfVKZa9EmUpGej5a8Z9WzJRWdSsL2-L86QVZv5Mg_1YC65kfTdGzlOiG_ethQbvn6mbgxRet7aoLJNi9_CWfdaselWBIzc0BA0fBwov9uAF_1FZi084n57w8t_Y1C6it7xM0AULndF_PtYu8_k4HpsyqOL6e4N8roUnhokuE10hIIeHWJhxJOLdmfNx32Buplvv2j9AhoEimmOy-gk3QsR6Ypx",
            "widthPx": 2298
        },
        {
            "authorAttributions": [
                {
                    "displayName": "Karo",
                    "photoUri": "https://lh3.googleusercontent.com/a/ACg8ocJQJ04C1AUKqexUPDISrNlVgRiygyFzTbcxiNNPQfJkcsX9SOQ=s100-p-k-no-mo",
                    "uri": "https://maps.google.com/maps/contrib/107044225865950722824"
                }
            ],
            "flagContentUri": "https://www.google.com/local/imagery/report/?cb_client=maps_api_places.places_api&image_key=!1e10!2sCIHM0ogKEJWXuJry_NTO4QE&hl=en-US",
            "googleMapsUri": "https://www.google.com/maps/place//data=!3m4!1e2!3m2!1sCIHM0ogKEJWXuJry_NTO4QE!2e10!4m2!3m1!1s0x487605970abb3463:0x8bad066586d43c5a",
            "heightPx": 4800,
            "name": "places/ChIJYzS7CpcFdkgRWjzUhmUGrYs/photos/AZLasHrXUwpOWA_31tUwtLxmqKpWWdlTEkhwodK0qcWeQ2btBTN8jo_fUsBIhKxzfCk_DSRXTcaXBabPeuxJNLOuX9mofAycA7-ghkm7C0Bun_1_oBClsaGgqKSPhSbZhtmj3Ez389-JMIO_B3VhLupWWaZFHCFV6O7y5aR9MjfrwFqqgCCIkj9pmZChhCE9ikPRSbpWCioIe3l6naa_I2c2cBFcroIfB2mjSE0venqcWBkRixxTIQeSyt66jkYXyNKdqBmbtSVnrd_OT-7DAmpogj5hLXDZhxYl19sVSuibfYa9T94sukHztSSnvfL7wDOIkw9fIuE0Upo2-lJHGZKiq3MzTnQL4cW2bxvsw1L2nzPnuSA7cJvwQAXjjiRmKaAuIjdUSrD4Tv7rzp_KEeqjd1ZaBBOtnhyfcuAOU6jA2Cn8ZVS7",
            "widthPx": 3839
        }
    ],
    "plusCode": {
        "compoundCode": "GV6M+RV London, UK",
        "globalCode": "9C3XGV6M+RV"
    },
    "postalAddress": {
        "addressLines": [
            "1 Surrey Street"
        ],
        "languageCode": "en-US",
        "locality": "London",
        "postalCode": "WC2R 2ND",
        "regionCode": "GB"
    },
    "primaryType": "restaurant",
    "primaryTypeDisplayName": {
        "languageCode": "en-US",
        "text": "Restaurant"
    },
    "rating": 4.8,
    "regularOpeningHours": {
        "nextOpenTime": "2025-12-11T12:00:00Z",
        "openNow": false,
        "periods": [
            {
                "close": {
                    "day": 1,
                    "hour": 21,
                    "minute": 30
                },
                "open": {
                    "day": 1,
                    "hour": 12,
                    "minute": 0
                }
            },
            {
                "close": {
                    "day": 2,
                    "hour": 21,
                    "minute": 30
                },
                "open": {
                    "day": 2,
                    "hour": 12,
                    "minute": 0
                }
            },
            {
                "close": {
                    "day": 3,
                    "hour": 21,
                    "minute": 30
                },
                "open": {
                    "day": 3,
                    "hour": 12,
                    "minute": 0
                }
            },
            {
                "close": {
                    "day": 4,
                    "hour": 21,
                    "minute": 30
                },
                "open": {
                    "day": 4,
                    "hour": 12,
                    "minute": 0
                }
            },
            {
                "close": {
                    "day": 5,
                    "hour": 21,
                    "minute": 30
                },
                "open": {
                    "day": 5,
                    "hour": 12,
                    "minute": 0
                }
            },
            {
                "close": {
                    "day": 6,
                    "hour": 21,
                    "minute": 30
                },
                "open": {
                    "day": 6,
                    "hour": 12,
                    "minute": 0
                }
            }
        ],
        "weekdayDescriptions": [
            "Monday: 12:00 – 9:30 PM",
            "Tuesday: 12:00 – 9:30 PM",
            "Wednesday: 12:00 – 9:30 PM",
            "Thursday: 12:00 – 9:30 PM",
            "Friday: 12:00 – 9:30 PM",
            "Saturday: 12:00 – 9:30 PM",
            "Sunday: Closed"
        ]
    },
    "reservable": true,
    "restroom": true,
    "reviewSummary": {
        "disclosureText": {
            "languageCode": "en-US",
            "text": "Summarized with Gemini"
        },
        "flagContentUri": "https://www.google.com/local/review/rap/report?postId=5%401:CAIQACodChtyc19oOmM4eDVhYVFTYndpYVJCRDhQZHdYZkE%7CCAIQACorChtyc19oOmM4eDVhYVFTYndpYVJCRDhQZHdYZkESDAi_2OfEBhD44ZHwAg&d=17924085&t=8",
        "reviewsUri": "https://www.google.com/maps/place//data=!4m4!3m3!1s0x487605970abb3463:0x8bad066586d43c5a!9m1!1b1",
        "text": {
            "languageCode": "en-US",
            "text": "People say this restaurant serves delicious Mediterranean food with fresh, seasonal ingredients, including standout dishes like rabbit, hake, and grilled carrots with labneh. They highlight the innovative menu, the generous portions, and the excellent value, especially the pre-theatre menu. They also like the relaxed yet elegant atmosphere, the beautiful terrace, and the friendly, attentive service."
        }
    },
    "reviews": [
        {
            "authorAttribution": {
                "displayName": "jnistic",
                "photoUri": "https://lh3.googleusercontent.com/a-/ALV-UjV1atCgW7Cpe6avvlxkCWj7OVZE36oghiUPR3apIOz5PZfbng0=s128-c0x00000000-cc-rp-mo-ba5",
                "uri": "https://www.google.com/maps/contrib/105987401898524866119/reviews"
            },
            "flagContentUri": "https://www.google.com/local/review/rap/report?postId=Ci9DQUlRQUNvZENodHljRjlvT2pOQ2VUZFdTekIzUTJ0eVUzRkZkM2x1TkZSRVVYYxAB&d=17924085&t=1",
            "googleMapsUri": "https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT2pOQ2VUZFdTekIzUTJ0eVUzRkZkM2x1TkZSRVVYYxAB!2m1!1s0x487605970abb3463:0x8bad066586d43c5a",
            "name": "places/ChIJYzS7CpcFdkgRWjzUhmUGrYs/reviews/Ci9DQUlRQUNvZENodHljRjlvT2pOQ2VUZFdTekIzUTJ0eVUzRkZkM2x1TkZSRVVYYxAB",
            "originalText": {
                "languageCode": "en",
                "text": "Very nice venue in the Temple area, the food is nice and the staff very welcoming. We had a pleadant dinner, we appreciated the sea bass crudo and the dover sole, the latter in particular was exquisite! The bill is not one of the cheapest, but that's what you get in London :)"
            },
            "publishTime": "2025-12-06T23:48:41.254545406Z",
            "rating": 4,
            "relativePublishTimeDescription": "in the last week",
            "text": {
                "languageCode": "en",
                "text": "Very nice venue in the Temple area, the food is nice and the staff very welcoming. We had a pleadant dinner, we appreciated the sea bass crudo and the dover sole, the latter in particular was exquisite! The bill is not one of the cheapest, but that's what you get in London :)"
            }
        },
        {
            "authorAttribution": {
                "displayName": "Eric D.",
                "photoUri": "https://lh3.googleusercontent.com/a-/ALV-UjVcvtpFKw-ijjk8-26xid3JcE-xjNqrlcqkzm14w5CHFJeL6fHD=s128-c0x00000000-cc-rp-mo-ba5",
                "uri": "https://www.google.com/maps/contrib/107228514290230824692/reviews"
            },
            "flagContentUri": "https://www.google.com/local/review/rap/report?postId=Ci9DQUlRQUNvZENodHljRjlvT2w5Vk1IbHdjVU41VjE4eFVqSTVRVkpOUWtkcFVsRRAB&d=17924085&t=1",
            "googleMapsUri": "https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT2w5Vk1IbHdjVU41VjE4eFVqSTVRVkpOUWtkcFVsRRAB!2m1!1s0x487605970abb3463:0x8bad066586d43c5a",
            "name": "places/ChIJYzS7CpcFdkgRWjzUhmUGrYs/reviews/Ci9DQUlRQUNvZENodHljRjlvT2w5Vk1IbHdjVU41VjE4eFVqSTVRVkpOUWtkcFVsRRAB",
            "originalText": {
                "languageCode": "en",
                "text": "Came here with an ex colleague for lunch on Saturday. Very nice atmosphere. The Torbay prawns were very crunchy and tasty. The merkerel was okay too.\n\nWe had a bottle of the Toklas vermentino and it tastes pretty good. I’m very fond of pinot grigio and vermentino so yea.\n\nStaff was friendly and helpful."
            },
            "publishTime": "2025-11-30T11:35:14.250596627Z",
            "rating": 5,
            "relativePublishTimeDescription": "a week ago",
            "text": {
                "languageCode": "en",
                "text": "Came here with an ex colleague for lunch on Saturday. Very nice atmosphere. The Torbay prawns were very crunchy and tasty. The merkerel was okay too.\n\nWe had a bottle of the Toklas vermentino and it tastes pretty good. I’m very fond of pinot grigio and vermentino so yea.\n\nStaff was friendly and helpful."
            }
        },
        {
            "authorAttribution": {
                "displayName": "Nandini Mazumdar",
                "photoUri": "https://lh3.googleusercontent.com/a-/ALV-UjV3EgtPaQyieHqs-zOg44bAkArAVvo9BJ5wPhpkRhGWCSbUSOsA=s128-c0x00000000-cc-rp-mo-ba7",
                "uri": "https://www.google.com/maps/contrib/107984306658294475601/reviews"
            },
            "flagContentUri": "https://www.google.com/local/review/rap/report?postId=Ci9DQUlRQUNvZENodHljRjlvT25kR00xVnZRemRXYXpWT1dXcFNlalZXTkVJNE1rRRAB&d=17924085&t=1",
            "googleMapsUri": "https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT25kR00xVnZRemRXYXpWT1dXcFNlalZXTkVJNE1rRRAB!2m1!1s0x487605970abb3463:0x8bad066586d43c5a",
            "name": "places/ChIJYzS7CpcFdkgRWjzUhmUGrYs/reviews/Ci9DQUlRQUNvZENodHljRjlvT25kR00xVnZRemRXYXpWT1dXcFNlalZXTkVJNE1rRRAB",
            "originalText": {
                "languageCode": "en",
                "text": "Really loved our meal here - the food was exquisite, the service was flawless, and the ambiance was elegant. Really loved the carrots, the mussels, the fried feta, the mushroom pasta, the mallard and the tarte tatin. Excellent wine list and the staff was lovely. Can’t wait to be back!"
            },
            "publishTime": "2025-11-07T16:01:55.044958775Z",
            "rating": 5,
            "relativePublishTimeDescription": "a month ago",
            "text": {
                "languageCode": "en",
                "text": "Really loved our meal here - the food was exquisite, the service was flawless, and the ambiance was elegant. Really loved the carrots, the mussels, the fried feta, the mushroom pasta, the mallard and the tarte tatin. Excellent wine list and the staff was lovely. Can’t wait to be back!"
            }
        },
        {
            "authorAttribution": {
                "displayName": "Rod Rivera",
                "photoUri": "https://lh3.googleusercontent.com/a-/ALV-UjW3C_a3dMuMxZPnKrq7ZzAkM9qc1OwZAK9p4UlmxNx0VFqwOTqknA=s128-c0x00000000-cc-rp-mo-ba4",
                "uri": "https://www.google.com/maps/contrib/101878726506157443069/reviews"
            },
            "flagContentUri": "https://www.google.com/local/review/rap/report?postId=Ci9DQUlRQUNvZENodHljRjlvT2w5T09ESjNjbU0yVVdSZk4zcENlVVprU1ZKZlFtYxAB&d=17924085&t=1",
            "googleMapsUri": "https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT2w5T09ESjNjbU0yVVdSZk4zcENlVVprU1ZKZlFtYxAB!2m1!1s0x487605970abb3463:0x8bad066586d43c5a",
            "name": "places/ChIJYzS7CpcFdkgRWjzUhmUGrYs/reviews/Ci9DQUlRQUNvZENodHljRjlvT2w5T09ESjNjbU0yVVdSZk4zcENlVVprU1ZKZlFtYxAB",
            "originalText": {
                "languageCode": "en",
                "text": "I enjoy coming to Toklas; the food is simple but with high-quality ingredients and nicely presented. It’s all about going back to basics: fresh, seasonal ingredients. The place is stylish but unpretentious. The location is perfect for meetings, dates, or just waiting until your theatre function starts. Plus, they have a bakery, and their bread is very fresh and tasty. The only criticism is that their ice cream is relatively weak. Other than that, you should book in advance, as it is a popular place and gets crowded. Highly recommended."
            },
            "publishTime": "2025-11-30T02:03:23.247592821Z",
            "rating": 5,
            "relativePublishTimeDescription": "a week ago",
            "text": {
                "languageCode": "en",
                "text": "I enjoy coming to Toklas; the food is simple but with high-quality ingredients and nicely presented. It’s all about going back to basics: fresh, seasonal ingredients. The place is stylish but unpretentious. The location is perfect for meetings, dates, or just waiting until your theatre function starts. Plus, they have a bakery, and their bread is very fresh and tasty. The only criticism is that their ice cream is relatively weak. Other than that, you should book in advance, as it is a popular place and gets crowded. Highly recommended."
            }
        },
        {
            "authorAttribution": {
                "displayName": "Massimiliano Vitali",
                "photoUri": "https://lh3.googleusercontent.com/a/ACg8ocIxvY7Cu_eqoDifeG44XLekojPokrz6PcLy5vGv67Y78RD3oQ=s128-c0x00000000-cc-rp-mo-ba4",
                "uri": "https://www.google.com/maps/contrib/103396829869890275392/reviews"
            },
            "flagContentUri": "https://www.google.com/local/review/rap/report?postId=Ci9DQUlRQUNvZENodHljRjlvT2tGVFUzUjZRM1Y2VG5sdVYxa3RWamN3ZFhaSmRsRRAB&d=17924085&t=1",
            "googleMapsUri": "https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT2tGVFUzUjZRM1Y2VG5sdVYxa3RWamN3ZFhaSmRsRRAB!2m1!1s0x487605970abb3463:0x8bad066586d43c5a",
            "name": "places/ChIJYzS7CpcFdkgRWjzUhmUGrYs/reviews/Ci9DQUlRQUNvZENodHljRjlvT2tGVFUzUjZRM1Y2VG5sdVYxa3RWamN3ZFhaSmRsRRAB",
            "originalText": {
                "languageCode": "en",
                "text": "First time at Toklas and I left very happy. I had very high expectations about this place. We had a very warm welcome, the host took out jackets and told us our table would be ready in a few minutes. We ordered quite a lot of food to share between the 5 of us. Everything was very very good, made on the order with fresh ingredients. The only thing I was not expecting were dried porcini mushrooms in the pasta, I wanted them fresh because they are in season, the dried porcini just overpowered the taste of the dish in my opinion.\nThe location is great, good lighting and very good vibes.\nI was not happy about the service I have to say . Our server at the beginning was really nice but then slowly slowly she changed mood. I asked her details about one of the starters and she moked me because I used the wrong word to call it. Then we felt pushed and speed up to order dessert, despite it was already late and for sure they didn't need the table back or anyway no one told us anything about it.\nOverall a great experience and very good food and wines but I have been to better places in London paying the same price."
            },
            "publishTime": "2025-11-11T16:59:02.720928423Z",
            "rating": 4,
            "relativePublishTimeDescription": "4 weeks ago",
            "text": {
                "languageCode": "en",
                "text": "First time at Toklas and I left very happy. I had very high expectations about this place. We had a very warm welcome, the host took out jackets and told us our table would be ready in a few minutes. We ordered quite a lot of food to share between the 5 of us. Everything was very very good, made on the order with fresh ingredients. The only thing I was not expecting were dried porcini mushrooms in the pasta, I wanted them fresh because they are in season, the dried porcini just overpowered the taste of the dish in my opinion.\nThe location is great, good lighting and very good vibes.\nI was not happy about the service I have to say . Our server at the beginning was really nice but then slowly slowly she changed mood. I asked her details about one of the starters and she moked me because I used the wrong word to call it. Then we felt pushed and speed up to order dessert, despite it was already late and for sure they didn't need the table back or anyway no one told us anything about it.\nOverall a great experience and very good food and wines but I have been to better places in London paying the same price."
            }
        }
    ],
    "servesBeer": true,
    "servesCocktails": true,
    "servesCoffee": true,
    "servesDessert": true,
    "servesDinner": true,
    "servesLunch": true,
    "servesWine": true,
    "shortFormattedAddress": "1 Surrey St, London",
    "timeZone": {
        "id": "Europe/London"
    },
    "types": [
        "wedding_venue",
        "bar",
        "event_venue",
        "restaurant",
        "food",
        "point_of_interest",
        "establishment"
    ],
    "userRatingCount": 992,
    "utcOffsetMinutes": 0,
    "viewport": {
        "high": {
            "latitude": 51.5132877302915,
            "longitude": -0.11398651970849799
        },
        "low": {
            "latitude": 51.5105897697085,
            "longitude": -0.11668448029150202
        }
    },
    "websiteUri": "https://www.toklaslondon.com/",
    "timestamp": 1765447200
}
</pre>
</div>

> The JSON shown above is a **real, unmodified API response** retrieved directly from the official Google Maps Places API.
> 
> The displayed snippet may be **truncated for readability**, but all stored samples in this repository preserve the **original API response exactly as returned by Google**, without transformation or re-mapping.

</details>

---

## 🔹 Features & Capabilities

- Extraction of **all Place Details fields**
- Output consists of **raw, unmodified responses directly returned by the official Google Maps Places API**
- No geographic limitations
- Supports all place types, including:
  - Restaurants, pharmacies, cafes, salons, jewelry stores, supermarkets, and more
- Extraction of **weekly opening hours** and real-time open/closed status
- Extraction of the **latest 5 user reviews**
- Extraction of **up to 10 high-quality place photos**
- Multiple output formats supported: **JSON, CSV, Excel, SQL**, and more

---

## 🧬 Output JSON Field Structure

```
id
name
displayName
├── languageCode
└── text

formattedAddress
addressComponents
├── languageCode
├── longText
├── shortText
└── types

addressDescriptor
├── areas
│   ├── containment
│   ├── displayName
│   │   ├── languageCode
│   │   └── text
│   ├── name
│   └── placeId
└── landmarks
    ├── displayName
    │   ├── languageCode
    │   └── text
    ├── name
    ├── placeId
    ├── spatialRelationship
    ├── straightLineDistanceMeters
    ├── travelDistanceMeters
    └── types

location
├── latitude
└── longitude

googleMapsUri
googleMapsLinks
├── directionsUri
├── photosUri
├── placeUri
├── reviewsUri
└── writeAReviewUri

businessStatus

currentOpeningHours
├── nextOpenTime
├── openNow
├── periods
│   ├── close
│   │   ├── date
│   │   │   ├── day
│   │   │   ├── month
│   │   │   └── year
│   │   ├── day
│   │   ├── hour
│   │   └── minute
│   └── open
│       ├── date
│       │   ├── day
│       │   ├── month
│       │   └── year
│       ├── day
│       ├── hour
│       └── minute
└── weekdayDescriptions

internationalPhoneNumber
nationalPhoneNumber

paymentOptions
├── acceptsCashOnly
└── acceptsDebitCards

dineIn
liveMusic

iconMaskBaseUri
iconBackgroundColor

photos
├── authorAttributions
│   ├── displayName
│   ├── photoUri
│   └── uri
├── flagContentUri
├── googleMapsUri
├── heightPx
├── name
└── widthPx
```

---

## 🔹 Contact

- **Telegram:** https://t.me/parhamkhani  
- **Email:** parhamkhani.ir@gmail.com

