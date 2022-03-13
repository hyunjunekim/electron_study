#gclient_gn_args_file = 'src/build/config/gclient_args.gni'
gclient_gn_args = [
]

vars = {
  'skia_git': 'https://skia.googlesource.com',
  'skia_revision': '6d19271fb1480980ed524a6fc65f9cc381bd64ce',
}

deps = {
  'src/third_party/skia':
    Var('skia_git') + '/skia.git' + '@' +  Var('skia_revision'),
}

#recursedeps = [
#  'src',
#]
