## Description
  PreviewMarkdown is a simple gem that will transform a simple
text area, into an incredible markdown text area.

## Install

If using a Rails or other rack app, add this to the gemfile

```ruby
  gem 'preview_markdown'
```


If using simple Ruby

Run

```ruby
  gem install preview_markdown
```

Add this to the top of your script

```ruby
  require 'preview_markdown'
```

##Usage

To add preview_markdown this to a text area

```ruby
  <% preview_markdown :text_area_name %>
```

### live Preview

To add the live preview functionallity add an empty div

```ruby
  <div id='preview_markdown'></div>
  <% preview_markdown :text_area_name, :preview => true %>
```

