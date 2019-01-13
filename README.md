# RDataset

RDatasets for Ruby.
* [RDatasets](https://github.com/vincentarelbundock/Rdatasets)
* [RDatasets.jl](https://github.com/johnmyleswhite/RDatasets.jl)

## Installation

```bash
git clone https://github.com/kojix2/rdataset
cd rdataset
bundle install
bundle exec rake install
```

## Usage

```ruby
require 'rdataset'
df = Daru::DataFrame.from_rdataset("datasets","iris")
df = RDataset.load("datasets", "iris")
```

## Development & Contributing
Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/rdataset.
