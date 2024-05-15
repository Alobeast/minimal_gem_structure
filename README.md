# Minimal Gem Structure

## 1. gemspec File:
The gem specification file is essential. It defines metadata about the gem such as its name, version, author, and dependencies. This file is what RubyGems uses to build and install the gem.

## 2. lib Directory:
This directory should contain the Ruby code for the gem. At the very least, it should include a single Ruby file named after your gem. This file is the entry point for requiring the gem in a Ruby program.

## 3. gem publishing:
`gem build gem_name.gemspec`

`gem push gem_name-0.0.1.gem`
