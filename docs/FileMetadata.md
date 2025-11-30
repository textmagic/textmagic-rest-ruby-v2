# TextMagic::FileMetadata

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **type** | **String** | File metadata type. |  |
| **height** | **Integer** |  |  |
| **width** | **Integer** |  |  |
| **preview** | [**FileMetadataPreview**](FileMetadataPreview.md) |  |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::FileMetadata.new(
  type: text,
  height: 1024,
  width: 1024,
  preview: null
)
```

