# Open Search

### Installation
  #### Docker
  Name | URL
  --- | ---
  Install Component | curl -O https://raw.githubusercontent.com/opensearch-project/documentation-website/2.11/assets/examples/docker-compose.yml
  Install Schema | curl -H "Content-Type: application/x-ndjson" -X PUT "https://localhost:9200/ecommerce" -ku admin:admin --data-binary "@ecommerce-field_mappings.json"
  Install Data | curl -H "Content-Type: application/x-ndjson" -X PUT "https://localhost:9200/ecommerce/_bulk" -ku admin:admin --data-binary "@ecommerce.json"
  Search |  curl -H 'Content-Type: application/json' -X GET "https://localhost:9200/ecommerce/_search?pretty=true" -ku admin:admin -d' {"query":{"match":{"customer_first_name":"Sonya"}}}'
  Note | There is a developer tool to test query:   Management > Dev Tools

### Onboarding Data
  #### Upload 
  1. Approach 1 - bulk upload
  2. Apporach 2 - data arrives incrementally
