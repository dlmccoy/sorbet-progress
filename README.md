# SorbetProgress

Measure your progress as you adopt [sorbet](https://sorbet.org/). I find that 
measuring progress keeps me motivated, which is crucial to finishing a project.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'sorbet-progress'
```

Then:

    bundle

Or install it yourself:

    gem install sorbet-progress

## Usage

```bash
bundle exec srb tc --metrics-file /tmp/sorbet_metrics.json
# No errors! Great job.
bundle exec sorbet_progress /tmp/sorbet_metrics.json
# SorbetProgress:
# total_signatures 	1563
# total_methods    	5267
# total_classes    	3795
# sigil_ignore     	unknown
# sigil_false      	1
# sigil_true       	12
# sigil_strong     	unknown
# Keep up the good work 👍
```

Not sure what the best format is. Pull requests welcome. It might be nice to
have an overall percentage, for example.

## Contributing

This project does not accept bug reports. Pull requests are welcome.

This project is intended to be a safe, welcoming space for collaboration, and
contributors are expected to adhere to the [code of conduct](/CODE_OF_CONDUCT.md)
