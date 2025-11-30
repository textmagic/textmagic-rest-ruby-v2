# TextMagic::SurveyNode

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **label** | **String** |  |  |
| **body** | **String** |  |  |
| **node_type** | **String** |  |  |
| **is_end_node** | **Boolean** |  |  |
| **send_delay** | **Integer** |  |  |
| **start_nodes** | **Array&lt;String&gt;** |  |  |
| **end_nodes** | **Array&lt;String&gt;** |  |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::SurveyNode.new(
  id: 1,
  label: Question 1,
  body: Hello {First name}! Would you like to participate in a short survey? To continue, just reply Yes.,
  node_type: q,
  is_end_node: false,
  send_delay: 0,
  start_nodes: null,
  end_nodes: null
)
```

