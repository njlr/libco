cxx_library(
  name = 'libco',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('', '*.h'),
  ]),
  srcs = [
    'co_epoll.cpp',
    'co_hook_sys_call.cpp',
    'co_routine.cpp',
    'coctx.cpp',
    'coctx_swap.S',
  ],
  visibility = [
    'PUBLIC',
  ],
)

cxx_binary(
  name = 'example-closure', 
  srcs = [
    'example_closure.cpp'
  ],
  deps = [
    ':libco',
  ],
)

cxx_binary(
  name = 'example-cond', 
  srcs = [
    'example_cond.cpp'
  ],
  deps = [
    ':libco',
  ],
)

cxx_binary(
  name = 'example-copystack', 
  srcs = [
    'example_copystack.cpp'
  ],
  deps = [
    ':libco',
  ],
)

cxx_binary(
  name = 'example-echocli', 
  srcs = [
    'example_echocli.cpp'
  ],
  deps = [
    ':libco',
  ],
)

cxx_binary(
  name = 'example-echosvr', 
  srcs = [
    'example_echosvr.cpp'
  ],
  deps = [
    ':libco',
  ],
)

cxx_binary(
  name = 'example-poll', 
  srcs = [
    'example_poll.cpp'
  ],
  deps = [
    ':libco',
  ],
)

cxx_binary(
  name = 'example-setenv', 
  srcs = [
    'example_setenv.cpp'
  ],
  deps = [
    ':libco',
  ],
)

cxx_binary(
  name = 'example-specific', 
  srcs = [
    'example_specific.cpp'
  ],
  deps = [
    ':libco',
  ],
)

cxx_binary(
  name = 'example-thread', 
  srcs = [
    'example_thread.cpp'
  ],
  deps = [
    ':libco',
  ],
)
