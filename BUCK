prebuilt_cxx_library(
  name = 'integer', 
  header_namespace = 'boost', 
  header_only = True, 
  exported_headers = subdir_glob([
    ('include/boost', '**/*.hpp'), 
  ]), 
  deps = [
    'buckaroo.github.buckaroo-pm.boost-assert//:assert', 
    'buckaroo.github.buckaroo-pm.boost-config//:config', 
    'buckaroo.github.buckaroo-pm.boost-static_assert//:static-assert', 
    'buckaroo.github.buckaroo-pm.boost-utility//:utility', 
    'buckaroo.github.buckaroo-pm.boost-detail//:detail', 
  ], 
  visibility = [
    'PUBLIC', 
  ], 
)
