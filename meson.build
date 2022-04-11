project('impel', 'c',
  version : '0.1',
  default_options : ['warning_level=3'])

incdir = include_directories(['.', 'src'])

conf = configuration_data()
cc = meson.get_compiler('c')

subdir('private')
subdir('src')
subdir('libimpel')
