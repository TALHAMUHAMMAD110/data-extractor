## Table of contents

- [General info](#general-info)
- [Requirements](#requirements)
- [Installation](#installation)
- [Technologies Used](#technology-used)
- [Run Commands](#commands)
- [Output](#output)

## General Information

This project is to implement a data extractor that reads out content from "HtmlFile.html” and extracts the below listed information

- Hotel name
- Address
- Classification / stars
- Review points
- Number of reviews
- Description
- Room categories
- Alternative hotels

## Requirements

1. [Python 3.10](https://www.python.org/downloads/)

## Installation

```
$ pip3 install requirements.txt


```

## Technologies Used

Project is created with:

- Python
- BeautifulSoup

## Run Commands

### main project

To run this project just open terminal and run below command

```
python3 main.py


```

### run tests

To run unittest run the below command

```
python3 -m unittest


```

## Output

```
{
    "Hotel name": "Kempinski Hotel Bristol Berlin",
    "address": "Kurfürstendamm 27, Charlottenburg-Wilmersdorf, 10719 Berlin, Germany",
    "stars": "5",
    "reviews_points": "8.3",
    "no_of_reviews": "1401",
    "description": "Stay in the heart of Berlin– This 5-star hotel on Berlin’s Kurfürstendamm shopping street offers elegant rooms, an indoor pool and great public transport links. It is 600 metres from the Gedächtniskirche Church and Berlin Zoo.Kempinski Hotel Bristol Berlin offers air-conditioned rooms with large windows, modern bathrooms and international TV channels. Bathrobes are provided. Free WiFi is available in all areas and high-speed WiFi access can be booked at an additional cost.Gourmet cuisine is served in the popular Kempinski Grill. Reinhard's brasserie offer light cuisine and a terrace overlooking Kurfürstendamm. Guests can enjoy drinks in the Gobelin Halle lounge or in the Bristol Bar.Kempinski Bristol Berlin’s spa includes a sauna, steam room and gym. Massages and beauty treatments can also be booked here. The hotel's business centre can be used free of charge.Uhlandstraße Underground Station is just outside the Kempinski’s front door. The KaDeWe shopping mall is 2 stops away.",
    "rooms_categories": [
        {
            "room_type": "Suite with Balcony",
            "max_persons": "2",
            "no_of_kids": "1"
        },
        {
            "room_type": "Classic Double or Twin Room",
            "max_persons": "2",
            "no_of_kids": "0"
        },
        {
            "room_type": "Superior Double or Twin Room",
            "max_persons": "3",
            "no_of_kids": "0"
        },
        {
            "room_type": "Deluxe Double Room",
            "max_persons": "2",
            "no_of_kids": "0"
        },
        {
            "room_type": "Deluxe Business Suite",
            "max_persons": "2",
            "no_of_kids": "0"
        },
        {
            "room_type": "Junior Suite",
            "max_persons": "3",
            "no_of_kids": "0"
        },
        {
            "room_type": "Family Room",
            "max_persons": "3",
            "no_of_kids": "0"
        }
    ],
    "alternative_hotels": [
        {
            "hotel_name": "Hotel Adlon Kempinski Berlin",
            "hotel_url": "http://www.booking.com/hotel/de/adlon-kempinski-berlin.en-gb.html?label=gen173nr-15CAsoO0IWa2VtcGluc2tpYnJpc3RvbGJlcmxpbkguYgVub3JlZmg7iAEBmAEuuAEEyAEE2AED6AEB;sid=76794d5ed9a9673c09a746b2d3e1a5bd;dcid=4;fs=1;shid=60664;"
        },
        {
            "hotel_name": "Grand Hyatt Berlin",
            "hotel_url": "http://www.booking.com/hotel/de/grand-hyatt-berlin.en-gb.html?label=gen173nr-15CAsoO0IWa2VtcGluc2tpYnJpc3RvbGJlcmxpbkguYgVub3JlZmg7iAEBmAEuuAEEyAEE2AED6AEB;sid=76794d5ed9a9673c09a746b2d3e1a5bd;dcid=4;fs=1;shid=60664;"
        },
        {
            "hotel_name": "Sofitel Berlin Kurfürstendamm",
            "hotel_url": "http://www.booking.com/hotel/de/sofitelhotelberlin-berlin.en-gb.html?label=gen173nr-15CAsoO0IWa2VtcGluc2tpYnJpc3RvbGJlcmxpbkguYgVub3JlZmg7iAEBmAEuuAEEyAEE2AED6AEB;sid=76794d5ed9a9673c09a746b2d3e1a5bd;dcid=4;fs=1;shid=60664;"
        },
        {
            "hotel_name": "Hilton Berlin",
            "hotel_url": "http://www.booking.com/hotel/de/hilton-berlin.en-gb.html?label=gen173nr-15CAsoO0IWa2VtcGluc2tpYnJpc3RvbGJlcmxpbkguYgVub3JlZmg7iAEBmAEuuAEEyAEE2AED6AEB;sid=76794d5ed9a9673c09a746b2d3e1a5bd;dcid=4;fs=1;shid=60664;"
        }
    ]
}


```
