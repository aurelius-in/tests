| Name                                                                 | Estimated Hours |
|----------------------------------------------------------------------|-----------------|
| Resource Allocation and Technology Selection                         | 8               |
| Mapping of excel columns to api response                             | 4               |
| [SPIKE] Kafka consumer and producer setup from start and Gen Al side | 16              |
| Setting up Star-ui and coho-api I code analysis                      | 12              |
| [SPIKE] Identify DB table to store automated Case summary (Gen Al) response | 12          |
| Setup Code Repos and Environs                                        | 4               |
| Kafka consumer and producer lower environments setup for STAR        | 8               |
| Create table to store automated Case summary (Gen Al) response       | 6               |
| Creating data pipeline between STAR and BH GEN AI Library            | 20              |
| Coho API changes to save information in new table                    | 10              |
| Identify all system events required to send Case information for BH Gen Al | 8           |
| (Unfinished) A/ML Analysis and Development                           | 24              |
| Create and Test Prompts                                              | 16              |
| STAR UI changes-Add new drop down value under select action option   | 4               |
| [SPIKE]: Finalize the logic of moving data from case_summary to case_summary_history table for different status | 12 |
| STAR UI changes: Create screen to load case summary                  | 8               |
| [SPIKE]: Finalize the logic of Calling and consuming GenAl repo endpoints | 14          |
| Deployment of starum-kakfa-consumer, starum-kafka-producer and coho-api on lower environment(Dev/QA) | 10  |
| Create get and update case summary endpoint for Case summary loading screen | 6             |
| [SPIKE] Document the flow from Gen Al side                           | 4               |
| Contin Continuous Improvement for DU                                 | 12              |
| Case summary data to be available in the Gen Al with necessary transformations and data attributes mapping. | 20  |
| Gen Al to process the extracted data - clinical guidelines, historical outcomes and pre-auth rules. Analyze and identify critical factors to provide immediate insights and flags potential areas that may require further review | 40 |
| Create prompts for Gen-Al case Summary                               | 8               |
| Transform the prompt for each case input received from STAR         | 8               |
| Care Advocate to be able to view the case Summary Screen in a new tab. | 4             |
| Audit log to track Case summary                                      | 6               |

...

| Name                                                                 | Estimated Hours | Reason                                                                                         |
|----------------------------------------------------------------------|-----------------|------------------------------------------------------------------------------------------------|
| Resource Allocation and Technology Selection                         | 6               | (Reusing resources and knowledge from the STAR project reduces initial setup time)              |
| Mapping of excel columns to api response                             | 3               | (Direct mapping from JSON simplifies the process, less complex than API response mapping)       |
| [SPIKE] Kafka consumer and producer setup from start and Gen Al side | 12              | (Some configurations can be reused, reducing setup and integration time)                        |
| Setting up Star-ui and coho-api I code analysis                      | 9               | (Reusing components and patterns from STAR-ui, less analysis required)                          |
| [SPIKE] Identify DB table to store automated Case summary (Gen Al) response | 9           | (Database design insights from STAR can be applied, reducing exploration time)                   |
| Setup Code Repos and Environs                                        | 3               | (Utilizing existing environments and repositories setups as templates)                           |
| Kafka consumer and producer lower environments setup for STAR        | 6               | (Configuration knowledge from STAR reduces setup effort)                                         |
| Create table to store automated Case summary (Gen Al) response       | 4.5             | (Design from STAR project can be adapted with minor modifications)                               |
| Creating data pipeline between STAR and BH GEN AI Library            | 15              | (Leveraging existing pipeline designs, with adjustments for POD specifics)                       |
| Coho API changes to save information in new table                    | 7.5             | (Similar changes to STAR, with some efficiencies due to reuse of logic and patterns)             |
| Identify all system events required to send Case information for BH Gen Al | 6             | (Less complex due to single JSON source, but some investigation still needed)                    |
| (Unfinished) A/ML Analysis and Development                           | 18              | (Reusing AI models and development insights from STAR, but customization needed)                 |
| Create and Test Prompts                                              | 12              | (Can reuse and adapt prompts from STAR, reducing creation and testing time)                      |
| STAR UI changes-Add new drop down value under select action option   | 3               | (Simpler UI adjustments due to existing patterns)                                                |
| [SPIKE]: Finalize the logic of moving data from case_summary to case_summary_history table for different status | 9  | (Previous project findings apply, reducing the need for extensive logic revisions)              |
| STAR UI changes: Create screen to load case summary                  | 6               | (Adapting existing UI components and screens from STAR, reducing design and development time)    |
| [SPIKE]: Finalize the logic of Calling and consuming GenAl repo endpoints | 10.5        | (Insights and code from STAR accelerate endpoint integration and testing)                        |
| Deployment of starum-kakfa-consumer, starum-kafka-producer and coho-api on lower environment(Dev/QA) | 7.5  | (Reusing deployment strategies and configurations from STAR, with adjustments for POD)          |
| Create get and update case summary endpoint for Case summary loading screen | 4.5           | (Adapting existing endpoints with minor modifications, leveraging STAR project code)             |
| [SPIKE] Document the flow from Gen Al side                           | 3               | (Documentation structure from STAR can be reused, focusing on differences for POD)               |
| Contin Continuous Improvement for DU                                 | 9               | (Leveraging continuous improvement processes from STAR, adapted for POD specifics)               |
| Case summary data to be available in the Gen Al with necessary transformations and data attributes mapping. | 15  | (Efficiencies from reusing data mapping logic, but adjustments needed for POD data structure)   |
| Gen Al to process the extracted data - clinical guidelines, historical outcomes and pre-auth rules. Analyze and identify critical factors to provide immediate insights and flags potential areas that may require further review | 30 | (Utilizing AI insights and models from STAR, with adaptations for POD data specifics)           |
| Create prompts for Gen-Al case Summary                               | 6               | (Prompts can largely be copied with adjustments, reducing development time)                      |
| Transform the prompt for each case input received from STAR         | 6               | (Reusing transformation logic with minor adjustments for POD's data structure)                   |
| Care Advocate to be able to view the case Summary Screen in a new tab. | 3             | (UI component reuse makes this simpler than initial implementation in STAR)                      |
| Audit log to track Case summary                                      | 4.5             | (Leveraging existing audit log solutions from STAR with modifications for POD)                   |
