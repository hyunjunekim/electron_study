#gclient_gn_args_file = 'src/build/config/gclient_args.gni'
gclient_gn_args = [
  'build_with_chromium',
  'checkout_android',
  'checkout_android_native_support',
  'checkout_libaom',
  'checkout_nacl',
  'checkout_pgo_profiles',
  'checkout_oculus_sdk',
  'checkout_openxr',
  'checkout_google_benchmark',
  'mac_xcode_version',
]

vars = {
  'chromium_version':
    '2a55c4f55b99b2191ea59cba1e2f6da4dbb7dee0',
  'node_version':
    'v14.15.0',
  'nan_version':
    '2c4ee8a32a299eada3cd6e468bbd0a473bfea96d',
  'squirrel.mac_version':
    'a3a5b3f03b824441c014893b18f99a103b2603e9',

  'pyyaml_version': '3.12',
  'requests_version': 'e4d59bedfd3c7f4f254f4f5d036587bcd8152458',

  'chromium_git': 'https://chromium.googlesource.com',
  'electron_git': 'https://github.com/electron',
  'nodejs_git': 'https://github.com/nodejs',
  'requests_git': 'https://github.com/kennethreitz',
  'yaml_git': 'https://github.com/yaml',
  'squirrel_git': 'https://github.com/Squirrel',

  # KEEP IN SYNC WITH utils.js FILE
  'yarn_version': '1.15.2',

  # To be able to build clean Chromium from sources.
  'apply_patches': True,

  # To use an mtime cache for patched files to speed up builds.
  'use_mtime_cache': True,

  # To allow in-house builds to checkout those manually.
  'checkout_chromium': True,
  'checkout_node': True,
  'checkout_nan': True,
  'checkout_pgo_profiles': True,

  # It's only needed to parse the native tests configurations.
  'checkout_pyyaml': False,

  # Python "requests" module is used for releases only.
  'checkout_requests': False,

  'mac_xcode_version': 'default',

  # To allow running hooks without parsing the DEPS tree
  'process_deps': True,

  # It is always needed for normal Electron builds,
  # but might be impossible for custom in-house builds.
  'download_external_binaries': True,

  'checkout_nacl':
    False,
  'checkout_libaom':
    True,
  'checkout_oculus_sdk':
    False,
  'checkout_openxr':
    False,
  'build_with_chromium':
    True,
  'checkout_android':
    False,
  'checkout_android_native_support':
    False,
  'checkout_google_benchmark':
    False,
}

recursedeps = [
  'src',
]
