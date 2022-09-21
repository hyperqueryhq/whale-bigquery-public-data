# `dimensions_ai_covid19.grants`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `id`
* [STRING]    `title`
* [STRING]    `abstract`
* [STRING]    `language`
* [RECORD]    `original_title`
* [STRING]    `original_title.value`
* [STRING]    `original_title.language`
* [RECORD]    `original_abstract`
* [STRING]    `original_abstract.value`
* [STRING]    `original_abstract.language`
* [STRING]    `linkout`
* [STRING]    `grant_number`
* [STRING]    `foa_number`
* [STRING]    `start_date`
* [STRING]    `end_date`
* [INTEGER]   `start_year`
* [INTEGER]   `end_year`
* [INTEGER]   `active_years`
* [RECORD]    `investigators`
* [STRING]    `investigators.first_name`
* [STRING]    `investigators.last_name`
* [STRING]    `investigators.researcher_id`
* [STRING]    `investigators.role`
* [RECORD]    `investigators.affiliations`
* [STRING]    `investigators.affiliations.affiliation`
* [STRING]    `investigators.affiliations.grid_ids`
* [INTEGER]   `investigators.affiliations.cities`
* [STRING]    `investigators.affiliations.countries_territories`
* [STRING]    `investigators.affiliations.states`
* [STRING]    `researcher_ids`
* [STRING]    `research_orgs`
* [RECORD]    `organisation_details`
* [STRING]    `organisation_details.name`
* [STRING]    `organisation_details.city`
* [STRING]    `organisation_details.country`
* [STRING]    `organisation_details.grid_id`
* [INTEGER]   `research_org_cities`
* [STRING]    `research_org_state_codes`
* [STRING]    `research_org_countries`
* [STRING]    `funder_org`
* [INTEGER]   `funder_org_cities`
* [STRING]    `funder_org_state_codes`
* [STRING]    `funder_org_countries`
* [FLOAT]     `funding_amount`
* [STRING]    `funding_currency`
* [FLOAT]     `funding_aud`
* [FLOAT]     `funding_cad`
* [FLOAT]     `funding_chf`
* [FLOAT]     `funding_eur`
* [FLOAT]     `funding_gbp`
* [FLOAT]     `funding_jpy`
* [FLOAT]     `funding_nzd`
* [FLOAT]     `funding_usd`
* [FLOAT]     `funding_cny`
* [RECORD]    `concepts`
* [STRING]    `concepts.concept`
* [FLOAT]     `concepts.relevance`
* [RECORD]    `category_bra`
* [STRING]    `category_bra.values`
* [RECORD]    `category_bra.full`
* [STRING]    `category_bra.full.id`
* [STRING]    `category_bra.full.value`
* [RECORD]    `category_for`
* [RECORD]    `category_for.first_level`
* [STRING]    `category_for.first_level.codes`
* [RECORD]    `category_for.first_level.full`
* [STRING]    `category_for.first_level.full.id`
* [STRING]    `category_for.first_level.full.code`
* [STRING]    `category_for.first_level.full.name`
* [RECORD]    `category_for.second_level`
* [STRING]    `category_for.second_level.codes`
* [RECORD]    `category_for.second_level.full`
* [STRING]    `category_for.second_level.full.id`
* [STRING]    `category_for.second_level.full.code`
* [STRING]    `category_for.second_level.full.name`
* [RECORD]    `category_hra`
* [STRING]    `category_hra.values`
* [RECORD]    `category_hra.full`
* [STRING]    `category_hra.full.id`
* [STRING]    `category_hra.full.value`
* [RECORD]    `category_hrcs_hc`
* [STRING]    `category_hrcs_hc.values`
* [RECORD]    `category_hrcs_hc.full`
* [STRING]    `category_hrcs_hc.full.id`
* [STRING]    `category_hrcs_hc.full.value`
* [RECORD]    `category_hrcs_rac`
* [STRING]    `category_hrcs_rac.codes`
* [RECORD]    `category_hrcs_rac.full`
* [STRING]    `category_hrcs_rac.full.id`
* [STRING]    `category_hrcs_rac.full.code`
* [STRING]    `category_hrcs_rac.full.name`
* [RECORD]    `category_icrp_cso`
* [STRING]    `category_icrp_cso.codes`
* [RECORD]    `category_icrp_cso.full`
* [STRING]    `category_icrp_cso.full.id`
* [STRING]    `category_icrp_cso.full.code`
* [STRING]    `category_icrp_cso.full.name`
* [RECORD]    `category_icrp_ct`
* [STRING]    `category_icrp_ct.values`
* [RECORD]    `category_icrp_ct.full`
* [STRING]    `category_icrp_ct.full.id`
* [STRING]    `category_icrp_ct.full.value`
* [RECORD]    `category_rcdc`
* [STRING]    `category_rcdc.values`
* [RECORD]    `category_rcdc.full`
* [STRING]    `category_rcdc.full.id`
* [STRING]    `category_rcdc.full.value`
* [RECORD]    `category_sdg`
* [STRING]    `category_sdg.codes`
* [RECORD]    `category_sdg.full`
* [STRING]    `category_sdg.full.id`
* [STRING]    `category_sdg.full.code`
* [STRING]    `category_sdg.full.name`
* [RECORD]    `category_uoa`
* [STRING]    `category_uoa.codes`
* [RECORD]    `category_uoa.full`
* [STRING]    `category_uoa.full.id`
* [STRING]    `category_uoa.full.code`
* [STRING]    `category_uoa.full.name`
* [RECORD]    `categories`
* [RECORD]    `categories.bra_v1`
* [STRING]    `categories.bra_v1.values`
* [RECORD]    `categories.bra_v1.full`
* [STRING]    `categories.bra_v1.full.id`
* [STRING]    `categories.bra_v1.full.value`
* [RECORD]    `categories.for_v1`
* [RECORD]    `categories.for_v1.first_level`
* [STRING]    `categories.for_v1.first_level.codes`
* [RECORD]    `categories.for_v1.first_level.full`
* [STRING]    `categories.for_v1.first_level.full.id`
* [STRING]    `categories.for_v1.first_level.full.code`
* [STRING]    `categories.for_v1.first_level.full.name`
* [RECORD]    `categories.for_v1.second_level`
* [STRING]    `categories.for_v1.second_level.codes`
* [RECORD]    `categories.for_v1.second_level.full`
* [STRING]    `categories.for_v1.second_level.full.id`
* [STRING]    `categories.for_v1.second_level.full.code`
* [STRING]    `categories.for_v1.second_level.full.name`
* [RECORD]    `categories.hra_v1`
* [STRING]    `categories.hra_v1.values`
* [RECORD]    `categories.hra_v1.full`
* [STRING]    `categories.hra_v1.full.id`
* [STRING]    `categories.hra_v1.full.value`
* [RECORD]    `categories.hrcs_hc_v1`
* [STRING]    `categories.hrcs_hc_v1.values`
* [RECORD]    `categories.hrcs_hc_v1.full`
* [STRING]    `categories.hrcs_hc_v1.full.id`
* [STRING]    `categories.hrcs_hc_v1.full.value`
* [RECORD]    `categories.hrcs_rac_v1`
* [STRING]    `categories.hrcs_rac_v1.codes`
* [RECORD]    `categories.hrcs_rac_v1.full`
* [STRING]    `categories.hrcs_rac_v1.full.id`
* [STRING]    `categories.hrcs_rac_v1.full.code`
* [STRING]    `categories.hrcs_rac_v1.full.name`
* [RECORD]    `categories.icrp_cso_v1`
* [STRING]    `categories.icrp_cso_v1.codes`
* [RECORD]    `categories.icrp_cso_v1.full`
* [STRING]    `categories.icrp_cso_v1.full.id`
* [STRING]    `categories.icrp_cso_v1.full.code`
* [STRING]    `categories.icrp_cso_v1.full.name`
* [RECORD]    `categories.icrp_ct_v1`
* [STRING]    `categories.icrp_ct_v1.values`
* [RECORD]    `categories.icrp_ct_v1.full`
* [STRING]    `categories.icrp_ct_v1.full.id`
* [STRING]    `categories.icrp_ct_v1.full.value`
* [RECORD]    `categories.rcdc_v1`
* [STRING]    `categories.rcdc_v1.values`
* [RECORD]    `categories.rcdc_v1.full`
* [STRING]    `categories.rcdc_v1.full.id`
* [STRING]    `categories.rcdc_v1.full.value`
* [RECORD]    `categories.sdg_v1`
* [STRING]    `categories.sdg_v1.codes`
* [RECORD]    `categories.sdg_v1.full`
* [STRING]    `categories.sdg_v1.full.id`
* [STRING]    `categories.sdg_v1.full.code`
* [STRING]    `categories.sdg_v1.full.name`
* [RECORD]    `categories.uoa_v1`
* [STRING]    `categories.uoa_v1.codes`
* [RECORD]    `categories.uoa_v1.full`
* [STRING]    `categories.uoa_v1.full.id`
* [STRING]    `categories.uoa_v1.full.code`
* [STRING]    `categories.uoa_v1.full.name`
* [RECORD]    `categories.bra_v2020`
* [STRING]    `categories.bra_v2020.values`
* [RECORD]    `categories.bra_v2020.full`
* [STRING]    `categories.bra_v2020.full.id`
* [STRING]    `categories.bra_v2020.full.value`
* [RECORD]    `categories.for_v2020`
* [RECORD]    `categories.for_v2020.first_level`
* [STRING]    `categories.for_v2020.first_level.codes`
* [RECORD]    `categories.for_v2020.first_level.full`
* [STRING]    `categories.for_v2020.first_level.full.id`
* [STRING]    `categories.for_v2020.first_level.full.code`
* [STRING]    `categories.for_v2020.first_level.full.name`
* [RECORD]    `categories.for_v2020.second_level`
* [STRING]    `categories.for_v2020.second_level.codes`
* [RECORD]    `categories.for_v2020.second_level.full`
* [STRING]    `categories.for_v2020.second_level.full.id`
* [STRING]    `categories.for_v2020.second_level.full.code`
* [STRING]    `categories.for_v2020.second_level.full.name`
* [RECORD]    `categories.hrcs_hc_v2020`
* [STRING]    `categories.hrcs_hc_v2020.values`
* [RECORD]    `categories.hrcs_hc_v2020.full`
* [STRING]    `categories.hrcs_hc_v2020.full.id`
* [STRING]    `categories.hrcs_hc_v2020.full.value`
* [RECORD]    `categories.hrcs_rac_v2020`
* [STRING]    `categories.hrcs_rac_v2020.codes`
* [RECORD]    `categories.hrcs_rac_v2020.full`
* [STRING]    `categories.hrcs_rac_v2020.full.id`
* [STRING]    `categories.hrcs_rac_v2020.full.code`
* [STRING]    `categories.hrcs_rac_v2020.full.name`
* [RECORD]    `categories.icrp_cso_v2020`
* [STRING]    `categories.icrp_cso_v2020.codes`
* [RECORD]    `categories.icrp_cso_v2020.full`
* [STRING]    `categories.icrp_cso_v2020.full.id`
* [STRING]    `categories.icrp_cso_v2020.full.code`
* [STRING]    `categories.icrp_cso_v2020.full.name`
* [RECORD]    `categories.icrp_ct_v2020`
* [STRING]    `categories.icrp_ct_v2020.values`
* [RECORD]    `categories.icrp_ct_v2020.full`
* [STRING]    `categories.icrp_ct_v2020.full.id`
* [STRING]    `categories.icrp_ct_v2020.full.value`
* [RECORD]    `categories.rcdc_v2020`
* [STRING]    `categories.rcdc_v2020.values`
* [RECORD]    `categories.rcdc_v2020.full`
* [STRING]    `categories.rcdc_v2020.full.id`
* [STRING]    `categories.rcdc_v2020.full.value`
* [RECORD]    `categories.for_2020_v2022`
* [RECORD]    `categories.for_2020_v2022.first_level`
* [STRING]    `categories.for_2020_v2022.first_level.codes`
* [RECORD]    `categories.for_2020_v2022.first_level.full`
* [STRING]    `categories.for_2020_v2022.first_level.full.id`
* [STRING]    `categories.for_2020_v2022.first_level.full.code`
* [STRING]    `categories.for_2020_v2022.first_level.full.name`
* [RECORD]    `categories.for_2020_v2022.second_level`
* [STRING]    `categories.for_2020_v2022.second_level.codes`
* [RECORD]    `categories.for_2020_v2022.second_level.full`
* [STRING]    `categories.for_2020_v2022.second_level.full.id`
* [STRING]    `categories.for_2020_v2022.second_level.full.code`
* [STRING]    `categories.for_2020_v2022.second_level.full.name`
* [TIMESTAMP] `date_inserted`
* [TIMESTAMP] `date_imported_gbq`
* [STRING]    `resulting_publication_ids`
* [STRING]    `funder_org_acronyms`

-------------------------------------------------------------------------------
*Do not make edits above this line.*