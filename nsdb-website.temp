# frozen_string_literal: true

Gem::Specification.new do |spec|
  spec.name          = "test-nsdb"
  spec.version       = "0.1.0"
  spec.authors       = ["NSDb Team"]
  spec.email         = ["info@nsdb.io"]

  spec.summary       = "NSDb Website"
  spec.homepage      = "http://nsdb.io"
  spec.license       = "MIT"

  spec.files         = `git ls-files -z`.split("\x0").select { |f| f.match(%r!^(assets|_layouts|_includes|_sass|LICENSE|README)!i) }

  spec.add_runtime_dependency "jekyll", "~> 3.8.5"
  spec.add_runtime_dependency "github-pages", "~> 204"

  spec.add_development_dependency "bundler", "~> 2.1.2"
  spec.add_development_dependency "rake", "~> 12.0"
end
