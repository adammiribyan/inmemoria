# A sample Guardfile
# More info at https://github.com/guard/guard#readme

guard 'sass', :output => '/' do
  watch(%r{public/stylesheets/sass/.+\.(scss|sass)})
end

guard 'livereload' do
  watch(%r{app/.+\.(erb|haml)})
  watch(%r{app/helpers/.+\.rb})
  watch(%r{public/.+\.(css|js|html)})
  watch(%r{config/locales/.+\.yml})
end