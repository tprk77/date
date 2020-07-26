project(
  'date',
  'cpp',
  version: '3.0.0',
  license: 'MIT'
)

# We are going to ignore TZ because I don't need it

date_incdir = include_directories('include')

date_dep = declare_dependency(
  version : meson.project_version(),
  include_directories : date_incdir
)
