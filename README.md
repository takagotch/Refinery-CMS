### Refinery-CMS
---
https://www.refinerycms.com/

https://github.com/refinery/refinerycms

```rb
// spec/support/refinery/html_helpes.rb
module HtmlHelpers
  RSpec::Matchers.define :xml_eq do |expected|
    match do |actual|
      Hash.from_xml(expected) == Hash.from_xml(actual)
    end
  end
end

```

```
```

```
```


