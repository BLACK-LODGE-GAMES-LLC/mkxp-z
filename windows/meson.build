win = import('windows')

res = files(
'resource.h',
'icon2.ico',
'resource.rc'
)

windows_resources = win.compile_resources('resource.rc', depend_files: res)
