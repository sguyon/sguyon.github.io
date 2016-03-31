source 'https://rubygems.org'

#github-pages contain:
# class Dependencies
#   VERSIONS = {
#     # Jekyll
#     "jekyll"                    => "3.0.3",
#     "jekyll-sass-converter"     => "1.3.0",
#     "jekyll-textile-converter"  => "0.1.0",

#     # Converters
#     "kramdown"                  => "1.10.0",
#     "rdiscount"                 => "2.1.8",
#     "redcarpet"                 => "3.3.3",
#     "RedCloth"                  => "4.2.9",

#     # Misc
#     "liquid"                    => "3.0.6",
#     "rouge"                     => "1.10.1",
#     "github-pages-health-check" => "1.1.0",

#     # Plugins
#     "jemoji"                    => "0.6.2",
#     "jekyll-mentions"           => "1.1.2",
#     "jekyll-redirect-from"      => "0.10.0",
#     "jekyll-sitemap"            => "0.10.0",
#     "jekyll-feed"               => "0.4.0",
#     "jekyll-gist"               => "1.4.0",
#     "jekyll-paginate"           => "1.1.0",
#     "jekyll-coffeescript"       => "1.0.1",
#     "jekyll-seo-tag"            => "1.3.3",
#     "jekyll-github-metadata"    => "1.10.0"
#   }.freeze



# class Configuration
#   # Plugins which are activated by default
#   DEFAULT_PLUGINS = %w(
#     jekyll-coffeescript
#     jekyll-gist
#     jekyll-github-metadata
#     jekyll-paginate
#     jekyll-textile-converter
#   ).freeze

#   # Plugins allowed by GitHub Pages
#   PLUGIN_WHITELIST = %w(
#     jekyll-coffeescript
#     jekyll-feed
#     jekyll-gist
#     jekyll-github-metadata
#     jekyll-mentions
#     jekyll-paginate
#     jekyll-redirect-from
#     jekyll-seo-tag
#     jekyll-sitemap
#     jekyll-textile-converter
#     jemoji
#   ).freeze


# # Default, user overwritable options
#     DEFAULTS = {
#       "jailed"   => false,
#       "gems"     => DEFAULT_PLUGINS,
#       "kramdown" => {
#         "input"     => "GFM",
#         "hard_wrap" => false
#       }
#     }.freeze
# OVERRIDES = {
#       "lsi"         => false,
#       "safe"        => true,
#       "plugins"     => SecureRandom.hex,
#       "whitelist"   => PLUGIN_WHITELIST,
#       "highlighter" => "rouge",
#       "kramdown"    => {
#         "template"           => "",
#         "math_engine"        => "mathjax",
#         "syntax_highlighter" => "rouge"
#       },
#       "gist"        => {
#         "noscript"  => false
#       }
#     }.freeze

group :jekyll_plugins do
  gem 'github-pages'
  gem 'jekyll-coffeescript'
  gem 'jekyll-watch'
  gem 'jekyll-assets'
end


gem 'capistrano'
gem 'capistrano-jekyll' # https://github.com/ne1ro/capistrano-jekyll
gem 'rvm-capistrano' # TODO check config @ https://github.com/capistrano/rvm


#TODO add bootstrap and co
