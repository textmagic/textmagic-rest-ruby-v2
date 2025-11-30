# TextMagic::File

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **name** | **String** |  |  |
| **original_name** | **String** |  |  |
| **mime_type** | **String** |  |  |
| **size** | **Integer** |  |  |
| **type** | **String** | File type. |  |
| **created_at** | **Time** |  |  |
| **preview_url** | **String** |  | [optional] |
| **url** | **String** |  | [optional] |
| **metadata** | [**FileMetadata**](FileMetadata.md) |  | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::File.new(
  id: null,
  name: image-66aba1bc787b40.51413958.png,
  original_name: image.png,
  mime_type: image/png,
  size: 1024,
  type: text,
  created_at: null,
  preview_url: https://example.com/image-preview.jpg,
  url: https://example.com/image.png,
  metadata: null
)
```

