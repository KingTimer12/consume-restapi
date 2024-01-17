project('consume-restapi', 'cpp',
  version : '0.1',
  default_options : ['warning_level=3'])

deps = []

deps += dependency('libcurl', required: true)
deps += dependency('rapidjson', required: true)

exe = executable('consume_restapi', 'consume_restapi.cpp',
  install : true, dependencies: deps)

test('basic', exe)
