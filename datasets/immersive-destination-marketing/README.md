# Immersive Destination Marketing Campaigns  
Part of the Immersive Data Hub by Martin Sambauer  

## Overview  
This dataset presents documented cases of immersive media campaigns used in destination marketing. Each campaign record describes how immersive formats (such as VR or 360° video) were employed by travel and tourism organisations to inspire audiences, engage travellers, and drive bookings or awareness.

## Dataset details  
Title: immersive-destination-marketing  
Folder: `datasets/immersive-destination-marketing/`  
Format: JSON (UTF-8, array of campaign objects, one object per campaign)  
Last update: see the field `data_collection_date` in each record  
Maintainer: Martin Sambauer (martin-sambauer.com)  

## Download and license  

Repository location  
- GitHub repository: `martin-sambauer/immersive-datasets`  
- Dataset folder in the repository:  
  `datasets/immersive-destination-marketing/`  

Direct downloads (raw files)  
- Dataset JSON  
  - Path: `datasets/immersive-destination-marketing/immersive-destination-marketing.json`  
  - Raw: `https://raw.githubusercontent.com/martin-sambauer/immersive-datasets/main/datasets/immersive-destination-marketing/immersive-destination-marketing.json`  

- README  
  - Path: `datasets/immersive-destination-marketing/README.md`  
  - Raw: `https://raw.githubusercontent.com/martin-sambauer/immersive-datasets/main/datasets/immersive-destination-marketing/README.md`  

- Methodology  
  - Path: `datasets/immersive-destination-marketing/methodology.md`  
  - Raw: `https://raw.githubusercontent.com/martin-sambauer/immersive-datasets/main/datasets/immersive-destination-marketing/methodology.md`  

- JSON Schema  
  - Path: `datasets/immersive-destination-marketing/schema.json`  
  - Raw: `https://raw.githubusercontent.com/martin-sambauer/immersive-datasets/main/datasets/immersive-destination-marketing/schema.json`  

License  
- This dataset is licensed under the Creative Commons Attribution 4.0 International license (CC BY 4.0).  
- Full license text:  
  https://creativecommons.org/licenses/by/4.0/  

Required attribution  
When you use, share, adapt or extend this dataset, please include an attribution line like:  

Immersive Destination Marketing dataset, Immersive Data Hub by Martin Sambauer (martin-sambauer.com), licensed under CC BY 4.0.  

This attribution can be placed in papers, dashboards, code repositories, presentations or any other derivative work that uses the dataset.

## Key fields  

`campaign_name`  
  Descriptive name of the campaign as used in public communication or case studies.  

`destination_name`  
  Name of the promoted destination or route (for example a city, region, transport route or multi-destination combination).  

`country`  
  Country primarily associated with the campaign or the commissioning body.  

`country_code`  
  ISO 3166-1 alpha-2 country code for the country field (for example GB, DE, CH, AU, CN, FR).  

`destination_category`  
  Category describing the type of destination, such as `multiple_destinations`, `region`, `transport_route`, `resort_town`, `country`, `city`, `rural_destination`, `natural_attraction`, `resort_area` and similar values used in the dataset.  

`year`  
  Year in which the core campaign took place or was launched.  

`status`  
  Project status such as `completed`, `ongoing` and similar values used in the dataset.  

`data_collection_date`  
  Date when this record was compiled or last verified for the dataset (ISO 8601 date string, for example `2025-11-11`).  

`commissioning_body`  
  Organisation that commissioned the immersive campaign (for example a tour operator, national tourism board, transport operator, museum, attraction or local authority).  

`immersive_format`  
  Specific immersive medium used in the campaign, for example 360° VR films, online 360° videos, full-body VR rigs, browser-based 3D virtual tours, nighttime spectacles or mixed reality experiences.  

`venue_type`  
  Type of venue or context where the experience was delivered, for example in-store travel agencies, websites / social media channels, pop-up lounges, visitor attractions, expo/tradeshow use or nighttime show locations.  

`primary_audience`  
  Main target audience segment for the campaign (for example leisure travellers, travel agents, press and industry stakeholders, families, visitors to a specific region).  

`primary_goal`  
  Main objective of the campaign, such as inspiring bookings, testing conversion impact of immersive formats, positioning a destination or route, supporting accessibility and planning, or refreshing heritage storytelling.  

`verification_status`  
  Qualitative indication of source strength, for example `strong` when multiple independent sources confirm the campaign.  

`delivery_mode`  
  High-level delivery mode for the experience, such as `physical`, `virtual` or combinations that appear in the dataset.  

`format_cluster`  
  Normalised grouping of the immersive_format into clusters such as `vr`, `online_360`, `virtual_tour_3d`, `immersive_walkthrough_or_dark_ride`, `immersive_exhibition`, `ar_or_mr_on_site`, `nighttime_show_or_spectacle` and similar.  

`promotion_location_type`  
  Normalised description of where the promotion is located, such as `off_site_market`, `online_global`, `on_site_destination`, `on_site`.  

`is_flying_theatre`  
  Boolean flag indicating whether a flying theatre system is used as part of the experience.  

`short_description`  
  Concise textual summary of the campaign and how the immersive format was integrated into the experience and sales or communication journey.  

`sources`  
  List of URLs referencing public case studies, press coverage or official destination pages that document the campaign.  

`offsite_destination_promotion`  
  Boolean flag indicating whether the experience promotes destinations offsite from the actual travel product location.  

`delivery_context`  
  Additional context for delivery, for example `in_store`, `online`, `on_site_attraction`, `expo_or_tradeshow`.  

`channel_group`  
  Channel group of the commissioning or operating organisation, such as `tour_operator_or_travel_agency`, `national_tourism_board`, `transport_operator_rail`, `regional_or_state_tourism_board`, `private_attraction_operator`, `heritage_site_or_museum`, `urban_place_maker_or_bid`, `integrated_resort_or_theme_park`, `nature_park_or_conservation_agency`, `food_and_drink_tourism` and similar.  

`budget`, `production_costs`, `visitor_numbers`, `revenue`  
  Numeric or string fields (or `null`) reserved for financial and reach indicators when reliable values are available and sourced.  

`budget_source`, `production_costs_source`, `visitor_numbers_source`, `revenue_source`  
  URLs that document the respective numerical values when they are published.  

`roi`, `sales_uplift`  
  Fields for reported return-on-investment or uplift values when published (for example a percentage increase in bookings).  

`roi_source`, `sales_uplift_source`  
  URLs that document reported ROI or sales uplift figures.  

`additional_information_01`, `additional_information_01_source`  
  Optional additional note and corresponding source URL for further context about a campaign.  

`user_feedback`  
  Object holding information about public social-media feedback searches (currently focused on X/Twitter). It can contain:  

  - `x_posts`: list of example posts with  
    - `post_id`, `author`, `timestamp`, `content_snippet`, `sentiment`, `link`  
    - `engagement` object with `likes`, `reposts`, `replies`  
    - `assessment` (for example `promotional`, `real_user_feedback`)  

  - `x_search`: metadata about the search  
    - `time_range`, `keywords`, `result`  

  - `x_feedback_summary`: aggregated view of findings  
    - `total_posts`, `real_user_feedback`, `promotional`, `assessment`  

`id`  
  Stable dataset identifier for the campaign record (for example `DM_001`, `DM_002`, …).  

## Use cases  

- Analyse how immersive formats are used in travel and destination marketing campaigns.  
- Compare different immersive format clusters across years, destination types and channel groups.  
- Combine with other datasets (for example venue inventories, demographic or tourism statistics) to study potential reach and sector trends.  
- Support strategic planning and storytelling for immersive-media producers, destination marketers, tour operators and transport operators.  

## Notes and limitations  

- The dataset is not exhaustive; it focuses on campaigns that have been publicly documented in case studies, press releases or official destination pages.  
- Some fields (for example budget, visitor_numbers, revenue, ROI) are only populated when trustworthy public numbers were found; otherwise they are left `null`.  
- Reported conversion or ROI values may be self-reported and should be interpreted with care; users are encouraged to check the linked sources.  
- Destination categories and format clusters are normalised by the maintainer and may not always match the exact wording used by the original campaigns.  

## How to use  

1. Download the JSON file from the path or raw URL listed in “Download and license”.  
2. Load the JSON into your preferred environment (for example Python, R, JavaScript, SQL import).  
3. Use the field `id` as a stable key when joining with your own tables.  
4. When extending the dataset, keep the existing field names and value conventions wherever possible, and supply `null` for unknown values rather than inventing data.  
5. Document any additional fields you add in a local data dictionary or schema so that future users and AIs can process them consistently.  

## Contribution and update process  

- Fork the repository on GitHub.  
- Add new campaign objects to `immersive-destination-marketing.json` following the existing field structure.  
- Set `data_collection_date` for each new record.  
- Check for duplicates based on a combination of `commissioning_body`, `campaign_name`, `destination_name` and `year`.  
- If you add new controlled vocabulary values (for example new `format_cluster` labels), keep them consistent and describe them in your pull request.  
- Open a pull request against the main repository so changes can be reviewed and merged.  

## Contact  

For questions, corrections or suggestions about this dataset, please contact:  

martin.sambauer@me.com
martin-sambauer.com  
